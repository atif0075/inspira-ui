---
title: Sparkles Text
description: A dynamic text that generates continuous sparkles with smooth transitions, perfect for highlighting text with animated stars.
navBadges:
  - value: New
    type: lime
---

::ComponentLoader{label="Preview" componentName="SparklesTextDemo" type="examples" id="sparkles-text"}
::

## API

| Prop Name       | Type     | Default                                  | Description                                   |
| --------------- | -------- | ---------------------------------------- | --------------------------------------------- |
| `class`         | `string` | `-`                                      | The class to be applied to the sparkles text. |
| `text`          | `string` | ``                                       | The text to display.                          |
| `sparklesCount` | `number` | `10`                                     | sparkles count that appears on the text.      |
| `colors`        | `object` | `{first: '#A07CFE'; second: '#FE8FB5';}` | The sparkles colors.                          |

## Component Code

You can copy and paste the following code to create these components:

::CodeViewer{filename="SparklesText.vue" language="vue" componentName="SparklesText" type="ui" id="sparkles-text"}
::

## Credits

- Credits to [SivaReddy Uppathi](https://github.com/sivareddyuppathi) for this component.
- Inspired from [Magic UI](https://magicui.design/docs/components/sparkles-text).
- Credits to [M Atif](https://github.com/atif0075) for updating this component.