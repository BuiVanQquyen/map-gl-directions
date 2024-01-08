Meey GL Directions
---
This package extend from Mapbox.
### Usage

```javascript
var mapboxgl = require('mapbox-gl');
var MeeyDirections = require('meey-gl-directions');

var directions = new MeeyDirections({
  accessToken: 'YOUR-MAPBOX-ACCESS-TOKEN',
  unit: 'metric',
  profile: 'cycling'
});

var map = new mapboxgl.Map({
  container: 'map',
  style: 'mapbox://styles/mapbox/streets-v12'
});

map.addControl(directions, 'top-left');
```

Live example: https://www.mapbox.com/mapbox-gl-js/example/mapbox-gl-directions/

### Deeper dive

See [API.md](https://github.com/mapbox/mapbox-gl-directions/blob/master/API.md) for complete reference.

### Contributing

See [CONTRIBUTING.md](https://github.com/mapbox/mapbox-gl-directions/blob/master/CONTRIBUTING.md).
