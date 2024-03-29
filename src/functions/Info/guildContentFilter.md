---
title: $guildContentFilter
description: $guildContentFilter will return the guild's content filter level.
id: guildContentFilter
---

`$guildContentFilter` will return the guild's content filter level.

## Usage

```php
$guildContentFilter[guildID?]
```

## Parameters

| Field    | Type    | Description | Required |
|----------|---------|-------------|:--------:|
| guildID? | integer | guild ID    |   true   |

| Type |          |
|------|----------|
| 0    | Disabled |
| 1    | Medium   |
| 2    | High     |

## Example

This will return the content filter level of a specific guild:

```javascript
bot.command({
    name: 'guildContentFilter',
    code: `
  $guildContentFilter[$guildID]
  `
});
```
