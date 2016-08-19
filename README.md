# HoverBox
CSS pattern design for Hover Boxes

## Usage

```HTML
<div class="hover-box">
  <div class="hover-box-icon">
    Icon markup of choice
  </div>
  <div class="hover-box-content">
    <div class="hover-box-main">
      Important text
    </div>
    <div class="hover-box-small">
      Less important text
    </div>
  </div
  [
    <div class="hover-box-action">
      <div class="hover-box-action-content">
      Actions
    </div>
    OR
    </div>
    <div class="hover-box-action-content">
      Actions
    </div>
  ]
</div>
```

## Options

| Name | Element | Type | Values | Description |
| --- | --- | --- | --- | --- |
| Type | `.hover-box` | `class` | `clickable` or `disabled` | Changes the box behavior |
| Size | `.hover-box` | `class` | `s25`, `s30`, `s35`, `s40`, `s45` or `s50` | Changes icon min-width |
| Color | `.hover-box` | `class` or `style` | valid style values | Change the color of the hover box. Define with style or classes  |

There are several ways you can use Hover Box:

- Static hover `.hover-box`
- Clickable  `.hover-box .clickable`
- Disabled  `.hover-box .disabled`
- With actions  `.hover-box`
- With action trigger and nested actions
