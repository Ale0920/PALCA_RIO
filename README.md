# PALCA_RIO# Auto detect text files and perform LF normalization
* text=auto

<!doctype html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="initial-scale=1,user-scalable=no,maximum-scale=1,width=device-width">
        <meta name="mobile-web-app-capable" content="yes">
        <meta name="apple-mobile-web-app-capable" content="yes">
        <link rel="stylesheet" href="./resources/ol.css">
        <link rel="stylesheet" href="resources/fontawesome-all.min.css">
        <link rel="stylesheet" href="./resources/ol-layerswitcher.css">
        <link rel="stylesheet" href="./resources/qgis2web.css">
<style>
.search-layer {
  top: 100px;
  left: .5em;
}
.ol-touch .search-layer {
  top: 130px;
}
</style>
        <style>
        html, body {
            background-color: #ffffff;
        }
        .ol-control button {
            background-color: #f8f8f8 !important;
            color: #000000 !important;
            border-radius: 0px !important;
        }
        .ol-zoom, .geolocate, .gcd-gl-control .ol-control {
            background-color: rgba(255,255,255,.4) !important;
            padding: 3px !important;
        }
        .ol-scale-line {
            background: none !important;
        }
        .ol-scale-line-inner {
            border: 2px solid #f8f8f8 !important;
            border-top: none !important;
            background: rgba(255, 255, 255, 0.5) !important;
            color: black !important;
        }
        </style>

        <style>
        .geolocate {
            top: 65px;
            left: .5em;
        }
        .ol-touch .geolocate {
            top: 80px;
        }
        </style>
        <style>
        html, body, #map {
            width: 100%;
            height: 100%;
            padding: 0;
            margin: 0;
        }
        </style>
        <title></title>
    </head>
    <body>
        <div id="map">
            <div id="popup" class="ol-popup">
                <a href="#" id="popup-closer" class="ol-popup-closer"></a>
                <div id="popup-content"></div>
            </div>
        </div>
        <script src="resources/qgis2web_expressions.js"></script>
<script src="resources/proj4.js"></script>
        <script>proj4.defs('EPSG:32718','+proj=utm +zone=18 +south +datum=WGS84 +units=m +no_defs');</script>
        <script src="resources/polyfills.js"></script>
        <script src="./resources/functions.js"></script>
        <script src="./resources/ol.js"></script>
        <script src="./resources/ol-layerswitcher.js"></script>
        <script src="layers/c_rios_5.js"></script><script src="layers/c_curvas_10.js"></script><script src="layers/c_shp_12.js"></script><script src="layers/Centroide1_13.js"></script>
        <script src="styles/SUBCUENCASZEE2015_1_style.js"></script><script src="styles/c_rios_5_style.js"></script><script src="styles/c_curvas_10_style.js"></script><script src="styles/c_shp_12_style.js"></script><script src="styles/Centroide1_13_style.js"></script>
        <script src="./layers/layers.js" type="text/javascript"></script> 
        <script src="./resources/Autolinker.min.js"></script>
        <script src="./resources/qgis2web.js"></script>
        <script src="http://200.123.29.106:80/geoserver/ows?SERVICE=WFS&VERSION=1.0.0&REQUEST=GetFeature&TYPENAME=geonode:MF_SUBCUENCAS&SRSNAME=EPSG:32718&outputFormat=text%2Fjavascript&format_options=callback%3AgetSUBCUENCASZEE2015_1Json"></script>
    </body>
</html>
