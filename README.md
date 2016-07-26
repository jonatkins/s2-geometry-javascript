s2-geometry-javascript
======================

Porting Google's S2 Geometry Library to Javascript

Currently contains basic support for S2Cell

Simple Examples
---------------

```javascript
var cell = S2.S2Cell.FromLatLng({ lat: 40.2574448, lng: -111.7089464 }, 15);

cell.getNeighbors(); // [ cellLeft, cellDown, cellRight, cellUp ]

cell.getLatLng(); // { lat: 40.2574448, lng: -111.7089464 }
```

More details and examples to come later.
