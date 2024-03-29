---
title: $appendFile
description: $appendFile will add given text to a specific file.
id: appendFile
---

`$appendFile` will add given text to a specific file.

## Usage

```php
$appendFile[file;text;encode?]
```

## Parameters

| Field   | Type    | Description                              | Required |
|---------|---------|------------------------------------------|:--------:|
| file    | integer | file location                            |   true   |
| text    | integer | text to add to the file                  |   true   |
| encode? | integer | encode type <br /> 1. **utf8** (default) |  false   |

## Example

This will add a comment to your main file:

```javascript
bot.command({
    name: 'appendFile',
    code: `
  $appendFile[./index.js;// Hello!]
  `
});
```
