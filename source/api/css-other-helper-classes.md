title: Quasar CSS Helper Classes
---
There are a lot of CSS classes that you can use while writing your Vue templates. Very handy to ease the complexity of your VueModels and templates.

The list below is not complete. Also check the other CSS documentation pages like Typography, Visibility, Shadows, Positioning.

### Mouse Related

| Class Name | Description |
| --- | --- |
| `non-selectable` | User won't be able to select DOM node along with its text |
| `scroll` | Applies CSS tweaks to make scroll work at its best on ALL platforms |
| `no-scroll` | Hides scrollbars on the DOM node |
| `no-pointer-events` | DOM element does not become a target of mouse events - clicks, hover and so on |
| `all-pointer-events` | The opposite of `no-pointer-events` |
| `cursor-pointer` | Change mouse pointer on DOM element to look as if on a clickable link |

### Size Related
| Class Name | Description |
| --- | --- |
| `fit` | Width and Height is set to 100% |
| `full-height` | Height is set to 100% |
| `full-width` | Width is set to 100% |
| `window-height` | Height is set to 100vh with top and bottom margins 0 |
| `window-width` | Width is set to 100vw with left and right margins 0 |
| `block` | Sets `display` property set to `block` |

### Orientation Related
| Class Name | Description |
| --- | --- |
| `rotate-90` | Rotate by 90 degrees |
| `rotate-180` | Rotate by 180 degrees |
| `rotate-270` | Rotate by 270 degrees |
| `flip-horizontal` | Flip DOM element horizontally |
| `flip-vertical` | Flip DOM element vertically |
| `spin` | Apply a continuous spin/rotation to the DOM element |
| `blink` | Apply a blinking effect to the DOM element |

## Border Related
| Class Name | Description |
| --- | --- |
| `no-border` | Removes any border |
| `round-borders` | Applies a generic border radius based on theme |

## Box Model Related
| Class Name | Description |
| --- | --- |
| `no-margin` | Sets margin to "0" |
| `no-padding` | Sets padding to "0" |

## Groups
There's are two special CSS class named `group` and `generic-margin`.

`group` applies a small margin to all children DOM elements, while `generic-margin` applies same margin to the respective DOM element (this varies with each theme).
