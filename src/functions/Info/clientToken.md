---
title: $clientToken
description: $clientToken will return the client's token.
id: clientToken
---

`$clientToken` will return the client's token.

## Usage

```php
$clientToken
```

> ** ⚠ You should never share your Discord Bot Token with anyone.**

## Example

This will return the client's Token:

```javascript
bot.command({
    name: 'clientToken',
    code: `
  $clientToken
  `
});
```