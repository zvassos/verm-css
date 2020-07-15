# verm-css | My own Minimal CSS framework

## General Styles

- Font-size (Using **rem** and **vw**) -- `class="font--xlg"` **=** `font-size: 2rem;`
- Margin (Using **rem** and **vw**) -- `class="mt--xlg"` **=** `margin-top: 5rem;`
- Padding (Using **rem** and **vw**) -- `class="pb--xlg"` **=** `padding-bottom: 5rem;`
- Max-width -- `class="max--500"` **=** `max-width: 500px;`
- Colors -- `class="color--brand"` **=** `color: [your_main_color];`
- Backgrounds -- `class="bg--brand"` **=** `color: [your_main_color];`

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
