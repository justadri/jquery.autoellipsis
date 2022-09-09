# jquery.autoellipsis
jquery.autoellipsis is a jQuery plugin for automatically applying ellipsis on selected elements. This plugin optimally uses the available space, unlike methods like character counting.

## License
jquery.autoellipsis is available on GitHub under MIT license.

## How to use
```javascript
.ellipsis( [selector], [options] )
```
Returns: jQuery

Perform ellipsis on jQuery selection. The optional selector defines the sub-elements which will be affected by the ellipsis operation.

| argument | description |
| -- | -- |
| selector | The selector selecting the sub-elements to perform ellipsis on. If no selector is given, the plugin defaults to performing ellipsis on all child elements. |
| options | A map of additional options to pass to the method. |

**Available options** 

| option | description |
| -- | -- |
| ellipsis | The ellipsis character or string to use. Defaults to "..." (three dots). |
| setTitle | Sets the title attribute of the affected elements with the original content. May be set to either never, onEllipsis or always. When using onEllipsis, the title attribute will only be set when the content of the element was indeed ellipsed. Defaults to never. |
| live | When set to true, perform ellipsis on current and future elements matching the jQuery selection. Also reapplies the ellipsis when the target elements' dimensions change. Use with care, as this mode polls the selection elements. Defaults to false. ||

The method returns the jQuery object for chaining purposes.

## Example

coming soon