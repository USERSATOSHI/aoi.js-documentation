---
title: $guildSplash
description: $guildSplash will return a guild's invite background (if unlocked).
id: guildSplash
---

`$guildSplash` will return a guild's invite background (if unlocked).

## Usage

```php
$guildSplash[guildID?]
```

## Parameters

| Field    | Type    | Description | Required |
|----------|---------|-------------|:--------:|
| guildID? | integer | guild ID    |  false   |

## Example

This will return the guild's invite background (if unlocked):

```javascript
bot.command({
    name: 'guildSplash',
    code: `
  $guildSplash[$guildID]
  `
});
```
