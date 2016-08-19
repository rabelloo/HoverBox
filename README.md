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
  </div>
  {
    <div class="hover-box-action">
      <input readonly />
      <div class="hover-box-action-content">
        Actions
      </div>
    </div>
    
    OR ********
    
    <div class="hover-box-action-content">
      Actions
    </div>
  }
</div>
```

There are several ways you can use Hover Box:

- Static hover
- Clickable
- Disabled
- With actions
- With trigger and nested actions

See examples below.

## Options

| Name | Element | Type | Values | Description |
| --- | --- | --- | --- | --- |
| Type | `.hover-box` | `class` | `clickable` or `disabled` | Changes the box behavior |
| Size | `.hover-box` | `class` | `s25`, `s30`, `s35`, `s40`, `s45` or `s50` | Changes icon min-width |
| Color | `.hover-box` | `class` or `style` | valid style values | Change the color of the hover box. Define with style or classes  |

## Examples

**Static (basic)**
```HTML
<div class="hover-box">
  <div class="hover-box-icon">
    <i class="my-icon"></i>
  </div>
  <div class="hover-box-content">
    <div class="hover-box-main">
      READ ME
    </div>
    <div class="hover-box-small">
      And maybe me too...
    </div>
  </div>
</div>
```

**Clickable**
```HTML
<div class="hover-box clickable">
  ...
  <div class="hover-box-content">
    <div class="hover-box-main">
      CLICK ME
    </div>
  </div>
  ...
</div>
```

**Disabled**
```HTML
<div class="hover-box disabled">
  ...
  <div class="hover-box-content">
    <div class="hover-box-main">
      NO CLICKEY
    </div>
  </div>
  ...
</div>
```

**With actions**
```HTML
<div class="hover-box">
  ...
  <div class="hover-box-action-content">
    <button type="button" class="my-button">Do awesome thing!</button>
  </div>
</div>
```

**With trigger and nested actions**
```HTML
<div class="hover-box">
  ...
  <div class="hover-box-action">
    <input readonly />
    <div class="hover-box-action-content">
      <button type="button" class="my-button">I only show up when the input is :focus'ed!</button>
    </div>
  </div>
</div>
```
