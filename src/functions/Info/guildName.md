---
title: $guildName
description: $guildName will return a guild's name.
id: guildName
---

`$guildName` will return a guild's name.

## Usage

```php
$guildName[guildID?]
```

## Parameters

| Field    | Type    | Description | Required |
|----------|---------|-------------|:--------:|
| guildID? | integer | guild ID    |  false   |

## Example

This will return the name of your guild:

```javascript
bot.command({
    name: 'guildName',
    code: `
  $guildName[$guildID]
  `
});
```
