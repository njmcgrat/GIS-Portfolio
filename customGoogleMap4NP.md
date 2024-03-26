<html>
  <head>
    <meta name="viewport" content="initial-scale=1.0, user-scalable=no">
    <meta charset="utf-8">
    <title>Embedded Map</title>
    <style>
      html, body, #map-canvas {
        height: 100%;
        margin: 0px;
        padding: 0px
      }
    </style>
    <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyDPfHpWqKkKBKArvmkcuCH0LzvFkZRbf9g&callback=initMap"></script>
    <script>
var map;
var infowindow;
function initialize() {
  var mapOptions = {gestureHandling: 'cooperative'}

  map = new google.maps.Map(document.getElementById('map-canvas'), mapOptions);


  var mapLayer = new google.maps.KmlLayer({
    url: "https://www.google.com/maps/d/kml?mid=1d79449301d4b362"  });
  mapLayer.setMap(map);

}

google.maps.event.addDomListener(window, 'load', initialize);

    </script>
  </head>
  <body>
    <div id="map-canvas"></div>
  </body>
</html>
