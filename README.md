# Google Places API Place Types List #

I couldn't find a way to programmatically get [all the possible place types](https://developers.google.com/places/supported_types#table1) so I made one...

```js
const placeTypes = require('google-place-types');

placeTypes.map(type => console.log(type));
```
