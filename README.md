# CSS Font Weight Names

A JSON Object of css font-weight names mapped to their numeric value.

## Usage

``` js
var fontweights = require('css-font-weight-names');

console.dir(fontweights);
```

yields

``` json
{
    "extrathin": 50,
    "hairline": 50,
    "ultrathin": 50,
    "thin": 100,
    "extralight": 200,
	...
}
```

## How was this list generated?

This list represents an standard by consensus, amalgamated from the following sources:

- [W3C]: CSS Fonts Module Level 3 › font-weight
- [WebPlatform]: CSS › Properties › font-weight
- [.NET]: System › Windows › FontWeights
- [Java]: javafx › scene › text › FontWeight
- [TypeKit]: Main › Web Design and Development › Using multiple weights and styles

## Installation

```sh
npm install css-font-weight-names
```

[.NET]: https://msdn.microsoft.com/en-us/library/system.windows.fontweights(v=vs.110).aspx
[Java]: https://docs.oracle.com/javafx/2/api/javafx/scene/text/FontWeight.html
[TypeKit]: http://help.typekit.com/customer/portal/articles/6855-using-multiple-weights-and-styles
[W3C]: http://www.w3.org/TR/css3-fonts/#font-weight-prop
[WebPlatform]: https://docs.webplatform.org/wiki/css/properties/font-weight
