leaflet-color-markers
=====================

color variations of the standard leaflet marker and the OGI OGHAM markers:

| Color | Marker 2x  | Marker  |
| ------------- |:-------------:|:-----:|
| CATTU | ![Marker CATTU 2x](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/CATTU-2x.png) | ![Marker CATTU](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/CATTU.png) |
| CUNA | ![Marker CUNA 2x](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/CUNA-2x.png) | ![Marker CUNA](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/CUNA.png) |
| MUCOI | ![Marker MUCOI 2x](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/MUCOI-2x.png) | ![Marker MUCOI](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/MUCOI.png) |
| LUG | ![Marker LUG 2x](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/LUG-2x.png) | ![Marker LUG](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/LUG.png) |
| ERC | ![Marker ERC 2x](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/ERC-2x.png) | ![Marker ERC](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/ERC.png) |
| DALAGNI | ![Marker DALAGNI 2x](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/DALAGNI-2x.png) | ![Marker DALAGNI](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/DALAGNI.png) |
| DERCMASOC | ![Marker DERCMASOC 2x](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/DERCMASOC-2x.png) | ![Marker DERCMASOC](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/DERCMASOC.png) |
| Blue | ![Marker Red 2x](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/marker-icon-2x-blue.png) | ![Marker Red](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/marker-icon-blue.png) |
| Red | ![Marker Red 2x](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/marker-icon-2x-red.png) | ![Marker Red](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/marker-icon-red.png) |
| Green | ![Marker Green 2x](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/marker-icon-2x-green.png) | ![Marker Green](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/marker-icon-green.png) |
| Orange | ![Marker Orange 2x](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/marker-icon-2x-orange.png) | ![Marker Orange](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/marker-icon-orange.png) |
| Yellow | ![Marker Grey 2x](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/marker-icon-2x-yellow.png) | ![Marker Grey](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/marker-icon-yellow.png) |
| Violet | ![Marker Grey 2x](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/marker-icon-2x-violet.png) | ![Marker Grey](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/marker-icon-violet.png) |
| Grey | ![Marker Grey 2x](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/marker-icon-2x-grey.png) | ![Marker Grey](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/marker-icon-grey.png) |
| Black | ![Marker Grey 2x](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/marker-icon-2x-black.png) | ![Marker Grey](https://raw.githubusercontent.com/ogi-ogham/leaflet-color-markers/master/img/marker-icon-black.png) |

### Usage

```javascript
var greenIcon = new L.Icon({
  iconUrl: 'https://cdn.rawgit.com/ogi-ogham/leaflet-color-markers/master/img/marker-icon-2x-green.png',
  shadowUrl: 'https://cdnjs.cloudflare.com/ajax/libs/leaflet/0.7.7/images/marker-shadow.png',
  iconSize: [25, 41],
  iconAnchor: [12, 41],
  popupAnchor: [1, -34],
  shadowSize: [41, 41]
});

L.marker([51.5, -0.09], {icon: greenIcon}).addTo(map);
```

```javascript
var cattuIcon = new L.Icon({
	iconUrl: 'https://cdn.rawgit.com/ogi-ogham/leaflet-color-markers/master/img/CATTU-2x.png',
	iconSize: [41, 41],
	iconAnchor: [20, 41],
	popupAnchor: [0, -41]
});

L.marker([51.5, -0.09], {icon: cattuIcon}).addTo(map);
```
