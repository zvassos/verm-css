# verm-css | My own Minimal CSS framework

## General Styles

- Font-size -- `class="font--50"` **=** `font-size: calc(35px + 15 * (100vw - 320px) / 1280);`
- Margin -- `class="mt--xlg"` **=** `margin-top: calc(40px + 60 * (100vw - 320px) / 1280);`
- Padding -- `class="pb--xlg"` **=** `padding-bottom: calc(40px + 60 * (100vw - 320px) / 1280);`
- Max-width -- `class="max--500"` **=** `max-width: 500px;`
- Colors -- `class="color--brand"` **=** `color: [your_main_color];`
- Backgrounds -- `class="bg--brand"` **=** `background-color: [your_main_color];`

## Flex Column Example
### Two column row until 768px view port "--um"

```
<div class="cols--um">
    <div class="col--40">This is a 40% width column</div>
    <div class="col--60">This is a 60% width column</div>
</div>
```

### Two column row until 768px view port "--um" & Centered Vertical, Centered Horizontal

```
<div class="cols--um align--center justify--center">
    <div class="col--40">This is a 40% width column</div>
    <div class="col--40">This is a 60% width column</div>
</div>
```
