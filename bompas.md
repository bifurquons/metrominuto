---
title: "Bompas"
order: 7
in_menu: true
---
<!DOCTYPE html>
<html>
<head>
    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://netdna.bootstrapcdn.com/bootstrap/3.0.0/css/bootstrap-glyphicons.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.2.0/css/all.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css"/>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_47ff86c75c59e914af23eed7e70bae87 {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
                .leaflet-container { font-size: 1rem; }
            </style>
        
</head>
<body>
    
    
    <div id="legend" style="
        position: fixed;
        bottom: 70px; right: 20px; width: 320px; min-height: 300px;
        background-color: rgba(255, 255, 255, 1);
        border-radius: 15px; box-shadow: 0px 4px 10px rgba(0,0,0,0.1);
        z-index: 9999; font-size: 14px; font-family: 'Arial', sans-serif;
        padding: 15px;
        display: none;
    ">
        <div style="text-align: center; font-weight: bold; font-size: 16px; margin-bottom: 10px;">
            🗺️ Carte Minute Vélo pour : Bompas
        </div>
        <p style="margin: 5px 0; text-align: center; color: #555;">
            <b>Type de vélo :</b><br>
              Vélo musculaire   <span style="font-size: 13px; position: relative; top: -2px;right:-8px;"></span>
                <span style="font-size: 16px;">🚲</span>   <br><br>

            ⏳ Estimation des temps de trajet par <a href= "https://geovelo.app"> 
<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" role="img" artist="Katerina Limpitsouni" source="https://undraw.co/" width="80px" viewBox="0 0 556.5 101.52">
<path fill="#005A44" fill-rule="evenodd" d="M487 5.969h11v72h-11v-72Zm45.199 73.226c-4.662 0-8.812-1.1-12.45-3.299-3.638-2.262-6.509-5.34-8.612-9.236-2.104-3.895-3.156-8.325-3.156-13.289 0-5.026 1.052-9.456 3.156-13.288 2.103-3.896 4.974-6.943 8.612-9.142 3.638-2.2 7.788-3.299 12.45-3.299 4.718 0 8.896 1.1 12.535 3.299 3.695 2.199 6.566 5.215 8.612 9.047 2.104 3.833 3.155 8.294 3.155 13.383 0 4.964-1.051 9.393-3.155 13.289-2.046 3.895-4.917 6.974-8.612 9.236-3.639 2.2-7.817 3.299-12.535 3.299Zm0-10.085c2.615 0 4.946-.628 6.992-1.885 2.047-1.256 3.638-3.078 4.775-5.466 1.194-2.387 1.791-5.183 1.791-8.388 0-3.267-.597-6.063-1.791-8.388-1.137-2.387-2.728-4.21-4.775-5.466-2.046-1.256-4.349-1.885-6.907-1.885-2.615 0-4.946.629-6.992 1.885-1.99 1.257-3.582 3.079-4.776 5.466-1.193 2.325-1.79 5.121-1.79 8.388 0 3.205.597 6 1.79 8.388 1.194 2.388 2.786 4.21 4.776 5.466 2.046 1.257 4.349 1.885 6.907 1.885Zm-88.214 6.786c3.949 2.2 7.156 3.299 12.401 3.299 4.126 0 6.39-.691 9.573-2.074 3.241-1.445 5.922-3.487 8.044-6.126l-5.923-7.257c-1.65 1.885-3.536 3.267-5.657 4.147l-.144.06c-2.024.84-3.036 1.26-5.627 1.26-3.065 0-4.387-.629-6.744-1.885-2.358-1.257-4.184-3.048-5.481-5.372-.817-1.465-1.376-3.068-1.679-4.807h34.26c.059-.565.089-1.162.089-1.79.059-.629.088-1.194.088-1.697 0-5.278-1.031-9.864-3.094-13.76-3.771-7.123-10.767-12.252-19.384-12.252-8.618 0-15.972 5.2-19.915 12.44-2.063 3.833-3.094 8.263-3.094 13.29 0 4.963 1.061 9.392 3.182 13.288 2.181 3.895 5.216 6.974 9.105 9.236Zm-1.335-26.577c.241-1.888.746-3.584 1.512-5.09 2.018-3.872 5.715-7.162 10.545-7.162s8.461 3.345 10.456 7.068c.834 1.555 1.358 3.283 1.572 5.184H442.65Zm-65.638-20.945h11.658l15.314 37.125 14.143-37.125h11.374L408.55 77.983h-10.687l-20.851-49.61ZM337.42 75.896c3.638 2.2 7.788 3.299 12.45 3.299 4.718 0 8.897-1.1 12.535-3.299 3.695-2.262 6.566-5.34 8.612-9.236 2.104-3.895 3.155-8.325 3.155-13.289 0-5.089-1.051-9.55-3.155-13.383-2.046-3.832-4.917-6.848-8.612-9.047-3.638-2.2-7.817-3.299-12.535-3.299-4.662 0-8.812 1.1-12.45 3.299s-6.509 5.246-8.612 9.142c-2.104 3.832-3.156 8.262-3.156 13.288 0 4.964 1.052 9.393 3.156 13.289 2.103 3.895 4.974 6.974 8.612 9.236Zm19.442-8.67c-2.046 1.256-4.377 1.884-6.992 1.884-2.558 0-4.861-.628-6.907-1.885-1.99-1.256-3.582-3.078-4.776-5.466-1.193-2.387-1.79-5.183-1.79-8.388 0-3.267.597-6.063 1.79-8.388 1.194-2.387 2.786-4.21 4.776-5.466 2.046-1.256 4.377-1.885 6.992-1.885 2.558 0 4.861.629 6.907 1.885 2.047 1.257 3.638 3.079 4.775 5.466 1.194 2.325 1.791 5.121 1.791 8.388 0 3.205-.597 6-1.791 8.388-1.137 2.388-2.728 4.21-4.775 5.466Zm-59.543 11.969c-5.245 0-8.453-1.1-12.401-3.299-3.89-2.262-6.925-5.34-9.105-9.236-2.122-3.895-3.183-8.325-3.183-13.289 0-5.026 1.032-9.456 3.094-13.288 3.944-7.24 11.298-12.44 19.915-12.44 8.618 0 15.614 5.128 19.385 12.251 2.063 3.896 3.094 8.482 3.094 13.76 0 .503-.03 1.068-.089 1.696 0 .629-.029 1.226-.088 1.791h-34.26a15.09 15.09 0 0 0 1.679 4.807c1.296 2.324 3.123 4.115 5.48 5.372 2.358 1.256 3.68 1.885 6.744 1.885 2.591 0 3.603-.42 5.627-1.26l.144-.06c2.122-.88 4.008-2.262 5.658-4.147l5.923 7.257c-2.122 2.64-4.803 4.681-8.045 6.126-3.182 1.383-5.447 2.074-9.572 2.074ZM285.095 44.23c-.767 1.505-1.271 3.201-1.513 5.089h24.086c-.215-1.9-.739-3.629-1.572-5.184-1.996-3.723-5.627-7.068-10.457-7.068-4.83 0-8.527 3.29-10.544 7.163Zm-33.566 32.52c.404-.194.793-.392 1.167-.594v2.723c0 1.711-.316 3.289-.946 4.737l-.002.005c-.61 1.464-1.838 2.678-3.736 3.626l-.004.002c-1.811.937-4.603 1.424-8.42 1.424-1.992 0-3.951-.193-5.878-.578l-.009-.001a46.709 46.709 0 0 1-5.128-1.161c-1.554-.454-2.845-.874-3.874-1.26l-.461-.172v10.095l.233.078c1.772.59 3.996 1.146 6.666 1.667 2.692.591 5.738.885 9.134.885 4.247 0 7.859-.49 10.828-1.48 2.961-.987 5.349-2.375 7.149-4.173 1.853-1.788 3.182-3.846 3.98-6.17.86-2.25 1.288-4.695 1.288-7.33V40.285c0-2.996-.901-5.457-2.725-7.35-1.801-1.932-4.16-3.357-7.065-4.28-2.897-.923-6.117-1.381-9.654-1.381-3.34 0-6.584.393-9.73 1.179a21.24 21.24 0 0 0-8.415 4.06l-.004.002c-2.457 1.993-4.405 4.773-5.851 8.324l-.002.005c-1.385 3.562-2.07 8.123-2.07 13.67 0 5.233.817 9.701 2.466 13.395l.002.004c1.717 3.697 4.231 6.545 7.541 8.531l.007.004c3.375 1.919 7.463 2.903 12.25 2.969h.005c1.913 0 3.826-.264 5.737-.79a28.72 28.72 0 0 0 5.516-1.873l.005-.003Zm-17.095-37.753c2.063-1.562 5.033-2.367 8.955-2.367 1.668 0 3.235.16 4.703.48 1.448.314 2.553.875 3.34 1.662l.009.009.01.008c.807.692 1.245 1.813 1.245 3.444v25.438a20.454 20.454 0 0 1-5.101 2.105 24.91 24.91 0 0 1-5.668.672c-4.397 0-7.594-1.492-9.661-4.435-2.093-2.98-3.154-6.902-3.154-11.792 0-3.287.387-6.276 1.156-8.97.761-2.664 2.151-4.742 4.165-6.253h.001Z" clip-rule="evenodd"/>
<circle cx="32.639" cy="68.883" r="32.639" fill="#3DD693"/>
<circle cx="139.275" cy="68.883" r="32.639" fill="#6FA5FF"/>
<path fill="#005A44" fill-rule="evenodd" d="M70.503 18.206c1.275-5.215.15-9.779-3.027-13.618C63.335-.416 56.45-.803 50.633.946c-2.82.664-4.696 2.539-3.797 5.32 1.023 3.168 4.088 2.043 5.414 1.556.166-.06.304-.111.408-.143.828-.249 1.95-.518 3.171-.629 2.532-.23 4.765.251 6.23 2.02 1.794 2.168 2.418 4.536 1.526 7.805-.887 3.253-3.301 7.427-7.934 12.8A35.587 35.587 0 0 0 42.074 27c-19.713 0-35.694 15.98-35.694 35.693 0 19.713 15.98 35.694 35.694 35.694 19.712 0 35.693-15.98 35.693-35.694 0-12.26-6.181-23.076-15.597-29.502 10.983-10.502 28.885-18.839 48.268-20.656 3.685-.346 6.202-.029 7.791.523 1.549.538 2.004 1.205 2.148 1.551.157.376.253 1.105-.278 2.3-.535 1.201-1.627 2.657-3.4 4.117-8.671 7.14-14.689 14.227-17.139 26.018-1.118 5.381-.547 10.179 1.407 14.216 1.944 4.014 5.134 7.027 8.853 9.08a26.571 26.571 0 0 0 4.274 1.88c4.168 15.087 17.994 26.167 34.408 26.167 19.713 0 35.694-15.98 35.694-35.694 0-19.712-15.981-35.693-35.694-35.693s-35.693 15.98-35.693 35.693c0 .426.007.85.022 1.27-2.477-1.45-4.386-3.393-5.535-5.767-1.198-2.475-1.694-5.666-.851-9.721 2.002-9.635 6.728-15.436 14.724-22.021 2.393-1.97 4.272-4.256 5.354-6.688 1.085-2.44 1.441-5.239.342-7.868-1.112-2.66-3.43-4.475-6.33-5.482-2.861-.994-6.472-1.283-10.753-.882-14.358 1.346-28.105 6.023-39.279 12.67Zm51.557 55.568c4.385.277 8.865-.331 12.925-1.818 5.458-2 9.81-3.769 13.03-5.152l-1.463 5.854a3.515 3.515 0 1 0 6.821 1.705l3.238-12.95a3.516 3.516 0 0 0-1.602-3.866l-10.791-6.475a3.516 3.516 0 0 0-3.618 6.03l5.084 3.05c-3.142 1.36-7.524 3.153-13.117 5.201-3.94 1.443-8.379 1.797-12.478 1.133a28.914 28.914 0 0 1-.249-3.792c0-15.83 12.833-28.662 28.662-28.662 15.83 0 28.662 12.833 28.662 28.662 0 15.83-12.832 28.662-28.662 28.662-11.902 0-22.109-7.254-26.442-17.582Zm-71.233-38.38a66.11 66.11 0 0 0-9.359 16.962c-1.212 3.26-2.295 6.696-2.738 10.162a3.487 3.487 0 0 0 3.056 3.927c2.287.284 3.682-1.085 4.003-3.571.15-1.163.805-4.129 2.27-8.067a59.087 59.087 0 0 1 9.306-16.36c8.035 5.078 13.37 14.04 13.37 24.247 0 15.83-12.832 28.662-28.661 28.662-15.83 0-28.662-12.832-28.662-28.662 0-15.83 12.832-28.662 28.662-28.662 3.052 0 5.993.478 8.753 1.362Z" clip-rule="evenodd"/>
</svg>
 </a>, itinéraire équilibré <br><br>


            💡📐 Conception et réalisation : <a href= "mailto: cartominute@gmail.com">Nouvelles Aires</a> et <a href= "mailto: nathan.blassel@neonab.com">Neonab</a> <br>
        </p>
        <hr style="border: none; height: 1px; background-color: #ddd; margin: 10px 0;">
        <p style="text-align: center; font-weight: bold;">⏱️ Temps de parcours :</p>
        <p style="display: flex; align-items: center;">
            <span style="display: inline-block; width: 20px; height: 20px; background: #71be20; border-radius: 5px; margin-right: 10px;"></span> Moins de 10 minutes
        </p>
        <p style="display: flex; align-items: center;">
            <span style="display: inline-block; width: 20px; height: 20px; background: #7cc3fd; border-radius: 5px; margin-right: 10px;"></span> De 10 à 20 minutes
        </p>
        <p style="display: flex; align-items: center;">
            <span style="display: inline-block; width: 20px; height: 20px; background: #df8ffd; border-radius: 5px; margin-right: 10px;"></span> De 20 à 30 minutes
        </p>
        <p style="display: flex; align-items: center;">
            <span style="display: inline-block; width: 20px; height: 20px; background: #754e84; border-radius: 5px; margin-right: 10px;"></span> De 30 à 45 minutes
        </p>
    </div>
    <button id="toggle-legend" style="
        position: fixed;
        bottom: 20px; right: 20px; width: 320px; height: 45px;
        background-color: rgba(117, 78, 132, 0.70); color: white; font-size: 16px;
        border: none; border-radius: 25px; cursor: pointer;
        box-shadow: 0px 3px 6px rgba(0,0,0,0.2);
        transition: all 0.3s ease;
        z-index: 10000;
    ">
        📜 Afficher la légende
    </button>
    <script>
        document.getElementById('toggle-legend').addEventListener('click', function() {
            var legend = document.getElementById('legend');
            var button = document.getElementById('toggle-legend');
            if (legend.style.display === 'none' || legend.style.display === '') {
                legend.style.display = 'block';
                button.innerHTML = '❌ Masquer la légende';
            } else {
                legend.style.display = 'none';
                button.innerHTML = '📜 Afficher la légende';
            }
        });
    </script>
    
    
            <div class="folium-map" id="map_47ff86c75c59e914af23eed7e70bae87" ></div>
        
</body>
<script>
    
    
            var map_47ff86c75c59e914af23eed7e70bae87 = L.map(
                "map_47ff86c75c59e914af23eed7e70bae87",
                {
                    center: [0.0, 0.0],
                    crs: L.CRS.EPSG3857,
                    ...{
  "zoom": 1,
  "zoomControl": true,
  "preferCanvas": false,
}

                }
            );

            

        
    
            var tile_layer_ec75fe51fa8da4d0548c2e1c5159c019 = L.tileLayer(
                "https://{s}.basemaps.cartocdn.com/light_nolabels/{z}/{x}/{y}{r}.png",
                {
  "minZoom": 8,
  "maxZoom": 20,
  "maxNativeZoom": 20,
  "noWrap": false,
  "attribution": "OpenStreetMap Contributors, CARTO. Made by Neonab with \ud83d\udeb4",
  "subdomains": "abcd",
  "detectRetina": false,
  "tms": false,
  "opacity": 1,
}

            );
        
    
            tile_layer_ec75fe51fa8da4d0548c2e1c5159c019.addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            map_47ff86c75c59e914af23eed7e70bae87.fitBounds(
                [[42.714868349999996, 2.9212736], [42.74104065, 2.9435903999999997]],
                {}
            );
        
    
        function geo_json_ce8ba09da15e82d8e435973f1c10fe24_styler(feature) {
            switch(feature.id) {
                default:
                    return {"color": "white", "fillColor": "black", "fillOpacity": 0.2, "weight": 0};
            }
        }

        function geo_json_ce8ba09da15e82d8e435973f1c10fe24_onEachFeature(feature, layer) {
            layer.on({
            });
        };
        var geo_json_ce8ba09da15e82d8e435973f1c10fe24 = L.geoJson(null, {
                onEachFeature: geo_json_ce8ba09da15e82d8e435973f1c10fe24_onEachFeature,
            
                style: geo_json_ce8ba09da15e82d8e435973f1c10fe24_styler,
            ...{
}
        });

        function geo_json_ce8ba09da15e82d8e435973f1c10fe24_add (data) {
            geo_json_ce8ba09da15e82d8e435973f1c10fe24
                .addData(data);
        }
            geo_json_ce8ba09da15e82d8e435973f1c10fe24_add({"bbox": [-180.0, -90.0, 180.0, 90.0], "features": [{"bbox": [-180.0, -90.0, 180.0, 90.0], "geometry": {"coordinates": [[[-180.0, -90.0], [-180.0, 90.0], [180.0, 90.0], [180.0, -90.0], [-180.0, -90.0]], [[2.9514009896668334, 42.729330299381694], [2.951126934757263, 42.73069444944558], [2.950672813725416, 42.732032225451874], [2.9500429892883115, 42.73333074180108], [2.949243517603711, 42.73457749026328], [2.9482820903074667, 42.73576046054706], [2.947167960735782, 42.736868256096685], [2.9459118550312406, 42.737890203997225], [2.94452586898053, 42.738816457923456], [2.9430233515717346, 42.739638093134914], [2.9414187763910276, 42.74034719259544], [2.939727602098957, 42.74093692338172], [2.9379661233350953, 42.741401602638376], [2.9361513134955004, 42.74173675243874], [2.9343006609084274, 42.741939143017795], [2.932432, 42.74200682395711], [2.9305633390915724, 42.74193914301779], [2.9287126865044995, 42.74173675243874], [2.9268978766649063, 42.741401602638376], [2.92513639790104, 42.74093692338171], [2.9234452236089723, 42.74034719259544], [2.921840648428262, 42.739638093134914], [2.92033813101947, 42.73881645792347], [2.918952144968756, 42.737890203997225], [2.9176960392642255, 42.736868256096685], [2.916581909692522, 42.735760460547056], [2.9156204823962923, 42.73457749026328], [2.9148210107116883, 42.733330741801076], [2.9141911862745755, 42.732032225451874], [2.913737065242737, 42.730694449445586], [2.9134630103331665, 42.729330299381694], [2.913371649218913, 42.72795291405391], [2.9134638496700873, 42.72657555886718], [2.9137387116613374, 42.725211498068084], [2.914193576503937, 42.72387386701997], [2.9148240528966376, 42.72257554575165], [2.915624059627388, 42.7213290349962], [2.9165858844988115, 42.720146335910115], [2.9177002588961267, 42.71903883462712], [2.9189564472682097, 42.71801719275368], [2.920342350651508, 42.71709124485454], [2.9218446232348, 42.716269903909755], [2.923448800840391, 42.715561075646946], [2.9251394400863377, 42.71497158256745], [2.926900266894573, 42.7145070983917], [2.928714332923346, 42.71417209354955], [2.9305641784286256, 42.71396979223531], [2.932432, 42.71390214143704], [2.9342998215713743, 42.71396979223531], [2.936149667076654, 42.71417209354955], [2.937963733105425, 42.7145070983917], [2.939724559913662, 42.71497158256745], [2.9414151991596094, 42.715561075646946], [2.9430193767652, 42.716269903909755], [2.9445216493484923, 42.71709124485454], [2.94590755273179, 42.71801719275368], [2.947163741103873, 42.71903883462712], [2.9482781155011883, 42.7201463359101], [2.9492399403726117, 42.7213290349962], [2.9500399471033623, 42.72257554575165], [2.950670423496063, 42.72387386701997], [2.9511252883386603, 42.725211498068084], [2.9514001503299125, 42.72657555886718], [2.951492350781087, 42.72795291405391], [2.9514009896668334, 42.729330299381694]]], "type": "Polygon"}, "id": "0", "properties": {}, "type": "Feature"}], "type": "FeatureCollection"});

        
    
            geo_json_ce8ba09da15e82d8e435973f1c10fe24.addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var poly_line_fa0a314ac339b6c70f96e988e55a202e = L.polyline(
                [[42.716058, 2.932749], [42.71633228753462, 2.9328714947368426], [42.71660787645429, 2.9329849578947367], [42.71688476675899, 2.9330893894736834], [42.71716295844875, 2.933184789473684], [42.717442451523546, 2.933271157894737], [42.71772324598338, 2.9333484947368422], [42.718005341828245, 2.9334168], [42.71828873905817, 2.9334760736842105], [42.71857343767313, 2.9335263157894738], [42.71885943767313, 2.933567526315789], [42.71914673905817, 2.933599705263158], [42.71943534182825, 2.933622852631579], [42.719725245983376, 2.9336369684210526], [42.72001645152354, 2.933642052631579], [42.720308958448754, 2.9336381052631584], [42.720602766759, 2.9336251263157895], [42.720897876454295, 2.9336031157894737], [42.72119428753462, 2.9335720736842106], [42.721492, 2.933532]],
                {"bubblingMouseEvents": true, "color": "#71be20", "dashArray": "20,10", "dashOffset": null, "fill": false, "fillColor": "#71be20", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 1.0, "smoothFactor": 1.0, "stroke": true, "weight": 7}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
        var popup_5217380788f1c0b0865f3bcda2fed980 = L.popup({"max_width": 1200});
        
            
                var html_7af69df25466198fe0dd8293c96ba978 = $(`<div id="html_7af69df25466198fe0dd8293c96ba978" style="width: 100.0%; height: 100.0%;">             <div style="             font-size: 14px;             font-family: 'Arial', sans-serif;             text-align: center;         ">             <div style="font-weight: bold; font-size: 16px; margin-bottom: 10px;">                   <span style="font-size: 13px; position: relative; top: -2px;right:-8px;"></span>                 <span style="font-size: 16px;">🚲</span>  Itinéraire à Vélo musculaire             </div>             <br>                              Rond-point du millénaire ➡️ Super U : <b><span style="color: #71be20;">3 min</span></b><br>                 Rond-point du millénaire ⬅️ Super U : <b><span style="color: #71be20;">4 min</span></b><br>                  (Moyenne : <b><span style="color: #71be20;">3 min</span></b>)<br>                           <div style="text-align: center; margin-top: 15px;">                 <a href='https://geovelo.app/fr/route/?from=2.932749%2C42.716058&to=2.933532%2C42.721492' target='_blank' style="                     display: inline-block;                     padding: 10px 20px;                     background-color: #71be20;                     color: white;                     text-decoration: none;                     border-radius: 25px;                     font-weight: bold;                     box-shadow: 0px 3px 6px rgba(0,0,0,0.2);                     transition: all 0.3s ease;                 ">Aller à l'itinéraire Géovélo</a>             </div>         </div>      </div>`)[0];
                popup_5217380788f1c0b0865f3bcda2fed980.setContent(html_7af69df25466198fe0dd8293c96ba978);
            
        
        poly_line_fa0a314ac339b6c70f96e988e55a202e.bindPopup(popup_5217380788f1c0b0865f3bcda2fed980);
        ;

        // New behaviour *************
        

        var isMouseOverLine = false;
        var isMouseOverPopup = false;
        var timeoutId = null;

        
        // Open Popup over Line
        poly_line_fa0a314ac339b6c70f96e988e55a202e.on('mouseover', function (e) {
            isMouseOverLine=true;
            this.openPopup();
            if (timeoutId) {
                clearTimeout(timeoutId);
                timeoutId = null;
        }});


        // Check if Mouse is still Over Line
        poly_line_fa0a314ac339b6c70f96e988e55a202e.on('mouseout', function (e) {
            isMouseOverLine=false;});
        
        // Check if Mouse is still over Popup (much more complex)
        document.addEventListener('mousemove', function(e) {
            var popupContainer = document.querySelector('.leaflet-popup');
            if (popupContainer) {
                var rect = popupContainer.getBoundingClientRect();
                var mouseX = e.clientX;
                var mouseY = e.clientY;
        
                isMouseOverPopup = (
                    mouseX >= rect.left &&
                    mouseX <= rect.right &&
                    mouseY >= rect.top &&
                    mouseY <= rect.bottom
                );
                if (isMouseOverPopup && timeoutId) {
                    clearTimeout(timeoutId);
                    timeoutId = null;
        }        }});


        
        // Close Popup if Mouse left the line and the popup for more than 2 seconds

        function ClosePopup(that) {
            setTimeout(function() {
                if (!isMouseOverPopup && !isMouseOverLine) {
                    that.closePopup();
                } else {
                    setTimeout(function() {
                        ClosePopup(that);
                    }, 1000); // 1000 ms = 1s
                }
            }, 2000); // 2000 ms = 2s
        }


        
        poly_line_fa0a314ac339b6c70f96e988e55a202e.on('mouseout', function (e) {
            ClosePopup(this)});

        // End new behaviour *************

        
    
    
            var marker_b91a8565dafa64f4a11a29aa1e6fe59e = L.marker(
                [42.71885943767313, 2.933567526315789],
                {
  "draggable": false,
  "autoPan": true,
  "maxZoom": 20,
  "id": "Rond-point du mill\u00e9naireSuper U",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_9fb331f4c7f00c64bd6befe55762879d = L.divIcon({
  "html": "\n    \u003cdiv style=\"font-size: 12px;\n                color: #71be20;\n                font-weight: bold;\n                width: 70px;\n                position: absolute;\n                top: 00px;\n                left: 00px;\n                text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n          \u003cspan style=\"font-size: 13px; position: relative; top: -2px;right:-8px;\"\u003e\u003c/span\u003e\n                \u003cspan style=\"font-size: 16px;\"\u003e\ud83d\udeb2\u003c/span\u003e 3\u0027\n    \u003c/div\u003e\n    ",
  "className": "empty",
});
            marker_b91a8565dafa64f4a11a29aa1e6fe59e.setIcon(div_icon_9fb331f4c7f00c64bd6befe55762879d);
        
    
                marker_b91a8565dafa64f4a11a29aa1e6fe59e.setIcon(div_icon_9fb331f4c7f00c64bd6befe55762879d);
            
    
            var poly_line_f626a26d9525cf61a75f3b945b213997 = L.polyline(
                [[42.721492, 2.933532], [42.72160725595568, 2.933505541828255], [42.72172078171745, 2.933475935734072], [42.72183257728531, 2.9334431817174513], [42.72194264265928, 2.9334072797783937], [42.722050977839345, 2.933368229916898], [42.72215758282549, 2.933326032132964], [42.722262457617724, 2.933280686426593], [42.722365602216065, 2.9332321927977842], [42.7224670166205, 2.933180551246538], [42.722566700831024, 2.9331257617728537], [42.72266465484765, 2.9330678243767316], [42.72276087867036, 2.9330067390581718], [42.722855372299165, 2.9329425058171745], [42.72294813573407, 2.93287512465374], [42.72303916897507, 2.932804595567867], [42.723128472022154, 2.932730918559557], [42.72321604487534, 2.932654093628809], [42.723301887534625, 2.9325741207756235], [42.723386, 2.932491]],
                {"bubblingMouseEvents": true, "color": "#71be20", "dashArray": "20,10", "dashOffset": null, "fill": false, "fillColor": "#71be20", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 1.0, "smoothFactor": 1.0, "stroke": true, "weight": 7}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
        var popup_2f7564c22b3bf208925e486981554053 = L.popup({"max_width": 1200});
        
            
                var html_c01e0c6a7fd01afa2838c48ce21c329b = $(`<div id="html_c01e0c6a7fd01afa2838c48ce21c329b" style="width: 100.0%; height: 100.0%;">             <div style="             font-size: 14px;             font-family: 'Arial', sans-serif;             text-align: center;         ">             <div style="font-weight: bold; font-size: 16px; margin-bottom: 10px;">                   <span style="font-size: 13px; position: relative; top: -2px;right:-8px;"></span>                 <span style="font-size: 16px;">🚲</span>  Itinéraire à Vélo musculaire             </div>             <br>                              Super U ➡️ Le fournil de l'épi d'or : <b><span style="color: #71be20;">2 min</span></b><br>                 Super U ⬅️ Le fournil de l'épi d'or : <b><span style="color: #71be20;">2 min</span></b><br>                  (Moyenne : <b><span style="color: #71be20;">2 min</span></b>)<br>                           <div style="text-align: center; margin-top: 15px;">                 <a href='https://geovelo.app/fr/route/?from=2.933532%2C42.721492&to=2.932491%2C42.723386' target='_blank' style="                     display: inline-block;                     padding: 10px 20px;                     background-color: #71be20;                     color: white;                     text-decoration: none;                     border-radius: 25px;                     font-weight: bold;                     box-shadow: 0px 3px 6px rgba(0,0,0,0.2);                     transition: all 0.3s ease;                 ">Aller à l'itinéraire Géovélo</a>             </div>         </div>      </div>`)[0];
                popup_2f7564c22b3bf208925e486981554053.setContent(html_c01e0c6a7fd01afa2838c48ce21c329b);
            
        
        poly_line_f626a26d9525cf61a75f3b945b213997.bindPopup(popup_2f7564c22b3bf208925e486981554053);
        ;

        // New behaviour *************
        

        var isMouseOverLine = false;
        var isMouseOverPopup = false;
        var timeoutId = null;

        
        // Open Popup over Line
        poly_line_f626a26d9525cf61a75f3b945b213997.on('mouseover', function (e) {
            isMouseOverLine=true;
            this.openPopup();
            if (timeoutId) {
                clearTimeout(timeoutId);
                timeoutId = null;
        }});


        // Check if Mouse is still Over Line
        poly_line_f626a26d9525cf61a75f3b945b213997.on('mouseout', function (e) {
            isMouseOverLine=false;});
        
        // Check if Mouse is still over Popup (much more complex)
        document.addEventListener('mousemove', function(e) {
            var popupContainer = document.querySelector('.leaflet-popup');
            if (popupContainer) {
                var rect = popupContainer.getBoundingClientRect();
                var mouseX = e.clientX;
                var mouseY = e.clientY;
        
                isMouseOverPopup = (
                    mouseX >= rect.left &&
                    mouseX <= rect.right &&
                    mouseY >= rect.top &&
                    mouseY <= rect.bottom
                );
                if (isMouseOverPopup && timeoutId) {
                    clearTimeout(timeoutId);
                    timeoutId = null;
        }        }});


        
        // Close Popup if Mouse left the line and the popup for more than 2 seconds

        function ClosePopup(that) {
            setTimeout(function() {
                if (!isMouseOverPopup && !isMouseOverLine) {
                    that.closePopup();
                } else {
                    setTimeout(function() {
                        ClosePopup(that);
                    }, 1000); // 1000 ms = 1s
                }
            }, 2000); // 2000 ms = 2s
        }


        
        poly_line_f626a26d9525cf61a75f3b945b213997.on('mouseout', function (e) {
            ClosePopup(this)});

        // End new behaviour *************

        
    
    
            var marker_1fa0592e2eed80f4a515c3c630a7bb2c = L.marker(
                [42.722566700831024, 2.9331257617728537],
                {
  "draggable": false,
  "autoPan": true,
  "maxZoom": 20,
  "id": "Super ULe fournil de l\u0027\u00e9pi d\u0027or",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_6a05fc239c1e3c65d66808c5d843d964 = L.divIcon({
  "html": "\n    \u003cdiv style=\"font-size: 12px;\n                color: #71be20;\n                font-weight: bold;\n                width: 70px;\n                position: absolute;\n                top: 00px;\n                left: 00px;\n                text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n          \u003cspan style=\"font-size: 13px; position: relative; top: -2px;right:-8px;\"\u003e\u003c/span\u003e\n                \u003cspan style=\"font-size: 16px;\"\u003e\ud83d\udeb2\u003c/span\u003e 2\u0027\n    \u003c/div\u003e\n    ",
  "className": "empty",
});
            marker_1fa0592e2eed80f4a515c3c630a7bb2c.setIcon(div_icon_6a05fc239c1e3c65d66808c5d843d964);
        
    
                marker_1fa0592e2eed80f4a515c3c630a7bb2c.setIcon(div_icon_6a05fc239c1e3c65d66808c5d843d964);
            
    
            var poly_line_81597c8a501fe398d656f88580e3af35 = L.polyline(
                [[42.723386, 2.932491], [42.72351200221607, 2.932625673684211], [42.723640893074794, 2.932755547368421], [42.72377267257617, 2.9328806210526315], [42.723907340720224, 2.9330008947368422], [42.724044897506936, 2.9331163684210533], [42.72418534293629, 2.9332270421052633], [42.7243286770083, 2.9333329157894736], [42.72447489972299, 2.9334339894736847], [42.72462401108034, 2.9335302631578957], [42.72477601108033, 2.9336217368421056], [42.72493089972299, 2.9337084105263163], [42.72508867700831, 2.9337902842105263], [42.72524934293629, 2.933867357894737], [42.72541289750692, 2.9339396315789474], [42.72557934072022, 2.934007105263158], [42.725748672576174, 2.9340697789473684], [42.725920893074786, 2.934127652631579], [42.72609600221606, 2.9341807263157893], [42.726274, 2.934229]],
                {"bubblingMouseEvents": true, "color": "#71be20", "dashArray": "20,10", "dashOffset": null, "fill": false, "fillColor": "#71be20", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 1.0, "smoothFactor": 1.0, "stroke": true, "weight": 7}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
        var popup_e55bd1f51b6453ff5b930829a672d25c = L.popup({"max_width": 1200});
        
            
                var html_48c2a48d45968f568111cb3ae6f131c3 = $(`<div id="html_48c2a48d45968f568111cb3ae6f131c3" style="width: 100.0%; height: 100.0%;">             <div style="             font-size: 14px;             font-family: 'Arial', sans-serif;             text-align: center;         ">             <div style="font-weight: bold; font-size: 16px; margin-bottom: 10px;">                   <span style="font-size: 13px; position: relative; top: -2px;right:-8px;"></span>                 <span style="font-size: 16px;">🚲</span>  Itinéraire à Vélo musculaire             </div>             <br>                              Le fournil de l'épi d'or ➡️ École Jean Moulin : <b><span style="color: #71be20;">2 min</span></b><br>                 Le fournil de l'épi d'or ⬅️ École Jean Moulin : <b><span style="color: #71be20;">3 min</span></b><br>                  (Moyenne : <b><span style="color: #71be20;">2 min</span></b>)<br>                           <div style="text-align: center; margin-top: 15px;">                 <a href='https://geovelo.app/fr/route/?from=2.932491%2C42.723386&to=2.934229%2C42.726274' target='_blank' style="                     display: inline-block;                     padding: 10px 20px;                     background-color: #71be20;                     color: white;                     text-decoration: none;                     border-radius: 25px;                     font-weight: bold;                     box-shadow: 0px 3px 6px rgba(0,0,0,0.2);                     transition: all 0.3s ease;                 ">Aller à l'itinéraire Géovélo</a>             </div>         </div>      </div>`)[0];
                popup_e55bd1f51b6453ff5b930829a672d25c.setContent(html_48c2a48d45968f568111cb3ae6f131c3);
            
        
        poly_line_81597c8a501fe398d656f88580e3af35.bindPopup(popup_e55bd1f51b6453ff5b930829a672d25c);
        ;

        // New behaviour *************
        

        var isMouseOverLine = false;
        var isMouseOverPopup = false;
        var timeoutId = null;

        
        // Open Popup over Line
        poly_line_81597c8a501fe398d656f88580e3af35.on('mouseover', function (e) {
            isMouseOverLine=true;
            this.openPopup();
            if (timeoutId) {
                clearTimeout(timeoutId);
                timeoutId = null;
        }});


        // Check if Mouse is still Over Line
        poly_line_81597c8a501fe398d656f88580e3af35.on('mouseout', function (e) {
            isMouseOverLine=false;});
        
        // Check if Mouse is still over Popup (much more complex)
        document.addEventListener('mousemove', function(e) {
            var popupContainer = document.querySelector('.leaflet-popup');
            if (popupContainer) {
                var rect = popupContainer.getBoundingClientRect();
                var mouseX = e.clientX;
                var mouseY = e.clientY;
        
                isMouseOverPopup = (
                    mouseX >= rect.left &&
                    mouseX <= rect.right &&
                    mouseY >= rect.top &&
                    mouseY <= rect.bottom
                );
                if (isMouseOverPopup && timeoutId) {
                    clearTimeout(timeoutId);
                    timeoutId = null;
        }        }});


        
        // Close Popup if Mouse left the line and the popup for more than 2 seconds

        function ClosePopup(that) {
            setTimeout(function() {
                if (!isMouseOverPopup && !isMouseOverLine) {
                    that.closePopup();
                } else {
                    setTimeout(function() {
                        ClosePopup(that);
                    }, 1000); // 1000 ms = 1s
                }
            }, 2000); // 2000 ms = 2s
        }


        
        poly_line_81597c8a501fe398d656f88580e3af35.on('mouseout', function (e) {
            ClosePopup(this)});

        // End new behaviour *************

        
    
    
            var marker_a48e4389faef02aae80c347ce425b53a = L.marker(
                [42.72477601108033, 2.9336217368421056],
                {
  "draggable": false,
  "autoPan": true,
  "maxZoom": 20,
  "id": "Le fournil de l\u0027\u00e9pi d\u0027or\u00c9cole Jean Moulin",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_85d37213044faaecbd49ac2ef617c421 = L.divIcon({
  "html": "\n    \u003cdiv style=\"font-size: 12px;\n                color: #71be20;\n                font-weight: bold;\n                width: 70px;\n                position: absolute;\n                top: 00px;\n                left: 00px;\n                text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n          \u003cspan style=\"font-size: 13px; position: relative; top: -2px;right:-8px;\"\u003e\u003c/span\u003e\n                \u003cspan style=\"font-size: 16px;\"\u003e\ud83d\udeb2\u003c/span\u003e 2\u0027\n    \u003c/div\u003e\n    ",
  "className": "empty",
});
            marker_a48e4389faef02aae80c347ce425b53a.setIcon(div_icon_85d37213044faaecbd49ac2ef617c421);
        
    
                marker_a48e4389faef02aae80c347ce425b53a.setIcon(div_icon_85d37213044faaecbd49ac2ef617c421);
            
    
            var poly_line_93cbbab344506e75c794d22d2b511264 = L.polyline(
                [[42.726274, 2.934229], [42.72645729473684, 2.9343091944598347], [42.72664141052631, 2.9343833673130195], [42.72682634736841, 2.9344515185595568], [42.72701210526316, 2.9345136481994465], [42.727198684210535, 2.9345697562326882], [42.72738608421053, 2.93461984265928], [42.727574305263154, 2.9346639074792242], [42.72776334736842, 2.934701950692521], [42.72795321052632, 2.93473397229917], [42.72814389473684, 2.9347599722991697], [42.7283354, 2.934779950692521], [42.72852772631579, 2.934793907479225], [42.72872087368421, 2.9348018426592803], [42.72891484210527, 2.934803756232687], [42.72910963157895, 2.934799648199446], [42.72930524210526, 2.9347895185595574], [42.72950167368421, 2.9347733673130194], [42.72969892631579, 2.934751194459834], [42.729897, 2.934723]],
                {"bubblingMouseEvents": true, "color": "#71be20", "dashArray": "20,10", "dashOffset": null, "fill": false, "fillColor": "#71be20", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 1.0, "smoothFactor": 1.0, "stroke": true, "weight": 7}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
        var popup_a8d8aaa2413b3bbe8756e73cb9f3f5bf = L.popup({"max_width": 1200});
        
            
                var html_ef5942a1ab02cfdea5797c68851fed4b = $(`<div id="html_ef5942a1ab02cfdea5797c68851fed4b" style="width: 100.0%; height: 100.0%;">             <div style="             font-size: 14px;             font-family: 'Arial', sans-serif;             text-align: center;         ">             <div style="font-weight: bold; font-size: 16px; margin-bottom: 10px;">                   <span style="font-size: 13px; position: relative; top: -2px;right:-8px;"></span>                 <span style="font-size: 16px;">🚲</span>  Itinéraire à Vélo musculaire             </div>             <br>                              École Jean Moulin ➡️ Hôtel de ville : <b><span style="color: #71be20;">2 min</span></b><br>                 École Jean Moulin ⬅️ Hôtel de ville : <b><span style="color: #71be20;">3 min</span></b><br>                  (Moyenne : <b><span style="color: #71be20;">2 min</span></b>)<br>                           <div style="text-align: center; margin-top: 15px;">                 <a href='https://geovelo.app/fr/route/?from=2.934229%2C42.726274&to=2.934723%2C42.729897' target='_blank' style="                     display: inline-block;                     padding: 10px 20px;                     background-color: #71be20;                     color: white;                     text-decoration: none;                     border-radius: 25px;                     font-weight: bold;                     box-shadow: 0px 3px 6px rgba(0,0,0,0.2);                     transition: all 0.3s ease;                 ">Aller à l'itinéraire Géovélo</a>             </div>         </div>      </div>`)[0];
                popup_a8d8aaa2413b3bbe8756e73cb9f3f5bf.setContent(html_ef5942a1ab02cfdea5797c68851fed4b);
            
        
        poly_line_93cbbab344506e75c794d22d2b511264.bindPopup(popup_a8d8aaa2413b3bbe8756e73cb9f3f5bf);
        ;

        // New behaviour *************
        

        var isMouseOverLine = false;
        var isMouseOverPopup = false;
        var timeoutId = null;

        
        // Open Popup over Line
        poly_line_93cbbab344506e75c794d22d2b511264.on('mouseover', function (e) {
            isMouseOverLine=true;
            this.openPopup();
            if (timeoutId) {
                clearTimeout(timeoutId);
                timeoutId = null;
        }});


        // Check if Mouse is still Over Line
        poly_line_93cbbab344506e75c794d22d2b511264.on('mouseout', function (e) {
            isMouseOverLine=false;});
        
        // Check if Mouse is still over Popup (much more complex)
        document.addEventListener('mousemove', function(e) {
            var popupContainer = document.querySelector('.leaflet-popup');
            if (popupContainer) {
                var rect = popupContainer.getBoundingClientRect();
                var mouseX = e.clientX;
                var mouseY = e.clientY;
        
                isMouseOverPopup = (
                    mouseX >= rect.left &&
                    mouseX <= rect.right &&
                    mouseY >= rect.top &&
                    mouseY <= rect.bottom
                );
                if (isMouseOverPopup && timeoutId) {
                    clearTimeout(timeoutId);
                    timeoutId = null;
        }        }});


        
        // Close Popup if Mouse left the line and the popup for more than 2 seconds

        function ClosePopup(that) {
            setTimeout(function() {
                if (!isMouseOverPopup && !isMouseOverLine) {
                    that.closePopup();
                } else {
                    setTimeout(function() {
                        ClosePopup(that);
                    }, 1000); // 1000 ms = 1s
                }
            }, 2000); // 2000 ms = 2s
        }


        
        poly_line_93cbbab344506e75c794d22d2b511264.on('mouseout', function (e) {
            ClosePopup(this)});

        // End new behaviour *************

        
    
    
            var marker_8b903b52f3692cd82ba2abe287c2316c = L.marker(
                [42.72814389473684, 2.9347599722991697],
                {
  "draggable": false,
  "autoPan": true,
  "maxZoom": 20,
  "id": "\u00c9cole Jean MoulinH\u00f4tel de ville",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_ffd49440ed6b91406e5b6c141d79548a = L.divIcon({
  "html": "\n    \u003cdiv style=\"font-size: 12px;\n                color: #71be20;\n                font-weight: bold;\n                width: 70px;\n                position: absolute;\n                top: 00px;\n                left: 00px;\n                text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n          \u003cspan style=\"font-size: 13px; position: relative; top: -2px;right:-8px;\"\u003e\u003c/span\u003e\n                \u003cspan style=\"font-size: 16px;\"\u003e\ud83d\udeb2\u003c/span\u003e 2\u0027\n    \u003c/div\u003e\n    ",
  "className": "empty",
});
            marker_8b903b52f3692cd82ba2abe287c2316c.setIcon(div_icon_ffd49440ed6b91406e5b6c141d79548a);
        
    
                marker_8b903b52f3692cd82ba2abe287c2316c.setIcon(div_icon_ffd49440ed6b91406e5b6c141d79548a);
            
    
            var poly_line_9e834b81be0a96c978fd7036c6f4877e = L.polyline(
                [[42.729897, 2.934723], [42.73001769972299, 2.934665779501385], [42.73013572520776, 2.9346055074792243], [42.73025107645429, 2.9345421839335177], [42.730363753462605, 2.9344758088642657], [42.7304737562327, 2.9344063822714683], [42.73058108476455, 2.9343339041551246], [42.730685739058174, 2.9342583745152346], [42.73078771911357, 2.9341797933518006], [42.73088702493075, 2.9340981606648198], [42.7309836565097, 2.934013476454293], [42.73107761385042, 2.9339257407202215], [42.73116889695291, 2.933834953462604], [42.731257505817176, 2.9337411146814403], [42.73134344044321, 2.933644224376731], [42.73142670083102, 2.9335442825484765], [42.73150728698061, 2.9334412891966757], [42.73158519889196, 2.93333524432133], [42.73166043656509, 2.9332261479224377], [42.731733, 2.933114]],
                {"bubblingMouseEvents": true, "color": "#71be20", "dashArray": "20,10", "dashOffset": null, "fill": false, "fillColor": "#71be20", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 1.0, "smoothFactor": 1.0, "stroke": true, "weight": 7}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
        var popup_f78ef598f7aee42595aa5c6b3b6ad332 = L.popup({"max_width": 1200});
        
            
                var html_8de017d43f31cddebcb2eaf26151602f = $(`<div id="html_8de017d43f31cddebcb2eaf26151602f" style="width: 100.0%; height: 100.0%;">             <div style="             font-size: 14px;             font-family: 'Arial', sans-serif;             text-align: center;         ">             <div style="font-weight: bold; font-size: 16px; margin-bottom: 10px;">                   <span style="font-size: 13px; position: relative; top: -2px;right:-8px;"></span>                 <span style="font-size: 16px;">🚲</span>  Itinéraire à Vélo musculaire             </div>             <br>                              Hôtel de ville ➡️ Commerces & bibliothèque : <b><span style="color: #71be20;">2 min</span></b><br>                 Hôtel de ville ⬅️ Commerces & bibliothèque : <b><span style="color: #71be20;">2 min</span></b><br>                  (Moyenne : <b><span style="color: #71be20;">2 min</span></b>)<br>                           <div style="text-align: center; margin-top: 15px;">                 <a href='https://geovelo.app/fr/route/?from=2.934723%2C42.729897&to=2.933114%2C42.731733' target='_blank' style="                     display: inline-block;                     padding: 10px 20px;                     background-color: #71be20;                     color: white;                     text-decoration: none;                     border-radius: 25px;                     font-weight: bold;                     box-shadow: 0px 3px 6px rgba(0,0,0,0.2);                     transition: all 0.3s ease;                 ">Aller à l'itinéraire Géovélo</a>             </div>         </div>      </div>`)[0];
                popup_f78ef598f7aee42595aa5c6b3b6ad332.setContent(html_8de017d43f31cddebcb2eaf26151602f);
            
        
        poly_line_9e834b81be0a96c978fd7036c6f4877e.bindPopup(popup_f78ef598f7aee42595aa5c6b3b6ad332);
        ;

        // New behaviour *************
        

        var isMouseOverLine = false;
        var isMouseOverPopup = false;
        var timeoutId = null;

        
        // Open Popup over Line
        poly_line_9e834b81be0a96c978fd7036c6f4877e.on('mouseover', function (e) {
            isMouseOverLine=true;
            this.openPopup();
            if (timeoutId) {
                clearTimeout(timeoutId);
                timeoutId = null;
        }});


        // Check if Mouse is still Over Line
        poly_line_9e834b81be0a96c978fd7036c6f4877e.on('mouseout', function (e) {
            isMouseOverLine=false;});
        
        // Check if Mouse is still over Popup (much more complex)
        document.addEventListener('mousemove', function(e) {
            var popupContainer = document.querySelector('.leaflet-popup');
            if (popupContainer) {
                var rect = popupContainer.getBoundingClientRect();
                var mouseX = e.clientX;
                var mouseY = e.clientY;
        
                isMouseOverPopup = (
                    mouseX >= rect.left &&
                    mouseX <= rect.right &&
                    mouseY >= rect.top &&
                    mouseY <= rect.bottom
                );
                if (isMouseOverPopup && timeoutId) {
                    clearTimeout(timeoutId);
                    timeoutId = null;
        }        }});


        
        // Close Popup if Mouse left the line and the popup for more than 2 seconds

        function ClosePopup(that) {
            setTimeout(function() {
                if (!isMouseOverPopup && !isMouseOverLine) {
                    that.closePopup();
                } else {
                    setTimeout(function() {
                        ClosePopup(that);
                    }, 1000); // 1000 ms = 1s
                }
            }, 2000); // 2000 ms = 2s
        }


        
        poly_line_9e834b81be0a96c978fd7036c6f4877e.on('mouseout', function (e) {
            ClosePopup(this)});

        // End new behaviour *************

        
    
    
            var marker_e53e781de227ca64efe1e8823d9cb81d = L.marker(
                [42.7309836565097, 2.934013476454293],
                {
  "draggable": false,
  "autoPan": true,
  "maxZoom": 20,
  "id": "H\u00f4tel de villeCommerces \u0026 biblioth\u00e8que",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_782486eff03025311dd7b609a8652ece = L.divIcon({
  "html": "\n    \u003cdiv style=\"font-size: 12px;\n                color: #71be20;\n                font-weight: bold;\n                width: 70px;\n                position: absolute;\n                top: 00px;\n                left: 00px;\n                text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n          \u003cspan style=\"font-size: 13px; position: relative; top: -2px;right:-8px;\"\u003e\u003c/span\u003e\n                \u003cspan style=\"font-size: 16px;\"\u003e\ud83d\udeb2\u003c/span\u003e 2\u0027\n    \u003c/div\u003e\n    ",
  "className": "empty",
});
            marker_e53e781de227ca64efe1e8823d9cb81d.setIcon(div_icon_782486eff03025311dd7b609a8652ece);
        
    
                marker_e53e781de227ca64efe1e8823d9cb81d.setIcon(div_icon_782486eff03025311dd7b609a8652ece);
            
    
            var poly_line_294ef84ea86de55f162b80ea4e31fc47 = L.polyline(
                [[42.731733, 2.933114], [42.73226498725762, 2.9328669590027707], [42.73278533850415, 2.932606425484765], [42.733294053739606, 2.932332399445983], [42.73379113296399, 2.9320448808864272], [42.7342765761773, 2.931743869806095], [42.734750383379506, 2.931429366204987], [42.73521255457064, 2.931101370083103], [42.735663089750695, 2.9307598814404434], [42.73610198891968, 2.930404900277009], [42.73652925207756, 2.9300364265927983], [42.73694487922438, 2.929654460387812], [42.737348870360115, 2.92925900166205], [42.73774122548477, 2.9288500504155133], [42.73812194459834, 2.9284276066482], [42.73849102770083, 2.927991670360111], [42.73884847479225, 2.9275422415512464], [42.73919428587257, 2.927079320221607], [42.739528460941834, 2.9266029063711914], [42.739851, 2.926113]],
                {"bubblingMouseEvents": true, "color": "#71be20", "dashArray": "20,10", "dashOffset": null, "fill": false, "fillColor": "#71be20", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 1.0, "smoothFactor": 1.0, "stroke": true, "weight": 7}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
        var popup_a1bf0817b1a7142eac0af740f9b43117 = L.popup({"max_width": 1200});
        
            
                var html_466dd2e21d88613a88415f10e673769b = $(`<div id="html_466dd2e21d88613a88415f10e673769b" style="width: 100.0%; height: 100.0%;">             <div style="             font-size: 14px;             font-family: 'Arial', sans-serif;             text-align: center;         ">             <div style="font-weight: bold; font-size: 16px; margin-bottom: 10px;">                   <span style="font-size: 13px; position: relative; top: -2px;right:-8px;"></span>                 <span style="font-size: 16px;">🚲</span>  Itinéraire à Vélo musculaire             </div>             <br>                              Commerces & bibliothèque ➡️ Collège Jean Rous : <b><span style="color: #71be20;">6 min</span></b><br>                 Commerces & bibliothèque ⬅️ Collège Jean Rous : <b><span style="color: #71be20;">6 min</span></b><br>                  (Moyenne : <b><span style="color: #71be20;">6 min</span></b>)<br>                           <div style="text-align: center; margin-top: 15px;">                 <a href='https://geovelo.app/fr/route/?from=2.933114%2C42.731733&to=2.926113%2C42.739851' target='_blank' style="                     display: inline-block;                     padding: 10px 20px;                     background-color: #71be20;                     color: white;                     text-decoration: none;                     border-radius: 25px;                     font-weight: bold;                     box-shadow: 0px 3px 6px rgba(0,0,0,0.2);                     transition: all 0.3s ease;                 ">Aller à l'itinéraire Géovélo</a>             </div>         </div>      </div>`)[0];
                popup_a1bf0817b1a7142eac0af740f9b43117.setContent(html_466dd2e21d88613a88415f10e673769b);
            
        
        poly_line_294ef84ea86de55f162b80ea4e31fc47.bindPopup(popup_a1bf0817b1a7142eac0af740f9b43117);
        ;

        // New behaviour *************
        

        var isMouseOverLine = false;
        var isMouseOverPopup = false;
        var timeoutId = null;

        
        // Open Popup over Line
        poly_line_294ef84ea86de55f162b80ea4e31fc47.on('mouseover', function (e) {
            isMouseOverLine=true;
            this.openPopup();
            if (timeoutId) {
                clearTimeout(timeoutId);
                timeoutId = null;
        }});


        // Check if Mouse is still Over Line
        poly_line_294ef84ea86de55f162b80ea4e31fc47.on('mouseout', function (e) {
            isMouseOverLine=false;});
        
        // Check if Mouse is still over Popup (much more complex)
        document.addEventListener('mousemove', function(e) {
            var popupContainer = document.querySelector('.leaflet-popup');
            if (popupContainer) {
                var rect = popupContainer.getBoundingClientRect();
                var mouseX = e.clientX;
                var mouseY = e.clientY;
        
                isMouseOverPopup = (
                    mouseX >= rect.left &&
                    mouseX <= rect.right &&
                    mouseY >= rect.top &&
                    mouseY <= rect.bottom
                );
                if (isMouseOverPopup && timeoutId) {
                    clearTimeout(timeoutId);
                    timeoutId = null;
        }        }});


        
        // Close Popup if Mouse left the line and the popup for more than 2 seconds

        function ClosePopup(that) {
            setTimeout(function() {
                if (!isMouseOverPopup && !isMouseOverLine) {
                    that.closePopup();
                } else {
                    setTimeout(function() {
                        ClosePopup(that);
                    }, 1000); // 1000 ms = 1s
                }
            }, 2000); // 2000 ms = 2s
        }


        
        poly_line_294ef84ea86de55f162b80ea4e31fc47.on('mouseout', function (e) {
            ClosePopup(this)});

        // End new behaviour *************

        
    
    
            var marker_f1aae847454d35e910e9f41644095628 = L.marker(
                [42.73652925207756, 2.9300364265927983],
                {
  "draggable": false,
  "autoPan": true,
  "maxZoom": 20,
  "id": "Commerces \u0026 biblioth\u00e8queColl\u00e8ge Jean Rous",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_2b6ca5acf2623a9523823b8e39e03b12 = L.divIcon({
  "html": "\n    \u003cdiv style=\"font-size: 12px;\n                color: #71be20;\n                font-weight: bold;\n                width: 70px;\n                position: absolute;\n                top: 00px;\n                left: 00px;\n                text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n          \u003cspan style=\"font-size: 13px; position: relative; top: -2px;right:-8px;\"\u003e\u003c/span\u003e\n                \u003cspan style=\"font-size: 16px;\"\u003e\ud83d\udeb2\u003c/span\u003e 6\u0027\n    \u003c/div\u003e\n    ",
  "className": "empty",
});
            marker_f1aae847454d35e910e9f41644095628.setIcon(div_icon_2b6ca5acf2623a9523823b8e39e03b12);
        
    
                marker_f1aae847454d35e910e9f41644095628.setIcon(div_icon_2b6ca5acf2623a9523823b8e39e03b12);
            
    
            var poly_line_927994eecb09b863f96ea78fb55c44a8 = L.polyline(
                [[42.729476, 2.941713], [42.72960271745153, 2.941351402770083], [42.72971781717452, 2.9409891058171747], [42.72982129916897, 2.940626109141274], [42.7299131634349, 2.9402624127423826], [42.72999340997231, 2.9398980166204995], [42.73006203878116, 2.9395329207756236], [42.7301190498615, 2.939167125207756], [42.7301644432133, 2.938800629916898], [42.73019821883656, 2.9384334349030476], [42.7302203767313, 2.938065540166205], [42.73023091689751, 2.9376969457063713], [42.73022983933518, 2.937327651523546], [42.730217144044325, 2.9369576576177288], [42.73019283102493, 2.9365869639889195], [42.73015690027701, 2.9362155706371196], [42.73010935180055, 2.9358434775623268], [42.730050185595566, 2.935470684764543], [42.72997940166205, 2.9350971922437674], [42.729897, 2.934723]],
                {"bubblingMouseEvents": true, "color": "#71be20", "dashArray": "20,10", "dashOffset": null, "fill": false, "fillColor": "#71be20", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 1.0, "smoothFactor": 1.0, "stroke": true, "weight": 7}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
        var popup_f4487bfe6279f1829f27409e89afa707 = L.popup({"max_width": 1200});
        
            
                var html_cc9ea84c8326b66d7651216d8f63211b = $(`<div id="html_cc9ea84c8326b66d7651216d8f63211b" style="width: 100.0%; height: 100.0%;">             <div style="             font-size: 14px;             font-family: 'Arial', sans-serif;             text-align: center;         ">             <div style="font-weight: bold; font-size: 16px; margin-bottom: 10px;">                   <span style="font-size: 13px; position: relative; top: -2px;right:-8px;"></span>                 <span style="font-size: 16px;">🚲</span>  Itinéraire à Vélo musculaire             </div>             <br>                              Maison de Santé ➡️ Hôtel de ville : <b><span style="color: #71be20;">3 min</span></b><br>                 Maison de Santé ⬅️ Hôtel de ville : <b><span style="color: #71be20;">3 min</span></b><br>                  (Moyenne : <b><span style="color: #71be20;">3 min</span></b>)<br>                           <div style="text-align: center; margin-top: 15px;">                 <a href='https://geovelo.app/fr/route/?from=2.941713%2C42.729476&to=2.934723%2C42.729897' target='_blank' style="                     display: inline-block;                     padding: 10px 20px;                     background-color: #71be20;                     color: white;                     text-decoration: none;                     border-radius: 25px;                     font-weight: bold;                     box-shadow: 0px 3px 6px rgba(0,0,0,0.2);                     transition: all 0.3s ease;                 ">Aller à l'itinéraire Géovélo</a>             </div>         </div>      </div>`)[0];
                popup_f4487bfe6279f1829f27409e89afa707.setContent(html_cc9ea84c8326b66d7651216d8f63211b);
            
        
        poly_line_927994eecb09b863f96ea78fb55c44a8.bindPopup(popup_f4487bfe6279f1829f27409e89afa707);
        ;

        // New behaviour *************
        

        var isMouseOverLine = false;
        var isMouseOverPopup = false;
        var timeoutId = null;

        
        // Open Popup over Line
        poly_line_927994eecb09b863f96ea78fb55c44a8.on('mouseover', function (e) {
            isMouseOverLine=true;
            this.openPopup();
            if (timeoutId) {
                clearTimeout(timeoutId);
                timeoutId = null;
        }});


        // Check if Mouse is still Over Line
        poly_line_927994eecb09b863f96ea78fb55c44a8.on('mouseout', function (e) {
            isMouseOverLine=false;});
        
        // Check if Mouse is still over Popup (much more complex)
        document.addEventListener('mousemove', function(e) {
            var popupContainer = document.querySelector('.leaflet-popup');
            if (popupContainer) {
                var rect = popupContainer.getBoundingClientRect();
                var mouseX = e.clientX;
                var mouseY = e.clientY;
        
                isMouseOverPopup = (
                    mouseX >= rect.left &&
                    mouseX <= rect.right &&
                    mouseY >= rect.top &&
                    mouseY <= rect.bottom
                );
                if (isMouseOverPopup && timeoutId) {
                    clearTimeout(timeoutId);
                    timeoutId = null;
        }        }});


        
        // Close Popup if Mouse left the line and the popup for more than 2 seconds

        function ClosePopup(that) {
            setTimeout(function() {
                if (!isMouseOverPopup && !isMouseOverLine) {
                    that.closePopup();
                } else {
                    setTimeout(function() {
                        ClosePopup(that);
                    }, 1000); // 1000 ms = 1s
                }
            }, 2000); // 2000 ms = 2s
        }


        
        poly_line_927994eecb09b863f96ea78fb55c44a8.on('mouseout', function (e) {
            ClosePopup(this)});

        // End new behaviour *************

        
    
    
            var marker_2487e359c0e963ded6579a64a5695aea = L.marker(
                [42.7302203767313, 2.938065540166205],
                {
  "draggable": false,
  "autoPan": true,
  "maxZoom": 20,
  "id": "Maison de Sant\u00e9H\u00f4tel de ville",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_096b671068cd8394f915cd23c023593a = L.divIcon({
  "html": "\n    \u003cdiv style=\"font-size: 12px;\n                color: #71be20;\n                font-weight: bold;\n                width: 70px;\n                position: absolute;\n                top: 00px;\n                left: 00px;\n                text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n          \u003cspan style=\"font-size: 13px; position: relative; top: -2px;right:-8px;\"\u003e\u003c/span\u003e\n                \u003cspan style=\"font-size: 16px;\"\u003e\ud83d\udeb2\u003c/span\u003e 3\u0027\n    \u003c/div\u003e\n    ",
  "className": "empty",
});
            marker_2487e359c0e963ded6579a64a5695aea.setIcon(div_icon_096b671068cd8394f915cd23c023593a);
        
    
                marker_2487e359c0e963ded6579a64a5695aea.setIcon(div_icon_096b671068cd8394f915cd23c023593a);
            
    
            var poly_line_9653fa9e033cd2e61ba71dc2a41ed39f = L.polyline(
                [[42.729897, 2.934723], [42.73000200055402, 2.9344722387811637], [42.73009880221607, 2.934220491966759], [42.73018740498615, 2.933967759556787], [42.73026780886427, 2.933714041551247], [42.73034001385042, 2.933459337950139], [42.7304040199446, 2.9332036487534627], [42.73045982714682, 2.9329469739612186], [42.73050743545706, 2.932689313573407], [42.73054684487535, 2.9324306675900287], [42.73057805540166, 2.9321710360110806], [42.73060106703601, 2.9319104188365652], [42.7306158797784, 2.9316488160664824], [42.730622493628815, 2.9313862277008313], [42.73062090858726, 2.9311226537396124], [42.73061112465374, 2.9308580941828257], [42.73059314182825, 2.930592549030471], [42.73056696011081, 2.930326018282549], [42.730532579501386, 2.930058501939058], [42.73049, 2.92979]],
                {"bubblingMouseEvents": true, "color": "#71be20", "dashArray": "20,10", "dashOffset": null, "fill": false, "fillColor": "#71be20", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 1.0, "smoothFactor": 1.0, "stroke": true, "weight": 7}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
        var popup_50ff405a9fd992b13c8fc90db5a114ef = L.popup({"max_width": 1200});
        
            
                var html_d3a38900d2ea771c6ef8377444562029 = $(`<div id="html_d3a38900d2ea771c6ef8377444562029" style="width: 100.0%; height: 100.0%;">             <div style="             font-size: 14px;             font-family: 'Arial', sans-serif;             text-align: center;         ">             <div style="font-weight: bold; font-size: 16px; margin-bottom: 10px;">                   <span style="font-size: 13px; position: relative; top: -2px;right:-8px;"></span>                 <span style="font-size: 16px;">🚲</span>  Itinéraire à Vélo musculaire             </div>             <br>                              Hôtel de ville ➡️ Parc des Sports et Loisirs : <b><span style="color: #71be20;">4 min</span></b><br>                 Hôtel de ville ⬅️ Parc des Sports et Loisirs : <b><span style="color: #71be20;">3 min</span></b><br>                  (Moyenne : <b><span style="color: #71be20;">3 min</span></b>)<br>                           <div style="text-align: center; margin-top: 15px;">                 <a href='https://geovelo.app/fr/route/?from=2.934723%2C42.729897&to=2.92979%2C42.73049' target='_blank' style="                     display: inline-block;                     padding: 10px 20px;                     background-color: #71be20;                     color: white;                     text-decoration: none;                     border-radius: 25px;                     font-weight: bold;                     box-shadow: 0px 3px 6px rgba(0,0,0,0.2);                     transition: all 0.3s ease;                 ">Aller à l'itinéraire Géovélo</a>             </div>         </div>      </div>`)[0];
                popup_50ff405a9fd992b13c8fc90db5a114ef.setContent(html_d3a38900d2ea771c6ef8377444562029);
            
        
        poly_line_9653fa9e033cd2e61ba71dc2a41ed39f.bindPopup(popup_50ff405a9fd992b13c8fc90db5a114ef);
        ;

        // New behaviour *************
        

        var isMouseOverLine = false;
        var isMouseOverPopup = false;
        var timeoutId = null;

        
        // Open Popup over Line
        poly_line_9653fa9e033cd2e61ba71dc2a41ed39f.on('mouseover', function (e) {
            isMouseOverLine=true;
            this.openPopup();
            if (timeoutId) {
                clearTimeout(timeoutId);
                timeoutId = null;
        }});


        // Check if Mouse is still Over Line
        poly_line_9653fa9e033cd2e61ba71dc2a41ed39f.on('mouseout', function (e) {
            isMouseOverLine=false;});
        
        // Check if Mouse is still over Popup (much more complex)
        document.addEventListener('mousemove', function(e) {
            var popupContainer = document.querySelector('.leaflet-popup');
            if (popupContainer) {
                var rect = popupContainer.getBoundingClientRect();
                var mouseX = e.clientX;
                var mouseY = e.clientY;
        
                isMouseOverPopup = (
                    mouseX >= rect.left &&
                    mouseX <= rect.right &&
                    mouseY >= rect.top &&
                    mouseY <= rect.bottom
                );
                if (isMouseOverPopup && timeoutId) {
                    clearTimeout(timeoutId);
                    timeoutId = null;
        }        }});


        
        // Close Popup if Mouse left the line and the popup for more than 2 seconds

        function ClosePopup(that) {
            setTimeout(function() {
                if (!isMouseOverPopup && !isMouseOverLine) {
                    that.closePopup();
                } else {
                    setTimeout(function() {
                        ClosePopup(that);
                    }, 1000); // 1000 ms = 1s
                }
            }, 2000); // 2000 ms = 2s
        }


        
        poly_line_9653fa9e033cd2e61ba71dc2a41ed39f.on('mouseout', function (e) {
            ClosePopup(this)});

        // End new behaviour *************

        
    
    
            var marker_b688af1c3d83f98ba837b41b3c076eef = L.marker(
                [42.73057805540166, 2.9321710360110806],
                {
  "draggable": false,
  "autoPan": true,
  "maxZoom": 20,
  "id": "H\u00f4tel de villeParc des Sports et Loisirs",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_d09bb87855193503057e23bd7d8eaf42 = L.divIcon({
  "html": "\n    \u003cdiv style=\"font-size: 12px;\n                color: #71be20;\n                font-weight: bold;\n                width: 70px;\n                position: absolute;\n                top: 00px;\n                left: 00px;\n                text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n          \u003cspan style=\"font-size: 13px; position: relative; top: -2px;right:-8px;\"\u003e\u003c/span\u003e\n                \u003cspan style=\"font-size: 16px;\"\u003e\ud83d\udeb2\u003c/span\u003e 3\u0027\n    \u003c/div\u003e\n    ",
  "className": "empty",
});
            marker_b688af1c3d83f98ba837b41b3c076eef.setIcon(div_icon_d09bb87855193503057e23bd7d8eaf42);
        
    
                marker_b688af1c3d83f98ba837b41b3c076eef.setIcon(div_icon_d09bb87855193503057e23bd7d8eaf42);
            
    
            var poly_line_f215581c0c7f398eae53f4b1713c5110 = L.polyline(
                [[42.73049, 2.92979], [42.73055448587259, 2.929541489750693], [42.73061117506926, 2.92929315900277], [42.730660067590016, 2.9290450077562324], [42.7307011634349, 2.9287970360110807], [42.73073446260388, 2.928549243767313], [42.73075996509696, 2.9283016310249304], [42.73077767091412, 2.928054197783933], [42.7307875800554, 2.9278069440443213], [42.73078969252078, 2.9275598698060943], [42.73078400831025, 2.9273129750692517], [42.73077052742382, 2.927066259833795], [42.73074924986149, 2.9268197240997225], [42.73072017562327, 2.926573367867036], [42.73068330470914, 2.9263271911357336], [42.730638637119114, 2.926081193905817], [42.73058617285318, 2.925835376177285], [42.73052591191136, 2.9255897379501383], [42.730457854293626, 2.9253442792243765], [42.730382, 2.925099]],
                {"bubblingMouseEvents": true, "color": "#71be20", "dashArray": "20,10", "dashOffset": null, "fill": false, "fillColor": "#71be20", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 1.0, "smoothFactor": 1.0, "stroke": true, "weight": 7}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
        var popup_a41e612b19c9a184a1a4cc07ccb1bb2d = L.popup({"max_width": 1200});
        
            
                var html_c48a8971ada0d54bb110b981af1568ae = $(`<div id="html_c48a8971ada0d54bb110b981af1568ae" style="width: 100.0%; height: 100.0%;">             <div style="             font-size: 14px;             font-family: 'Arial', sans-serif;             text-align: center;         ">             <div style="font-weight: bold; font-size: 16px; margin-bottom: 10px;">                   <span style="font-size: 13px; position: relative; top: -2px;right:-8px;"></span>                 <span style="font-size: 16px;">🚲</span>  Itinéraire à Vélo musculaire             </div>             <br>                              Parc des Sports et Loisirs ➡️ Utile & Pain du jour : <b><span style="color: #71be20;">2 min</span></b><br>                 Parc des Sports et Loisirs ⬅️ Utile & Pain du jour : <b><span style="color: #71be20;">2 min</span></b><br>                  (Moyenne : <b><span style="color: #71be20;">2 min</span></b>)<br>                           <div style="text-align: center; margin-top: 15px;">                 <a href='https://geovelo.app/fr/route/?from=2.92979%2C42.73049&to=2.925099%2C42.730382' target='_blank' style="                     display: inline-block;                     padding: 10px 20px;                     background-color: #71be20;                     color: white;                     text-decoration: none;                     border-radius: 25px;                     font-weight: bold;                     box-shadow: 0px 3px 6px rgba(0,0,0,0.2);                     transition: all 0.3s ease;                 ">Aller à l'itinéraire Géovélo</a>             </div>         </div>      </div>`)[0];
                popup_a41e612b19c9a184a1a4cc07ccb1bb2d.setContent(html_c48a8971ada0d54bb110b981af1568ae);
            
        
        poly_line_f215581c0c7f398eae53f4b1713c5110.bindPopup(popup_a41e612b19c9a184a1a4cc07ccb1bb2d);
        ;

        // New behaviour *************
        

        var isMouseOverLine = false;
        var isMouseOverPopup = false;
        var timeoutId = null;

        
        // Open Popup over Line
        poly_line_f215581c0c7f398eae53f4b1713c5110.on('mouseover', function (e) {
            isMouseOverLine=true;
            this.openPopup();
            if (timeoutId) {
                clearTimeout(timeoutId);
                timeoutId = null;
        }});


        // Check if Mouse is still Over Line
        poly_line_f215581c0c7f398eae53f4b1713c5110.on('mouseout', function (e) {
            isMouseOverLine=false;});
        
        // Check if Mouse is still over Popup (much more complex)
        document.addEventListener('mousemove', function(e) {
            var popupContainer = document.querySelector('.leaflet-popup');
            if (popupContainer) {
                var rect = popupContainer.getBoundingClientRect();
                var mouseX = e.clientX;
                var mouseY = e.clientY;
        
                isMouseOverPopup = (
                    mouseX >= rect.left &&
                    mouseX <= rect.right &&
                    mouseY >= rect.top &&
                    mouseY <= rect.bottom
                );
                if (isMouseOverPopup && timeoutId) {
                    clearTimeout(timeoutId);
                    timeoutId = null;
        }        }});


        
        // Close Popup if Mouse left the line and the popup for more than 2 seconds

        function ClosePopup(that) {
            setTimeout(function() {
                if (!isMouseOverPopup && !isMouseOverLine) {
                    that.closePopup();
                } else {
                    setTimeout(function() {
                        ClosePopup(that);
                    }, 1000); // 1000 ms = 1s
                }
            }, 2000); // 2000 ms = 2s
        }


        
        poly_line_f215581c0c7f398eae53f4b1713c5110.on('mouseout', function (e) {
            ClosePopup(this)});

        // End new behaviour *************

        
    
    
            var marker_627654890b7c4d12c7a4136c54bcd07c = L.marker(
                [42.73078400831025, 2.9273129750692517],
                {
  "draggable": false,
  "autoPan": true,
  "maxZoom": 20,
  "id": "Parc des Sports et LoisirsUtile \u0026 Pain du jour",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_0f7cad875695a2086abecac9cea5485a = L.divIcon({
  "html": "\n    \u003cdiv style=\"font-size: 12px;\n                color: #71be20;\n                font-weight: bold;\n                width: 70px;\n                position: absolute;\n                top: 00px;\n                left: 00px;\n                text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n          \u003cspan style=\"font-size: 13px; position: relative; top: -2px;right:-8px;\"\u003e\u003c/span\u003e\n                \u003cspan style=\"font-size: 16px;\"\u003e\ud83d\udeb2\u003c/span\u003e 2\u0027\n    \u003c/div\u003e\n    ",
  "className": "empty",
});
            marker_627654890b7c4d12c7a4136c54bcd07c.setIcon(div_icon_0f7cad875695a2086abecac9cea5485a);
        
    
                marker_627654890b7c4d12c7a4136c54bcd07c.setIcon(div_icon_0f7cad875695a2086abecac9cea5485a);
            
    
            var poly_line_d3e7ebe326f4912a771aa80dd10c14bc = L.polyline(
                [[42.729897, 2.934723], [42.73010694626039, 2.935106105263158], [42.73032634293629, 2.9354798947368423], [42.730555190027694, 2.9358443684210522], [42.730793487534626, 2.936199526315789], [42.73104123545706, 2.9365453684210525], [42.73129843379501, 2.9368818947368416], [42.73156508254847, 2.9372091052631566], [42.73184118171745, 2.9375269999999993], [42.732126731301946, 2.9378355789473685], [42.73242173130193, 2.9381348421052627], [42.73272618171745, 2.9384247894736837], [42.73304008254847, 2.9387054210526307], [42.733363433795006, 2.938976736842105], [42.73369623545706, 2.9392387368421047], [42.73403848753462, 2.9394914210526313], [42.734390190027696, 2.9397347894736843], [42.73475134293629, 2.9399688421052628], [42.735121946260385, 2.940193578947368], [42.735502, 2.940409]],
                {"bubblingMouseEvents": true, "color": "#71be20", "dashArray": "20,10", "dashOffset": null, "fill": false, "fillColor": "#71be20", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 1.0, "smoothFactor": 1.0, "stroke": true, "weight": 7}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
        var popup_697a3de685956294ec8dd6d65c9f195d = L.popup({"max_width": 1200});
        
            
                var html_e0b1cad535caccb7c58d758777c2d734 = $(`<div id="html_e0b1cad535caccb7c58d758777c2d734" style="width: 100.0%; height: 100.0%;">             <div style="             font-size: 14px;             font-family: 'Arial', sans-serif;             text-align: center;         ">             <div style="font-weight: bold; font-size: 16px; margin-bottom: 10px;">                   <span style="font-size: 13px; position: relative; top: -2px;right:-8px;"></span>                 <span style="font-size: 16px;">🚲</span>  Itinéraire à Vélo musculaire             </div>             <br>                              Hôtel de ville ➡️ La Grange : <b><span style="color: #71be20;">5 min</span></b><br>                 Hôtel de ville ⬅️ La Grange : <b><span style="color: #71be20;">5 min</span></b><br>                  (Moyenne : <b><span style="color: #71be20;">5 min</span></b>)<br>                           <div style="text-align: center; margin-top: 15px;">                 <a href='https://geovelo.app/fr/route/?from=2.934723%2C42.729897&to=2.940409%2C42.735502' target='_blank' style="                     display: inline-block;                     padding: 10px 20px;                     background-color: #71be20;                     color: white;                     text-decoration: none;                     border-radius: 25px;                     font-weight: bold;                     box-shadow: 0px 3px 6px rgba(0,0,0,0.2);                     transition: all 0.3s ease;                 ">Aller à l'itinéraire Géovélo</a>             </div>         </div>      </div>`)[0];
                popup_697a3de685956294ec8dd6d65c9f195d.setContent(html_e0b1cad535caccb7c58d758777c2d734);
            
        
        poly_line_d3e7ebe326f4912a771aa80dd10c14bc.bindPopup(popup_697a3de685956294ec8dd6d65c9f195d);
        ;

        // New behaviour *************
        

        var isMouseOverLine = false;
        var isMouseOverPopup = false;
        var timeoutId = null;

        
        // Open Popup over Line
        poly_line_d3e7ebe326f4912a771aa80dd10c14bc.on('mouseover', function (e) {
            isMouseOverLine=true;
            this.openPopup();
            if (timeoutId) {
                clearTimeout(timeoutId);
                timeoutId = null;
        }});


        // Check if Mouse is still Over Line
        poly_line_d3e7ebe326f4912a771aa80dd10c14bc.on('mouseout', function (e) {
            isMouseOverLine=false;});
        
        // Check if Mouse is still over Popup (much more complex)
        document.addEventListener('mousemove', function(e) {
            var popupContainer = document.querySelector('.leaflet-popup');
            if (popupContainer) {
                var rect = popupContainer.getBoundingClientRect();
                var mouseX = e.clientX;
                var mouseY = e.clientY;
        
                isMouseOverPopup = (
                    mouseX >= rect.left &&
                    mouseX <= rect.right &&
                    mouseY >= rect.top &&
                    mouseY <= rect.bottom
                );
                if (isMouseOverPopup && timeoutId) {
                    clearTimeout(timeoutId);
                    timeoutId = null;
        }        }});


        
        // Close Popup if Mouse left the line and the popup for more than 2 seconds

        function ClosePopup(that) {
            setTimeout(function() {
                if (!isMouseOverPopup && !isMouseOverLine) {
                    that.closePopup();
                } else {
                    setTimeout(function() {
                        ClosePopup(that);
                    }, 1000); // 1000 ms = 1s
                }
            }, 2000); // 2000 ms = 2s
        }


        
        poly_line_d3e7ebe326f4912a771aa80dd10c14bc.on('mouseout', function (e) {
            ClosePopup(this)});

        // End new behaviour *************

        
    
    
            var marker_9349cea5dd9bafe8e6e6944d5c7b4e69 = L.marker(
                [42.73242173130193, 2.9381348421052627],
                {
  "draggable": false,
  "autoPan": true,
  "maxZoom": 20,
  "id": "H\u00f4tel de villeLa Grange",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_9d9ccde7b099c62ae5896df4eaea47a4 = L.divIcon({
  "html": "\n    \u003cdiv style=\"font-size: 12px;\n                color: #71be20;\n                font-weight: bold;\n                width: 70px;\n                position: absolute;\n                top: 00px;\n                left: 00px;\n                text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n          \u003cspan style=\"font-size: 13px; position: relative; top: -2px;right:-8px;\"\u003e\u003c/span\u003e\n                \u003cspan style=\"font-size: 16px;\"\u003e\ud83d\udeb2\u003c/span\u003e 5\u0027\n    \u003c/div\u003e\n    ",
  "className": "empty",
});
            marker_9349cea5dd9bafe8e6e6944d5c7b4e69.setIcon(div_icon_9d9ccde7b099c62ae5896df4eaea47a4);
        
    
                marker_9349cea5dd9bafe8e6e6944d5c7b4e69.setIcon(div_icon_9d9ccde7b099c62ae5896df4eaea47a4);
            
    
            var poly_line_46f1455439d1ea6b3ff01f722a658f76 = L.polyline(
                [[42.726274, 2.934229], [42.72596037839336, 2.9344334382271473], [42.72565533462603, 2.9346453423822716], [42.72535886869805, 2.9348647124653735], [42.725070980609416, 2.9350915484764544], [42.72479167036012, 2.935325850415513], [42.72452093795013, 2.9355676182825485], [42.7242587833795, 2.935816852077562], [42.7240052066482, 2.936073551800554], [42.723760207756236, 2.936337717451524], [42.723523786703595, 2.936609349030471], [42.7232959434903, 2.936888446537396], [42.72307667811634, 2.937175009972299], [42.72286599058172, 2.93746903933518], [42.72266388088643, 2.937770534626039], [42.72247034903047, 2.9380794958448755], [42.72228539501385, 2.93839592299169], [42.72210901883656, 2.938719816066482], [42.72194122049861, 2.9390511750692516], [42.721782, 2.93939]],
                {"bubblingMouseEvents": true, "color": "#71be20", "dashArray": "20,10", "dashOffset": null, "fill": false, "fillColor": "#71be20", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 1.0, "smoothFactor": 1.0, "stroke": true, "weight": 7}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
        var popup_9281916649d5b5ec149a62286fc5d280 = L.popup({"max_width": 1200});
        
            
                var html_923731c0cff0cdb0d7b78ab94f651fa9 = $(`<div id="html_923731c0cff0cdb0d7b78ab94f651fa9" style="width: 100.0%; height: 100.0%;">             <div style="             font-size: 14px;             font-family: 'Arial', sans-serif;             text-align: center;         ">             <div style="font-weight: bold; font-size: 16px; margin-bottom: 10px;">                   <span style="font-size: 13px; position: relative; top: -2px;right:-8px;"></span>                 <span style="font-size: 16px;">🚲</span>  Itinéraire à Vélo musculaire             </div>             <br>                              École Jean Moulin ➡️ Las Palades : <b><span style="color: #71be20;">6 min</span></b><br>                 École Jean Moulin ⬅️ Las Palades : <b><span style="color: #71be20;">4 min</span></b><br>                  (Moyenne : <b><span style="color: #71be20;">5 min</span></b>)<br>                           <div style="text-align: center; margin-top: 15px;">                 <a href='https://geovelo.app/fr/route/?from=2.934229%2C42.726274&to=2.93939%2C42.721782' target='_blank' style="                     display: inline-block;                     padding: 10px 20px;                     background-color: #71be20;                     color: white;                     text-decoration: none;                     border-radius: 25px;                     font-weight: bold;                     box-shadow: 0px 3px 6px rgba(0,0,0,0.2);                     transition: all 0.3s ease;                 ">Aller à l'itinéraire Géovélo</a>             </div>         </div>      </div>`)[0];
                popup_9281916649d5b5ec149a62286fc5d280.setContent(html_923731c0cff0cdb0d7b78ab94f651fa9);
            
        
        poly_line_46f1455439d1ea6b3ff01f722a658f76.bindPopup(popup_9281916649d5b5ec149a62286fc5d280);
        ;

        // New behaviour *************
        

        var isMouseOverLine = false;
        var isMouseOverPopup = false;
        var timeoutId = null;

        
        // Open Popup over Line
        poly_line_46f1455439d1ea6b3ff01f722a658f76.on('mouseover', function (e) {
            isMouseOverLine=true;
            this.openPopup();
            if (timeoutId) {
                clearTimeout(timeoutId);
                timeoutId = null;
        }});


        // Check if Mouse is still Over Line
        poly_line_46f1455439d1ea6b3ff01f722a658f76.on('mouseout', function (e) {
            isMouseOverLine=false;});
        
        // Check if Mouse is still over Popup (much more complex)
        document.addEventListener('mousemove', function(e) {
            var popupContainer = document.querySelector('.leaflet-popup');
            if (popupContainer) {
                var rect = popupContainer.getBoundingClientRect();
                var mouseX = e.clientX;
                var mouseY = e.clientY;
        
                isMouseOverPopup = (
                    mouseX >= rect.left &&
                    mouseX <= rect.right &&
                    mouseY >= rect.top &&
                    mouseY <= rect.bottom
                );
                if (isMouseOverPopup && timeoutId) {
                    clearTimeout(timeoutId);
                    timeoutId = null;
        }        }});


        
        // Close Popup if Mouse left the line and the popup for more than 2 seconds

        function ClosePopup(that) {
            setTimeout(function() {
                if (!isMouseOverPopup && !isMouseOverLine) {
                    that.closePopup();
                } else {
                    setTimeout(function() {
                        ClosePopup(that);
                    }, 1000); // 1000 ms = 1s
                }
            }, 2000); // 2000 ms = 2s
        }


        
        poly_line_46f1455439d1ea6b3ff01f722a658f76.on('mouseout', function (e) {
            ClosePopup(this)});

        // End new behaviour *************

        
    
    
            var marker_86a6304fec4e0cd1d767a802c3d60545 = L.marker(
                [42.723523786703595, 2.936609349030471],
                {
  "draggable": false,
  "autoPan": true,
  "maxZoom": 20,
  "id": "\u00c9cole Jean MoulinLas Palades",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_7e38c3a3efefabeca102e5b52a8b0585 = L.divIcon({
  "html": "\n    \u003cdiv style=\"font-size: 12px;\n                color: #71be20;\n                font-weight: bold;\n                width: 70px;\n                position: absolute;\n                top: 00px;\n                left: 00px;\n                text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n          \u003cspan style=\"font-size: 13px; position: relative; top: -2px;right:-8px;\"\u003e\u003c/span\u003e\n                \u003cspan style=\"font-size: 16px;\"\u003e\ud83d\udeb2\u003c/span\u003e 5\u0027\n    \u003c/div\u003e\n    ",
  "className": "empty",
});
            marker_86a6304fec4e0cd1d767a802c3d60545.setIcon(div_icon_7e38c3a3efefabeca102e5b52a8b0585);
        
    
                marker_86a6304fec4e0cd1d767a802c3d60545.setIcon(div_icon_7e38c3a3efefabeca102e5b52a8b0585);
            
    
            var poly_line_ecadab78c338516e2b1a6e9861cff9de = L.polyline(
                [[42.726981, 2.942576], [42.727251942382274, 2.9422063030470915], [42.727509832686984, 2.9418317595567864], [42.72775467091412, 2.9414523695290855], [42.727986457063714, 2.941068132963989], [42.72820519113575, 2.940679049861496], [42.728410873130194, 2.9402851202216063], [42.7286035030471, 2.9398863440443206], [42.72878308088643, 2.93948272132964], [42.7289496066482, 2.9390742520775626], [42.72910308033241, 2.938660936288089], [42.72924350193906, 2.9382427739612185], [42.72937087146815, 2.937819765096953], [42.72948518891967, 2.9373919096952905], [42.72958645429363, 2.9369592077562325], [42.72967466759003, 2.9365216592797783], [42.72974982880886, 2.936079264265928], [42.72981193795014, 2.9356320227146813], [42.72986099501385, 2.9351799346260385], [42.729897, 2.934723]],
                {"bubblingMouseEvents": true, "color": "#71be20", "dashArray": "20,10", "dashOffset": null, "fill": false, "fillColor": "#71be20", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 1.0, "smoothFactor": 1.0, "stroke": true, "weight": 7}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
        var popup_8058ff8bc5430ebe76983db290e12db8 = L.popup({"max_width": 1200});
        
            
                var html_7d939abf143161b4620d5ade898e8fce = $(`<div id="html_7d939abf143161b4620d5ade898e8fce" style="width: 100.0%; height: 100.0%;">             <div style="             font-size: 14px;             font-family: 'Arial', sans-serif;             text-align: center;         ">             <div style="font-weight: bold; font-size: 16px; margin-bottom: 10px;">                   <span style="font-size: 13px; position: relative; top: -2px;right:-8px;"></span>                 <span style="font-size: 16px;">🚲</span>  Itinéraire à Vélo musculaire             </div>             <br>                              Les Jardins de la Palmeraie ➡️ Hôtel de ville : <b><span style="color: #71be20;">5 min</span></b><br>                 Les Jardins de la Palmeraie ⬅️ Hôtel de ville : <b><span style="color: #71be20;">5 min</span></b><br>                  (Moyenne : <b><span style="color: #71be20;">5 min</span></b>)<br>                           <div style="text-align: center; margin-top: 15px;">                 <a href='https://geovelo.app/fr/route/?from=2.942576%2C42.726981&to=2.934723%2C42.729897' target='_blank' style="                     display: inline-block;                     padding: 10px 20px;                     background-color: #71be20;                     color: white;                     text-decoration: none;                     border-radius: 25px;                     font-weight: bold;                     box-shadow: 0px 3px 6px rgba(0,0,0,0.2);                     transition: all 0.3s ease;                 ">Aller à l'itinéraire Géovélo</a>             </div>         </div>      </div>`)[0];
                popup_8058ff8bc5430ebe76983db290e12db8.setContent(html_7d939abf143161b4620d5ade898e8fce);
            
        
        poly_line_ecadab78c338516e2b1a6e9861cff9de.bindPopup(popup_8058ff8bc5430ebe76983db290e12db8);
        ;

        // New behaviour *************
        

        var isMouseOverLine = false;
        var isMouseOverPopup = false;
        var timeoutId = null;

        
        // Open Popup over Line
        poly_line_ecadab78c338516e2b1a6e9861cff9de.on('mouseover', function (e) {
            isMouseOverLine=true;
            this.openPopup();
            if (timeoutId) {
                clearTimeout(timeoutId);
                timeoutId = null;
        }});


        // Check if Mouse is still Over Line
        poly_line_ecadab78c338516e2b1a6e9861cff9de.on('mouseout', function (e) {
            isMouseOverLine=false;});
        
        // Check if Mouse is still over Popup (much more complex)
        document.addEventListener('mousemove', function(e) {
            var popupContainer = document.querySelector('.leaflet-popup');
            if (popupContainer) {
                var rect = popupContainer.getBoundingClientRect();
                var mouseX = e.clientX;
                var mouseY = e.clientY;
        
                isMouseOverPopup = (
                    mouseX >= rect.left &&
                    mouseX <= rect.right &&
                    mouseY >= rect.top &&
                    mouseY <= rect.bottom
                );
                if (isMouseOverPopup && timeoutId) {
                    clearTimeout(timeoutId);
                    timeoutId = null;
        }        }});


        
        // Close Popup if Mouse left the line and the popup for more than 2 seconds

        function ClosePopup(that) {
            setTimeout(function() {
                if (!isMouseOverPopup && !isMouseOverLine) {
                    that.closePopup();
                } else {
                    setTimeout(function() {
                        ClosePopup(that);
                    }, 1000); // 1000 ms = 1s
                }
            }, 2000); // 2000 ms = 2s
        }


        
        poly_line_ecadab78c338516e2b1a6e9861cff9de.on('mouseout', function (e) {
            ClosePopup(this)});

        // End new behaviour *************

        
    
    
            var marker_5cbccfe0305d84b8f7f651b4593178f3 = L.marker(
                [42.72910308033241, 2.938660936288089],
                {
  "draggable": false,
  "autoPan": true,
  "maxZoom": 20,
  "id": "Les Jardins de la PalmeraieH\u00f4tel de ville",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_2c492ea4aa278214eb343f1d163109bb = L.divIcon({
  "html": "\n    \u003cdiv style=\"font-size: 12px;\n                color: #71be20;\n                font-weight: bold;\n                width: 70px;\n                position: absolute;\n                top: 00px;\n                left: 00px;\n                text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n          \u003cspan style=\"font-size: 13px; position: relative; top: -2px;right:-8px;\"\u003e\u003c/span\u003e\n                \u003cspan style=\"font-size: 16px;\"\u003e\ud83d\udeb2\u003c/span\u003e 5\u0027\n    \u003c/div\u003e\n    ",
  "className": "empty",
});
            marker_5cbccfe0305d84b8f7f651b4593178f3.setIcon(div_icon_2c492ea4aa278214eb343f1d163109bb);
        
    
                marker_5cbccfe0305d84b8f7f651b4593178f3.setIcon(div_icon_2c492ea4aa278214eb343f1d163109bb);
            
    
            var poly_line_8eb85b7f442312bd664293d5dffd830d = L.polyline(
                [[42.726981, 2.942576], [42.72712522493075, 2.9425679002770084], [42.72726801551247, 2.942555653739612], [42.727409371745146, 2.942539260387811], [42.72754929362881, 2.9425187202216065], [42.72768778116344, 2.942494033240997], [42.72782483434903, 2.942465199445983], [42.727960453185595, 2.942432218836564], [42.72809463767313, 2.9423950914127417], [42.72822738781164, 2.9423538171745154], [42.72835870360111, 2.942308396121883], [42.72848858504155, 2.942258828254847], [42.728617032132966, 2.942205113573407], [42.72874404487535, 2.942147252077562], [42.72886962326869, 2.9420852437673126], [42.728993767313014, 2.942019088642659], [42.729116477008304, 2.941948786703601], [42.72923775235457, 2.9418743379501384], [42.72935759335179, 2.941795742382271], [42.729476, 2.941713]],
                {"bubblingMouseEvents": true, "color": "#71be20", "dashArray": "20,10", "dashOffset": null, "fill": false, "fillColor": "#71be20", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 1.0, "smoothFactor": 1.0, "stroke": true, "weight": 7}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
        var popup_c225d25fd0805671bfa83b238fc605d4 = L.popup({"max_width": 1200});
        
            
                var html_9310846c91ba8fa48b9133d4d4358865 = $(`<div id="html_9310846c91ba8fa48b9133d4d4358865" style="width: 100.0%; height: 100.0%;">             <div style="             font-size: 14px;             font-family: 'Arial', sans-serif;             text-align: center;         ">             <div style="font-weight: bold; font-size: 16px; margin-bottom: 10px;">                   <span style="font-size: 13px; position: relative; top: -2px;right:-8px;"></span>                 <span style="font-size: 16px;">🚲</span>  Itinéraire à Vélo musculaire             </div>             <br>                              Les Jardins de la Palmeraie ➡️ Maison de Santé : <b><span style="color: #71be20;">2 min</span></b><br>                 Les Jardins de la Palmeraie ⬅️ Maison de Santé : <b><span style="color: #71be20;">2 min</span></b><br>                  (Moyenne : <b><span style="color: #71be20;">2 min</span></b>)<br>                           <div style="text-align: center; margin-top: 15px;">                 <a href='https://geovelo.app/fr/route/?from=2.942576%2C42.726981&to=2.941713%2C42.729476' target='_blank' style="                     display: inline-block;                     padding: 10px 20px;                     background-color: #71be20;                     color: white;                     text-decoration: none;                     border-radius: 25px;                     font-weight: bold;                     box-shadow: 0px 3px 6px rgba(0,0,0,0.2);                     transition: all 0.3s ease;                 ">Aller à l'itinéraire Géovélo</a>             </div>         </div>      </div>`)[0];
                popup_c225d25fd0805671bfa83b238fc605d4.setContent(html_9310846c91ba8fa48b9133d4d4358865);
            
        
        poly_line_8eb85b7f442312bd664293d5dffd830d.bindPopup(popup_c225d25fd0805671bfa83b238fc605d4);
        ;

        // New behaviour *************
        

        var isMouseOverLine = false;
        var isMouseOverPopup = false;
        var timeoutId = null;

        
        // Open Popup over Line
        poly_line_8eb85b7f442312bd664293d5dffd830d.on('mouseover', function (e) {
            isMouseOverLine=true;
            this.openPopup();
            if (timeoutId) {
                clearTimeout(timeoutId);
                timeoutId = null;
        }});


        // Check if Mouse is still Over Line
        poly_line_8eb85b7f442312bd664293d5dffd830d.on('mouseout', function (e) {
            isMouseOverLine=false;});
        
        // Check if Mouse is still over Popup (much more complex)
        document.addEventListener('mousemove', function(e) {
            var popupContainer = document.querySelector('.leaflet-popup');
            if (popupContainer) {
                var rect = popupContainer.getBoundingClientRect();
                var mouseX = e.clientX;
                var mouseY = e.clientY;
        
                isMouseOverPopup = (
                    mouseX >= rect.left &&
                    mouseX <= rect.right &&
                    mouseY >= rect.top &&
                    mouseY <= rect.bottom
                );
                if (isMouseOverPopup && timeoutId) {
                    clearTimeout(timeoutId);
                    timeoutId = null;
        }        }});


        
        // Close Popup if Mouse left the line and the popup for more than 2 seconds

        function ClosePopup(that) {
            setTimeout(function() {
                if (!isMouseOverPopup && !isMouseOverLine) {
                    that.closePopup();
                } else {
                    setTimeout(function() {
                        ClosePopup(that);
                    }, 1000); // 1000 ms = 1s
                }
            }, 2000); // 2000 ms = 2s
        }


        
        poly_line_8eb85b7f442312bd664293d5dffd830d.on('mouseout', function (e) {
            ClosePopup(this)});

        // End new behaviour *************

        
    
    
            var marker_3f03e43aa55fd8a56f2ae38829a092f6 = L.marker(
                [42.72835870360111, 2.942308396121883],
                {
  "draggable": false,
  "autoPan": true,
  "maxZoom": 20,
  "id": "Les Jardins de la PalmeraieMaison de Sant\u00e9",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_a0dd9d14313ec12d0e743f817c50ebf3 = L.divIcon({
  "html": "\n    \u003cdiv style=\"font-size: 12px;\n                color: #71be20;\n                font-weight: bold;\n                width: 70px;\n                position: absolute;\n                top: 00px;\n                left: 00px;\n                text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n          \u003cspan style=\"font-size: 13px; position: relative; top: -2px;right:-8px;\"\u003e\u003c/span\u003e\n                \u003cspan style=\"font-size: 16px;\"\u003e\ud83d\udeb2\u003c/span\u003e 2\u0027\n    \u003c/div\u003e\n    ",
  "className": "empty",
});
            marker_3f03e43aa55fd8a56f2ae38829a092f6.setIcon(div_icon_a0dd9d14313ec12d0e743f817c50ebf3);
        
    
                marker_3f03e43aa55fd8a56f2ae38829a092f6.setIcon(div_icon_a0dd9d14313ec12d0e743f817c50ebf3);
            
    
            var poly_line_dfe90d3d4dc3884c17158db39238bdfc = L.polyline(
                [[42.726981, 2.942576], [42.72706864764543, 2.942126108587258], [42.72714242216067, 2.9416773922437667], [42.7272023235457, 2.941229850969528], [42.72724835180056, 2.9407834847645424], [42.72728050692522, 2.940338293628809], [42.72729878891967, 2.9398942775623262], [42.727303197783925, 2.939451436565096], [42.727293733518, 2.939009770637119], [42.72727039612188, 2.9385692797783936], [42.727233185595566, 2.9381299639889193], [42.72718210193906, 2.9376918232686977], [42.72711714515235, 2.937254857617728], [42.727038315235454, 2.9368190670360113], [42.72694561218836, 2.936384451523545], [42.726839036011086, 2.9359510110803324], [42.7267185867036, 2.935518745706371], [42.726584264265924, 2.935087655401662], [42.72643606869805, 2.934657740166205], [42.726274, 2.934229]],
                {"bubblingMouseEvents": true, "color": "#71be20", "dashArray": "20,10", "dashOffset": null, "fill": false, "fillColor": "#71be20", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 1.0, "smoothFactor": 1.0, "stroke": true, "weight": 7}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
        var popup_99563754f9016762e65979a52751d0c2 = L.popup({"max_width": 1200});
        
            
                var html_3d96297b98de0b33f5ef66c8c59c4a87 = $(`<div id="html_3d96297b98de0b33f5ef66c8c59c4a87" style="width: 100.0%; height: 100.0%;">             <div style="             font-size: 14px;             font-family: 'Arial', sans-serif;             text-align: center;         ">             <div style="font-weight: bold; font-size: 16px; margin-bottom: 10px;">                   <span style="font-size: 13px; position: relative; top: -2px;right:-8px;"></span>                 <span style="font-size: 16px;">🚲</span>  Itinéraire à Vélo musculaire             </div>             <br>                              Les Jardins de la Palmeraie ➡️ École Jean Moulin : <b><span style="color: #71be20;">6 min</span></b><br>                 Les Jardins de la Palmeraie ⬅️ École Jean Moulin : <b><span style="color: #71be20;">6 min</span></b><br>                  (Moyenne : <b><span style="color: #71be20;">6 min</span></b>)<br>                           <div style="text-align: center; margin-top: 15px;">                 <a href='https://geovelo.app/fr/route/?from=2.942576%2C42.726981&to=2.934229%2C42.726274' target='_blank' style="                     display: inline-block;                     padding: 10px 20px;                     background-color: #71be20;                     color: white;                     text-decoration: none;                     border-radius: 25px;                     font-weight: bold;                     box-shadow: 0px 3px 6px rgba(0,0,0,0.2);                     transition: all 0.3s ease;                 ">Aller à l'itinéraire Géovélo</a>             </div>         </div>      </div>`)[0];
                popup_99563754f9016762e65979a52751d0c2.setContent(html_3d96297b98de0b33f5ef66c8c59c4a87);
            
        
        poly_line_dfe90d3d4dc3884c17158db39238bdfc.bindPopup(popup_99563754f9016762e65979a52751d0c2);
        ;

        // New behaviour *************
        

        var isMouseOverLine = false;
        var isMouseOverPopup = false;
        var timeoutId = null;

        
        // Open Popup over Line
        poly_line_dfe90d3d4dc3884c17158db39238bdfc.on('mouseover', function (e) {
            isMouseOverLine=true;
            this.openPopup();
            if (timeoutId) {
                clearTimeout(timeoutId);
                timeoutId = null;
        }});


        // Check if Mouse is still Over Line
        poly_line_dfe90d3d4dc3884c17158db39238bdfc.on('mouseout', function (e) {
            isMouseOverLine=false;});
        
        // Check if Mouse is still over Popup (much more complex)
        document.addEventListener('mousemove', function(e) {
            var popupContainer = document.querySelector('.leaflet-popup');
            if (popupContainer) {
                var rect = popupContainer.getBoundingClientRect();
                var mouseX = e.clientX;
                var mouseY = e.clientY;
        
                isMouseOverPopup = (
                    mouseX >= rect.left &&
                    mouseX <= rect.right &&
                    mouseY >= rect.top &&
                    mouseY <= rect.bottom
                );
                if (isMouseOverPopup && timeoutId) {
                    clearTimeout(timeoutId);
                    timeoutId = null;
        }        }});


        
        // Close Popup if Mouse left the line and the popup for more than 2 seconds

        function ClosePopup(that) {
            setTimeout(function() {
                if (!isMouseOverPopup && !isMouseOverLine) {
                    that.closePopup();
                } else {
                    setTimeout(function() {
                        ClosePopup(that);
                    }, 1000); // 1000 ms = 1s
                }
            }, 2000); // 2000 ms = 2s
        }


        
        poly_line_dfe90d3d4dc3884c17158db39238bdfc.on('mouseout', function (e) {
            ClosePopup(this)});

        // End new behaviour *************

        
    
    
            var marker_f6bbf083bbbb580d34d9e37683657552 = L.marker(
                [42.727233185595566, 2.9381299639889193],
                {
  "draggable": false,
  "autoPan": true,
  "maxZoom": 20,
  "id": "Les Jardins de la Palmeraie\u00c9cole Jean Moulin",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_828974782423995c8302592bfdbd8c99 = L.divIcon({
  "html": "\n    \u003cdiv style=\"font-size: 12px;\n                color: #71be20;\n                font-weight: bold;\n                width: 70px;\n                position: absolute;\n                top: 00px;\n                left: 00px;\n                text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n          \u003cspan style=\"font-size: 13px; position: relative; top: -2px;right:-8px;\"\u003e\u003c/span\u003e\n                \u003cspan style=\"font-size: 16px;\"\u003e\ud83d\udeb2\u003c/span\u003e 6\u0027\n    \u003c/div\u003e\n    ",
  "className": "empty",
});
            marker_f6bbf083bbbb580d34d9e37683657552.setIcon(div_icon_828974782423995c8302592bfdbd8c99);
        
    
                marker_f6bbf083bbbb580d34d9e37683657552.setIcon(div_icon_828974782423995c8302592bfdbd8c99);
            
    
            var poly_line_1d9fbfa97a001b3f98a089572acd8a59 = L.polyline(
                [[42.726981, 2.942576], [42.72694264542937, 2.941991434903047], [42.72688752908587, 2.941412844875346], [42.72681565096953, 2.9408402299168968], [42.726727011080335, 2.940273590027701], [42.726621609418295, 2.9397129252077563], [42.72649944598338, 2.939158235457063], [42.72636052077562, 2.938609520775622], [42.72620483379501, 2.9380667811634344], [42.72603238504156, 2.9375300166204985], [42.725843174515234, 2.936999227146814], [42.72563720221606, 2.936474412742382], [42.725414468144045, 2.935955573407202], [42.72517497229917, 2.935442709141274], [42.724918714681436, 2.934935819944598], [42.72464569529086, 2.9344349058171746], [42.72435591412742, 2.9339399667590027], [42.724049371191136, 2.933451002770083], [42.723726066481994, 2.9329680138504157], [42.723386, 2.932491]],
                {"bubblingMouseEvents": true, "color": "#71be20", "dashArray": "20,10", "dashOffset": null, "fill": false, "fillColor": "#71be20", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 1.0, "smoothFactor": 1.0, "stroke": true, "weight": 7}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
        var popup_86a468145c02feed63bd00060ec5c5ae = L.popup({"max_width": 1200});
        
            
                var html_3db496f2a41e0f1bb7988f8e12f5cb85 = $(`<div id="html_3db496f2a41e0f1bb7988f8e12f5cb85" style="width: 100.0%; height: 100.0%;">             <div style="             font-size: 14px;             font-family: 'Arial', sans-serif;             text-align: center;         ">             <div style="font-weight: bold; font-size: 16px; margin-bottom: 10px;">                   <span style="font-size: 13px; position: relative; top: -2px;right:-8px;"></span>                 <span style="font-size: 16px;">🚲</span>  Itinéraire à Vélo musculaire             </div>             <br>                              Les Jardins de la Palmeraie ➡️ Le fournil de l'épi d'or : <b><span style="color: #71be20;">7 min</span></b><br>                 Les Jardins de la Palmeraie ⬅️ Le fournil de l'épi d'or : <b><span style="color: #71be20;">7 min</span></b><br>                  (Moyenne : <b><span style="color: #71be20;">7 min</span></b>)<br>                           <div style="text-align: center; margin-top: 15px;">                 <a href='https://geovelo.app/fr/route/?from=2.942576%2C42.726981&to=2.932491%2C42.723386' target='_blank' style="                     display: inline-block;                     padding: 10px 20px;                     background-color: #71be20;                     color: white;                     text-decoration: none;                     border-radius: 25px;                     font-weight: bold;                     box-shadow: 0px 3px 6px rgba(0,0,0,0.2);                     transition: all 0.3s ease;                 ">Aller à l'itinéraire Géovélo</a>             </div>         </div>      </div>`)[0];
                popup_86a468145c02feed63bd00060ec5c5ae.setContent(html_3db496f2a41e0f1bb7988f8e12f5cb85);
            
        
        poly_line_1d9fbfa97a001b3f98a089572acd8a59.bindPopup(popup_86a468145c02feed63bd00060ec5c5ae);
        ;

        // New behaviour *************
        

        var isMouseOverLine = false;
        var isMouseOverPopup = false;
        var timeoutId = null;

        
        // Open Popup over Line
        poly_line_1d9fbfa97a001b3f98a089572acd8a59.on('mouseover', function (e) {
            isMouseOverLine=true;
            this.openPopup();
            if (timeoutId) {
                clearTimeout(timeoutId);
                timeoutId = null;
        }});


        // Check if Mouse is still Over Line
        poly_line_1d9fbfa97a001b3f98a089572acd8a59.on('mouseout', function (e) {
            isMouseOverLine=false;});
        
        // Check if Mouse is still over Popup (much more complex)
        document.addEventListener('mousemove', function(e) {
            var popupContainer = document.querySelector('.leaflet-popup');
            if (popupContainer) {
                var rect = popupContainer.getBoundingClientRect();
                var mouseX = e.clientX;
                var mouseY = e.clientY;
        
                isMouseOverPopup = (
                    mouseX >= rect.left &&
                    mouseX <= rect.right &&
                    mouseY >= rect.top &&
                    mouseY <= rect.bottom
                );
                if (isMouseOverPopup && timeoutId) {
                    clearTimeout(timeoutId);
                    timeoutId = null;
        }        }});


        
        // Close Popup if Mouse left the line and the popup for more than 2 seconds

        function ClosePopup(that) {
            setTimeout(function() {
                if (!isMouseOverPopup && !isMouseOverLine) {
                    that.closePopup();
                } else {
                    setTimeout(function() {
                        ClosePopup(that);
                    }, 1000); // 1000 ms = 1s
                }
            }, 2000); // 2000 ms = 2s
        }


        
        poly_line_1d9fbfa97a001b3f98a089572acd8a59.on('mouseout', function (e) {
            ClosePopup(this)});

        // End new behaviour *************

        
    
    
            var marker_80df3fc08b7b4bac6bcd6663f696b737 = L.marker(
                [42.725843174515234, 2.936999227146814],
                {
  "draggable": false,
  "autoPan": true,
  "maxZoom": 20,
  "id": "Les Jardins de la PalmeraieLe fournil de l\u0027\u00e9pi d\u0027or",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_6257ca9984e8b04298ec0ed772cd84d1 = L.divIcon({
  "html": "\n    \u003cdiv style=\"font-size: 12px;\n                color: #71be20;\n                font-weight: bold;\n                width: 70px;\n                position: absolute;\n                top: 00px;\n                left: 00px;\n                text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n          \u003cspan style=\"font-size: 13px; position: relative; top: -2px;right:-8px;\"\u003e\u003c/span\u003e\n                \u003cspan style=\"font-size: 16px;\"\u003e\ud83d\udeb2\u003c/span\u003e 7\u0027\n    \u003c/div\u003e\n    ",
  "className": "empty",
});
            marker_80df3fc08b7b4bac6bcd6663f696b737.setIcon(div_icon_6257ca9984e8b04298ec0ed772cd84d1);
        
    
                marker_80df3fc08b7b4bac6bcd6663f696b737.setIcon(div_icon_6257ca9984e8b04298ec0ed772cd84d1);
            
    
            var poly_line_47716467750dd9ca68d7f0afe2138167 = L.polyline(
                [[42.730056, 2.922288], [42.7300311096953, 2.9224408238227153], [42.73001089141273, 2.9225931058171746], [42.729995345152346, 2.922744845983379], [42.729984470914125, 2.92289604432133], [42.72997826869806, 2.923046700831025], [42.729976738504156, 2.923196815512465], [42.7299798803324, 2.9233463883656507], [42.729987694182824, 2.9234954193905818], [42.730000180055406, 2.923643908587258], [42.73001733795014, 2.923791855955679], [42.730039167867034, 2.923939261495845], [42.730065669806095, 2.924086125207756], [42.73009684376731, 2.9242324470914127], [42.73013268975069, 2.924378227146814], [42.73017320775624, 2.9245234653739614], [42.73021839778393, 2.924668161772853], [42.73026825983379, 2.9248123163434903], [42.73032279390581, 2.9249559290858724], [42.730382, 2.925099]],
                {"bubblingMouseEvents": true, "color": "#71be20", "dashArray": "20,10", "dashOffset": null, "fill": false, "fillColor": "#71be20", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 1.0, "smoothFactor": 1.0, "stroke": true, "weight": 7}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
        var popup_e2d93216ec87e6818778c353cd2a2423 = L.popup({"max_width": 1200});
        
            
                var html_2a7312f16ab6cd56c9a8d6c5ac495cb4 = $(`<div id="html_2a7312f16ab6cd56c9a8d6c5ac495cb4" style="width: 100.0%; height: 100.0%;">             <div style="             font-size: 14px;             font-family: 'Arial', sans-serif;             text-align: center;         ">             <div style="font-weight: bold; font-size: 16px; margin-bottom: 10px;">                   <span style="font-size: 13px; position: relative; top: -2px;right:-8px;"></span>                 <span style="font-size: 16px;">🚲</span>  Itinéraire à Vélo musculaire             </div>             <br>                              Les Cottages de Perpignan ➡️ Utile & Pain du jour : <b><span style="color: #71be20;">5 min</span></b><br>                 Les Cottages de Perpignan ⬅️ Utile & Pain du jour : <b><span style="color: #71be20;">5 min</span></b><br>                  (Moyenne : <b><span style="color: #71be20;">5 min</span></b>)<br>                           <div style="text-align: center; margin-top: 15px;">                 <a href='https://geovelo.app/fr/route/?from=2.922288%2C42.730056&to=2.925099%2C42.730382' target='_blank' style="                     display: inline-block;                     padding: 10px 20px;                     background-color: #71be20;                     color: white;                     text-decoration: none;                     border-radius: 25px;                     font-weight: bold;                     box-shadow: 0px 3px 6px rgba(0,0,0,0.2);                     transition: all 0.3s ease;                 ">Aller à l'itinéraire Géovélo</a>             </div>         </div>      </div>`)[0];
                popup_e2d93216ec87e6818778c353cd2a2423.setContent(html_2a7312f16ab6cd56c9a8d6c5ac495cb4);
            
        
        poly_line_47716467750dd9ca68d7f0afe2138167.bindPopup(popup_e2d93216ec87e6818778c353cd2a2423);
        ;

        // New behaviour *************
        

        var isMouseOverLine = false;
        var isMouseOverPopup = false;
        var timeoutId = null;

        
        // Open Popup over Line
        poly_line_47716467750dd9ca68d7f0afe2138167.on('mouseover', function (e) {
            isMouseOverLine=true;
            this.openPopup();
            if (timeoutId) {
                clearTimeout(timeoutId);
                timeoutId = null;
        }});


        // Check if Mouse is still Over Line
        poly_line_47716467750dd9ca68d7f0afe2138167.on('mouseout', function (e) {
            isMouseOverLine=false;});
        
        // Check if Mouse is still over Popup (much more complex)
        document.addEventListener('mousemove', function(e) {
            var popupContainer = document.querySelector('.leaflet-popup');
            if (popupContainer) {
                var rect = popupContainer.getBoundingClientRect();
                var mouseX = e.clientX;
                var mouseY = e.clientY;
        
                isMouseOverPopup = (
                    mouseX >= rect.left &&
                    mouseX <= rect.right &&
                    mouseY >= rect.top &&
                    mouseY <= rect.bottom
                );
                if (isMouseOverPopup && timeoutId) {
                    clearTimeout(timeoutId);
                    timeoutId = null;
        }        }});


        
        // Close Popup if Mouse left the line and the popup for more than 2 seconds

        function ClosePopup(that) {
            setTimeout(function() {
                if (!isMouseOverPopup && !isMouseOverLine) {
                    that.closePopup();
                } else {
                    setTimeout(function() {
                        ClosePopup(that);
                    }, 1000); // 1000 ms = 1s
                }
            }, 2000); // 2000 ms = 2s
        }


        
        poly_line_47716467750dd9ca68d7f0afe2138167.on('mouseout', function (e) {
            ClosePopup(this)});

        // End new behaviour *************

        
    
    
            var marker_4dafbeef3df956d7f98c6507834db3da = L.marker(
                [42.73001733795014, 2.923791855955679],
                {
  "draggable": false,
  "autoPan": true,
  "maxZoom": 20,
  "id": "Les Cottages de PerpignanUtile \u0026 Pain du jour",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_ab1ca7a1b545b62f38a19a6ed8eaf385 = L.divIcon({
  "html": "\n    \u003cdiv style=\"font-size: 12px;\n                color: #71be20;\n                font-weight: bold;\n                width: 70px;\n                position: absolute;\n                top: 00px;\n                left: 00px;\n                text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n          \u003cspan style=\"font-size: 13px; position: relative; top: -2px;right:-8px;\"\u003e\u003c/span\u003e\n                \u003cspan style=\"font-size: 16px;\"\u003e\ud83d\udeb2\u003c/span\u003e 5\u0027\n    \u003c/div\u003e\n    ",
  "className": "empty",
});
            marker_4dafbeef3df956d7f98c6507834db3da.setIcon(div_icon_ab1ca7a1b545b62f38a19a6ed8eaf385);
        
    
                marker_4dafbeef3df956d7f98c6507834db3da.setIcon(div_icon_ab1ca7a1b545b62f38a19a6ed8eaf385);
            
    
            var poly_line_8a875a0d62fad8d7aa6a6d96843e7c3b = L.polyline(
                [[42.73049, 2.92979], [42.73050569916899, 2.929983540720222], [42.73052692299169, 2.9301750155124653], [42.73055367146814, 2.930364424376731], [42.73058594459834, 2.9305517673130197], [42.73062374238228, 2.93073704432133], [42.730667064819954, 2.930920255401662], [42.730715911911346, 2.9311014005540157], [42.730770283656504, 2.931280479778393], [42.730830180055406, 2.9314574930747925], [42.73089560110803, 2.931632440443213], [42.73096654681441, 2.9318053218836564], [42.731043017174514, 2.9319761373961217], [42.731125012188365, 2.9321448869806095], [42.73121253185595, 2.932311570637119], [42.731305576177284, 2.932476188365651], [42.731404145152354, 2.9326387401662046], [42.73150823878116, 2.932799226038781], [42.73161785706371, 2.9329576459833793], [42.731733, 2.933114]],
                {"bubblingMouseEvents": true, "color": "#71be20", "dashArray": "20,10", "dashOffset": null, "fill": false, "fillColor": "#71be20", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 1.0, "smoothFactor": 1.0, "stroke": true, "weight": 7}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
        var popup_fe7347feb31cbf4d162dd9237d75c8a3 = L.popup({"max_width": 1200});
        
            
                var html_dbfabbcbb0f8fd2bcbcc8de8ae41d0ed = $(`<div id="html_dbfabbcbb0f8fd2bcbcc8de8ae41d0ed" style="width: 100.0%; height: 100.0%;">             <div style="             font-size: 14px;             font-family: 'Arial', sans-serif;             text-align: center;         ">             <div style="font-weight: bold; font-size: 16px; margin-bottom: 10px;">                   <span style="font-size: 13px; position: relative; top: -2px;right:-8px;"></span>                 <span style="font-size: 16px;">🚲</span>  Itinéraire à Vélo musculaire             </div>             <br>                              Parc des Sports et Loisirs ➡️ Commerces & bibliothèque : <b><span style="color: #71be20;">2 min</span></b><br>                 Parc des Sports et Loisirs ⬅️ Commerces & bibliothèque : <b><span style="color: #71be20;">2 min</span></b><br>                  (Moyenne : <b><span style="color: #71be20;">2 min</span></b>)<br>                           <div style="text-align: center; margin-top: 15px;">                 <a href='https://geovelo.app/fr/route/?from=2.92979%2C42.73049&to=2.933114%2C42.731733' target='_blank' style="                     display: inline-block;                     padding: 10px 20px;                     background-color: #71be20;                     color: white;                     text-decoration: none;                     border-radius: 25px;                     font-weight: bold;                     box-shadow: 0px 3px 6px rgba(0,0,0,0.2);                     transition: all 0.3s ease;                 ">Aller à l'itinéraire Géovélo</a>             </div>         </div>      </div>`)[0];
                popup_fe7347feb31cbf4d162dd9237d75c8a3.setContent(html_dbfabbcbb0f8fd2bcbcc8de8ae41d0ed);
            
        
        poly_line_8a875a0d62fad8d7aa6a6d96843e7c3b.bindPopup(popup_fe7347feb31cbf4d162dd9237d75c8a3);
        ;

        // New behaviour *************
        

        var isMouseOverLine = false;
        var isMouseOverPopup = false;
        var timeoutId = null;

        
        // Open Popup over Line
        poly_line_8a875a0d62fad8d7aa6a6d96843e7c3b.on('mouseover', function (e) {
            isMouseOverLine=true;
            this.openPopup();
            if (timeoutId) {
                clearTimeout(timeoutId);
                timeoutId = null;
        }});


        // Check if Mouse is still Over Line
        poly_line_8a875a0d62fad8d7aa6a6d96843e7c3b.on('mouseout', function (e) {
            isMouseOverLine=false;});
        
        // Check if Mouse is still over Popup (much more complex)
        document.addEventListener('mousemove', function(e) {
            var popupContainer = document.querySelector('.leaflet-popup');
            if (popupContainer) {
                var rect = popupContainer.getBoundingClientRect();
                var mouseX = e.clientX;
                var mouseY = e.clientY;
        
                isMouseOverPopup = (
                    mouseX >= rect.left &&
                    mouseX <= rect.right &&
                    mouseY >= rect.top &&
                    mouseY <= rect.bottom
                );
                if (isMouseOverPopup && timeoutId) {
                    clearTimeout(timeoutId);
                    timeoutId = null;
        }        }});


        
        // Close Popup if Mouse left the line and the popup for more than 2 seconds

        function ClosePopup(that) {
            setTimeout(function() {
                if (!isMouseOverPopup && !isMouseOverLine) {
                    that.closePopup();
                } else {
                    setTimeout(function() {
                        ClosePopup(that);
                    }, 1000); // 1000 ms = 1s
                }
            }, 2000); // 2000 ms = 2s
        }


        
        poly_line_8a875a0d62fad8d7aa6a6d96843e7c3b.on('mouseout', function (e) {
            ClosePopup(this)});

        // End new behaviour *************

        
    
    
            var marker_a107cfd3282a27867b9a6d1fb8b13cef = L.marker(
                [42.73089560110803, 2.931632440443213],
                {
  "draggable": false,
  "autoPan": true,
  "maxZoom": 20,
  "id": "Parc des Sports et LoisirsCommerces \u0026 biblioth\u00e8que",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_ba89c34ad95076cefaa5175cc3a8a232 = L.divIcon({
  "html": "\n    \u003cdiv style=\"font-size: 12px;\n                color: #71be20;\n                font-weight: bold;\n                width: 70px;\n                position: absolute;\n                top: 00px;\n                left: 00px;\n                text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n          \u003cspan style=\"font-size: 13px; position: relative; top: -2px;right:-8px;\"\u003e\u003c/span\u003e\n                \u003cspan style=\"font-size: 16px;\"\u003e\ud83d\udeb2\u003c/span\u003e 2\u0027\n    \u003c/div\u003e\n    ",
  "className": "empty",
});
            marker_a107cfd3282a27867b9a6d1fb8b13cef.setIcon(div_icon_ba89c34ad95076cefaa5175cc3a8a232);
        
    
                marker_a107cfd3282a27867b9a6d1fb8b13cef.setIcon(div_icon_ba89c34ad95076cefaa5175cc3a8a232);
            
    
            var poly_line_1eacebdfa492102abe9a14aae66d483b = L.polyline(
                [[42.726274, 2.934229], [42.72656229529086, 2.934058433240998], [42.726843212742374, 2.9338808592797787], [42.72711675235456, 2.9336962781163436], [42.727382914127425, 2.9335046897506936], [42.72764169806094, 2.933306094182827], [42.727893104155115, 2.933100491412743], [42.72813713240997, 2.9328878814404433], [42.72837378282548, 2.9326682642659287], [42.72860305540166, 2.9324416398891975], [42.7288249501385, 2.93220800831025], [42.729039467036, 2.9319673695290867], [42.72924660609418, 2.931719723545707], [42.72944636731302, 2.9314650703601117], [42.729638750692516, 2.9312034099722997], [42.72982375623269, 2.9309347423822723], [42.73000138393351, 2.930659067590028], [42.73017163379502, 2.9303763855955682], [42.730334505817176, 2.930086696398892], [42.73049, 2.92979]],
                {"bubblingMouseEvents": true, "color": "#71be20", "dashArray": "20,10", "dashOffset": null, "fill": false, "fillColor": "#71be20", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 1.0, "smoothFactor": 1.0, "stroke": true, "weight": 7}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
        var popup_75083c870b29455d6f50faba58796a89 = L.popup({"max_width": 1200});
        
            
                var html_17b85086a1707ed1ae4990ca59a34b42 = $(`<div id="html_17b85086a1707ed1ae4990ca59a34b42" style="width: 100.0%; height: 100.0%;">             <div style="             font-size: 14px;             font-family: 'Arial', sans-serif;             text-align: center;         ">             <div style="font-weight: bold; font-size: 16px; margin-bottom: 10px;">                   <span style="font-size: 13px; position: relative; top: -2px;right:-8px;"></span>                 <span style="font-size: 16px;">🚲</span>  Itinéraire à Vélo musculaire             </div>             <br>                              École Jean Moulin ➡️ Parc des Sports et Loisirs : <b><span style="color: #71be20;">6 min</span></b><br>                 École Jean Moulin ⬅️ Parc des Sports et Loisirs : <b><span style="color: #71be20;">6 min</span></b><br>                  (Moyenne : <b><span style="color: #71be20;">6 min</span></b>)<br>                           <div style="text-align: center; margin-top: 15px;">                 <a href='https://geovelo.app/fr/route/?from=2.934229%2C42.726274&to=2.92979%2C42.73049' target='_blank' style="                     display: inline-block;                     padding: 10px 20px;                     background-color: #71be20;                     color: white;                     text-decoration: none;                     border-radius: 25px;                     font-weight: bold;                     box-shadow: 0px 3px 6px rgba(0,0,0,0.2);                     transition: all 0.3s ease;                 ">Aller à l'itinéraire Géovélo</a>             </div>         </div>      </div>`)[0];
                popup_75083c870b29455d6f50faba58796a89.setContent(html_17b85086a1707ed1ae4990ca59a34b42);
            
        
        poly_line_1eacebdfa492102abe9a14aae66d483b.bindPopup(popup_75083c870b29455d6f50faba58796a89);
        ;

        // New behaviour *************
        

        var isMouseOverLine = false;
        var isMouseOverPopup = false;
        var timeoutId = null;

        
        // Open Popup over Line
        poly_line_1eacebdfa492102abe9a14aae66d483b.on('mouseover', function (e) {
            isMouseOverLine=true;
            this.openPopup();
            if (timeoutId) {
                clearTimeout(timeoutId);
                timeoutId = null;
        }});


        // Check if Mouse is still Over Line
        poly_line_1eacebdfa492102abe9a14aae66d483b.on('mouseout', function (e) {
            isMouseOverLine=false;});
        
        // Check if Mouse is still over Popup (much more complex)
        document.addEventListener('mousemove', function(e) {
            var popupContainer = document.querySelector('.leaflet-popup');
            if (popupContainer) {
                var rect = popupContainer.getBoundingClientRect();
                var mouseX = e.clientX;
                var mouseY = e.clientY;
        
                isMouseOverPopup = (
                    mouseX >= rect.left &&
                    mouseX <= rect.right &&
                    mouseY >= rect.top &&
                    mouseY <= rect.bottom
                );
                if (isMouseOverPopup && timeoutId) {
                    clearTimeout(timeoutId);
                    timeoutId = null;
        }        }});


        
        // Close Popup if Mouse left the line and the popup for more than 2 seconds

        function ClosePopup(that) {
            setTimeout(function() {
                if (!isMouseOverPopup && !isMouseOverLine) {
                    that.closePopup();
                } else {
                    setTimeout(function() {
                        ClosePopup(that);
                    }, 1000); // 1000 ms = 1s
                }
            }, 2000); // 2000 ms = 2s
        }


        
        poly_line_1eacebdfa492102abe9a14aae66d483b.on('mouseout', function (e) {
            ClosePopup(this)});

        // End new behaviour *************

        
    
    
            var marker_f1dfd1298b5281e2c49d24d29c54ea25 = L.marker(
                [42.7288249501385, 2.93220800831025],
                {
  "draggable": false,
  "autoPan": true,
  "maxZoom": 20,
  "id": "\u00c9cole Jean MoulinParc des Sports et Loisirs",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_3545e5484420a78ba10c48dc409620a4 = L.divIcon({
  "html": "\n    \u003cdiv style=\"font-size: 12px;\n                color: #71be20;\n                font-weight: bold;\n                width: 70px;\n                position: absolute;\n                top: 00px;\n                left: 00px;\n                text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n          \u003cspan style=\"font-size: 13px; position: relative; top: -2px;right:-8px;\"\u003e\u003c/span\u003e\n                \u003cspan style=\"font-size: 16px;\"\u003e\ud83d\udeb2\u003c/span\u003e 6\u0027\n    \u003c/div\u003e\n    ",
  "className": "empty",
});
            marker_f1dfd1298b5281e2c49d24d29c54ea25.setIcon(div_icon_3545e5484420a78ba10c48dc409620a4);
        
    
                marker_f1dfd1298b5281e2c49d24d29c54ea25.setIcon(div_icon_3545e5484420a78ba10c48dc409620a4);
            
    
            var poly_line_4bb75360f9085ce2e22f62c8bc178bed = L.polyline(
                [[42.731733, 2.933114], [42.7318222465374, 2.9335543257617736], [42.731923617728526, 2.933988387257618], [42.7320371135734, 2.9344161844875343], [42.73216273407201, 2.9348377174515234], [42.732300479224385, 2.935252986149585], [42.732450349030465, 2.935661990581717], [42.732612343490295, 2.9360647307479217], [42.73278646260387, 2.9364612066481994], [42.73297270637119, 2.936851418282549], [42.73317107479224, 2.9372353656509693], [42.73338156786703, 2.9376130487534624], [42.73360418559557, 2.9379844675900273], [42.733838927977835, 2.938349622160665], [42.73408579501385, 2.938708512465374], [42.7343447867036, 2.939061138504155], [42.734615903047086, 2.9394075002770084], [42.73489914404432, 2.939747597783933], [42.73519450969528, 2.9400814310249306], [42.735502, 2.940409]],
                {"bubblingMouseEvents": true, "color": "#71be20", "dashArray": "20,10", "dashOffset": null, "fill": false, "fillColor": "#71be20", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 1.0, "smoothFactor": 1.0, "stroke": true, "weight": 7}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
        var popup_f996bc77114ef42106957eba7c7c9d4a = L.popup({"max_width": 1200});
        
            
                var html_70d934d0a8c7c46943b336e574b0194d = $(`<div id="html_70d934d0a8c7c46943b336e574b0194d" style="width: 100.0%; height: 100.0%;">             <div style="             font-size: 14px;             font-family: 'Arial', sans-serif;             text-align: center;         ">             <div style="font-weight: bold; font-size: 16px; margin-bottom: 10px;">                   <span style="font-size: 13px; position: relative; top: -2px;right:-8px;"></span>                 <span style="font-size: 16px;">🚲</span>  Itinéraire à Vélo musculaire             </div>             <br>                              Commerces & bibliothèque ➡️ La Grange : <b><span style="color: #71be20;">4 min</span></b><br>                 Commerces & bibliothèque ⬅️ La Grange : <b><span style="color: #71be20;">4 min</span></b><br>                  (Moyenne : <b><span style="color: #71be20;">4 min</span></b>)<br>                           <div style="text-align: center; margin-top: 15px;">                 <a href='https://geovelo.app/fr/route/?from=2.933114%2C42.731733&to=2.940409%2C42.735502' target='_blank' style="                     display: inline-block;                     padding: 10px 20px;                     background-color: #71be20;                     color: white;                     text-decoration: none;                     border-radius: 25px;                     font-weight: bold;                     box-shadow: 0px 3px 6px rgba(0,0,0,0.2);                     transition: all 0.3s ease;                 ">Aller à l'itinéraire Géovélo</a>             </div>         </div>      </div>`)[0];
                popup_f996bc77114ef42106957eba7c7c9d4a.setContent(html_70d934d0a8c7c46943b336e574b0194d);
            
        
        poly_line_4bb75360f9085ce2e22f62c8bc178bed.bindPopup(popup_f996bc77114ef42106957eba7c7c9d4a);
        ;

        // New behaviour *************
        

        var isMouseOverLine = false;
        var isMouseOverPopup = false;
        var timeoutId = null;

        
        // Open Popup over Line
        poly_line_4bb75360f9085ce2e22f62c8bc178bed.on('mouseover', function (e) {
            isMouseOverLine=true;
            this.openPopup();
            if (timeoutId) {
                clearTimeout(timeoutId);
                timeoutId = null;
        }});


        // Check if Mouse is still Over Line
        poly_line_4bb75360f9085ce2e22f62c8bc178bed.on('mouseout', function (e) {
            isMouseOverLine=false;});
        
        // Check if Mouse is still over Popup (much more complex)
        document.addEventListener('mousemove', function(e) {
            var popupContainer = document.querySelector('.leaflet-popup');
            if (popupContainer) {
                var rect = popupContainer.getBoundingClientRect();
                var mouseX = e.clientX;
                var mouseY = e.clientY;
        
                isMouseOverPopup = (
                    mouseX >= rect.left &&
                    mouseX <= rect.right &&
                    mouseY >= rect.top &&
                    mouseY <= rect.bottom
                );
                if (isMouseOverPopup && timeoutId) {
                    clearTimeout(timeoutId);
                    timeoutId = null;
        }        }});


        
        // Close Popup if Mouse left the line and the popup for more than 2 seconds

        function ClosePopup(that) {
            setTimeout(function() {
                if (!isMouseOverPopup && !isMouseOverLine) {
                    that.closePopup();
                } else {
                    setTimeout(function() {
                        ClosePopup(that);
                    }, 1000); // 1000 ms = 1s
                }
            }, 2000); // 2000 ms = 2s
        }


        
        poly_line_4bb75360f9085ce2e22f62c8bc178bed.on('mouseout', function (e) {
            ClosePopup(this)});

        // End new behaviour *************

        
    
    
            var marker_a11934660bc38b90d3c3d2817572afe9 = L.marker(
                [42.73317107479224, 2.9372353656509693],
                {
  "draggable": false,
  "autoPan": true,
  "maxZoom": 20,
  "id": "Commerces \u0026 biblioth\u00e8queLa Grange",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_1c00555e684a0972586e136e10d152a2 = L.divIcon({
  "html": "\n    \u003cdiv style=\"font-size: 12px;\n                color: #71be20;\n                font-weight: bold;\n                width: 70px;\n                position: absolute;\n                top: 00px;\n                left: 00px;\n                text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n          \u003cspan style=\"font-size: 13px; position: relative; top: -2px;right:-8px;\"\u003e\u003c/span\u003e\n                \u003cspan style=\"font-size: 16px;\"\u003e\ud83d\udeb2\u003c/span\u003e 4\u0027\n    \u003c/div\u003e\n    ",
  "className": "empty",
});
            marker_a11934660bc38b90d3c3d2817572afe9.setIcon(div_icon_1c00555e684a0972586e136e10d152a2);
        
    
                marker_a11934660bc38b90d3c3d2817572afe9.setIcon(div_icon_1c00555e684a0972586e136e10d152a2);
            
    
            var poly_line_ac026e63dfca3ce01287a101ef8216bc = L.polyline(
                [[42.735502, 2.940409], [42.73516533628809, 2.940387491966759], [42.73483083988919, 2.9403759994459833], [42.73449851080331, 2.940374522437673], [42.73416834903047, 2.9403830609418287], [42.733840354570646, 2.940401614958449], [42.73351452742382, 2.9404301844875347], [42.73319086759002, 2.940468769529085], [42.73286937506925, 2.9405173700831027], [42.7325500498615, 2.940575986149585], [42.73223289196676, 2.9406446177285317], [42.731917901385046, 2.940723264819945], [42.731605078116345, 2.9408119274238227], [42.731294422160666, 2.940910605540166], [42.730985933518, 2.9410192991689748], [42.73067961218837, 2.94113800831025], [42.73037545817174, 2.9412667329639888], [42.730073471468145, 2.941405473130194], [42.729773652077554, 2.9415542288088643], [42.729476, 2.941713]],
                {"bubblingMouseEvents": true, "color": "#71be20", "dashArray": "20,10", "dashOffset": null, "fill": false, "fillColor": "#71be20", "fillOpacity": 0.2, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "noClip": false, "opacity": 1.0, "smoothFactor": 1.0, "stroke": true, "weight": 7}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
        var popup_f280a0ee63538b30a59434292d0a793a = L.popup({"max_width": 1200});
        
            
                var html_1ba04779913850bbf3f2397b1ca31e60 = $(`<div id="html_1ba04779913850bbf3f2397b1ca31e60" style="width: 100.0%; height: 100.0%;">             <div style="             font-size: 14px;             font-family: 'Arial', sans-serif;             text-align: center;         ">             <div style="font-weight: bold; font-size: 16px; margin-bottom: 10px;">                   <span style="font-size: 13px; position: relative; top: -2px;right:-8px;"></span>                 <span style="font-size: 16px;">🚲</span>  Itinéraire à Vélo musculaire             </div>             <br>                              La Grange ➡️ Maison de Santé : <b><span style="color: #71be20;">5 min</span></b><br>                 La Grange ⬅️ Maison de Santé : <b><span style="color: #71be20;">4 min</span></b><br>                  (Moyenne : <b><span style="color: #71be20;">4 min</span></b>)<br>                           <div style="text-align: center; margin-top: 15px;">                 <a href='https://geovelo.app/fr/route/?from=2.940409%2C42.735502&to=2.941713%2C42.729476' target='_blank' style="                     display: inline-block;                     padding: 10px 20px;                     background-color: #71be20;                     color: white;                     text-decoration: none;                     border-radius: 25px;                     font-weight: bold;                     box-shadow: 0px 3px 6px rgba(0,0,0,0.2);                     transition: all 0.3s ease;                 ">Aller à l'itinéraire Géovélo</a>             </div>         </div>      </div>`)[0];
                popup_f280a0ee63538b30a59434292d0a793a.setContent(html_1ba04779913850bbf3f2397b1ca31e60);
            
        
        poly_line_ac026e63dfca3ce01287a101ef8216bc.bindPopup(popup_f280a0ee63538b30a59434292d0a793a);
        ;

        // New behaviour *************
        

        var isMouseOverLine = false;
        var isMouseOverPopup = false;
        var timeoutId = null;

        
        // Open Popup over Line
        poly_line_ac026e63dfca3ce01287a101ef8216bc.on('mouseover', function (e) {
            isMouseOverLine=true;
            this.openPopup();
            if (timeoutId) {
                clearTimeout(timeoutId);
                timeoutId = null;
        }});


        // Check if Mouse is still Over Line
        poly_line_ac026e63dfca3ce01287a101ef8216bc.on('mouseout', function (e) {
            isMouseOverLine=false;});
        
        // Check if Mouse is still over Popup (much more complex)
        document.addEventListener('mousemove', function(e) {
            var popupContainer = document.querySelector('.leaflet-popup');
            if (popupContainer) {
                var rect = popupContainer.getBoundingClientRect();
                var mouseX = e.clientX;
                var mouseY = e.clientY;
        
                isMouseOverPopup = (
                    mouseX >= rect.left &&
                    mouseX <= rect.right &&
                    mouseY >= rect.top &&
                    mouseY <= rect.bottom
                );
                if (isMouseOverPopup && timeoutId) {
                    clearTimeout(timeoutId);
                    timeoutId = null;
        }        }});


        
        // Close Popup if Mouse left the line and the popup for more than 2 seconds

        function ClosePopup(that) {
            setTimeout(function() {
                if (!isMouseOverPopup && !isMouseOverLine) {
                    that.closePopup();
                } else {
                    setTimeout(function() {
                        ClosePopup(that);
                    }, 1000); // 1000 ms = 1s
                }
            }, 2000); // 2000 ms = 2s
        }


        
        poly_line_ac026e63dfca3ce01287a101ef8216bc.on('mouseout', function (e) {
            ClosePopup(this)});

        // End new behaviour *************

        
    
    
            var marker_12cc29531b1cbb34149a0b62b653f37f = L.marker(
                [42.73223289196676, 2.9406446177285317],
                {
  "draggable": false,
  "autoPan": true,
  "maxZoom": 20,
  "id": "La GrangeMaison de Sant\u00e9",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_ac66889bd23ffaebdd99d95e0dc28a32 = L.divIcon({
  "html": "\n    \u003cdiv style=\"font-size: 12px;\n                color: #71be20;\n                font-weight: bold;\n                width: 70px;\n                position: absolute;\n                top: 00px;\n                left: 00px;\n                text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n          \u003cspan style=\"font-size: 13px; position: relative; top: -2px;right:-8px;\"\u003e\u003c/span\u003e\n                \u003cspan style=\"font-size: 16px;\"\u003e\ud83d\udeb2\u003c/span\u003e 4\u0027\n    \u003c/div\u003e\n    ",
  "className": "empty",
});
            marker_12cc29531b1cbb34149a0b62b653f37f.setIcon(div_icon_ac66889bd23ffaebdd99d95e0dc28a32);
        
    
                marker_12cc29531b1cbb34149a0b62b653f37f.setIcon(div_icon_ac66889bd23ffaebdd99d95e0dc28a32);
            
    
            var circle_marker_18f01d34f64e52f59662fe34ee90be72 = L.circleMarker(
                [42.729897, 2.934723],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "white", "fillOpacity": 1, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 1.5}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            circle_marker_18f01d34f64e52f59662fe34ee90be72.bindTooltip(
                `<div>
                     <div style="font-size: 13px; font-weight: bold;">Hôtel de ville</div>
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            var marker_0e6ee15c9c0f94a9a970305a97c06f8a = L.marker(
                [42.730897, 2.935723],
                {
  "draggable": false,
  "autoPan": true,
  "zIndexOffset": 1000,
  "id": "H\u00f4tel de ville",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_653127908a014b856281851af1228227 = L.divIcon({
  "html": "\n        \u003cdiv style=\"font-size: 9px;\n                    color: black;\n                    font-weight: bold;\n                    width: 70px;\n                    position: relative;\n                    top: 10px;\n                    left: 10px;\n                    text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n            H\u00f4tel de ville\n        \u003c/div\u003e\n        ",
  "className": "empty",
});
            marker_0e6ee15c9c0f94a9a970305a97c06f8a.setIcon(div_icon_653127908a014b856281851af1228227);
        
    
                marker_0e6ee15c9c0f94a9a970305a97c06f8a.setIcon(div_icon_653127908a014b856281851af1228227);
            
    
            var circle_marker_427ac8ec71676c604a1723b8c7b5ecbd = L.circleMarker(
                [42.726274, 2.934229],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "white", "fillOpacity": 1, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 1.5}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            circle_marker_427ac8ec71676c604a1723b8c7b5ecbd.bindTooltip(
                `<div>
                     <div style="font-size: 13px; font-weight: bold;">École Jean Moulin</div>
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            var marker_01db968dd3cdaea9de5447aa58c51687 = L.marker(
                [42.727273999999994, 2.935229],
                {
  "draggable": false,
  "autoPan": true,
  "zIndexOffset": 1000,
  "id": "\u00c9cole Jean Moulin",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_d732c30cbac1a520baa556a65d12941d = L.divIcon({
  "html": "\n        \u003cdiv style=\"font-size: 9px;\n                    color: black;\n                    font-weight: bold;\n                    width: 70px;\n                    position: relative;\n                    top: 10px;\n                    left: 10px;\n                    text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n            \u00c9cole Jean Moulin\n        \u003c/div\u003e\n        ",
  "className": "empty",
});
            marker_01db968dd3cdaea9de5447aa58c51687.setIcon(div_icon_d732c30cbac1a520baa556a65d12941d);
        
    
                marker_01db968dd3cdaea9de5447aa58c51687.setIcon(div_icon_d732c30cbac1a520baa556a65d12941d);
            
    
            var circle_marker_7020bc949b12128768336975c84e34d2 = L.circleMarker(
                [42.731733, 2.933114],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "white", "fillOpacity": 1, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 1.5}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            circle_marker_7020bc949b12128768336975c84e34d2.bindTooltip(
                `<div>
                     <div style="font-size: 13px; font-weight: bold;">Commerces & bibliothèque</div>
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            var marker_3bf5d0b2358baa6b7c5f1a19528d915e = L.marker(
                [42.732732999999996, 2.934114],
                {
  "draggable": false,
  "autoPan": true,
  "zIndexOffset": 1000,
  "id": "Commerces \u0026 biblioth\u00e8que",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_372af7edd5eb7ede854b705c090ccb0a = L.divIcon({
  "html": "\n        \u003cdiv style=\"font-size: 9px;\n                    color: black;\n                    font-weight: bold;\n                    width: 70px;\n                    position: relative;\n                    top: 10px;\n                    left: 10px;\n                    text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n            Commerces \u0026 biblioth\u00e8que\n        \u003c/div\u003e\n        ",
  "className": "empty",
});
            marker_3bf5d0b2358baa6b7c5f1a19528d915e.setIcon(div_icon_372af7edd5eb7ede854b705c090ccb0a);
        
    
                marker_3bf5d0b2358baa6b7c5f1a19528d915e.setIcon(div_icon_372af7edd5eb7ede854b705c090ccb0a);
            
    
            var circle_marker_6eac1f91ecef4a13c54b9bbaa30ad668 = L.circleMarker(
                [42.726981, 2.942576],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "white", "fillOpacity": 1, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 1.5}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            circle_marker_6eac1f91ecef4a13c54b9bbaa30ad668.bindTooltip(
                `<div>
                     <div style="font-size: 13px; font-weight: bold;">Les Jardins de la Palmeraie</div>
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            var marker_30529a47e1d8437166cae90656aa12c1 = L.marker(
                [42.727981, 2.9435759999999997],
                {
  "draggable": false,
  "autoPan": true,
  "zIndexOffset": 1000,
  "id": "Les Jardins de la Palmeraie",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_98e20af1cc5f02c864f2794a524e2fa2 = L.divIcon({
  "html": "\n        \u003cdiv style=\"font-size: 9px;\n                    color: black;\n                    font-weight: bold;\n                    width: 70px;\n                    position: relative;\n                    top: 10px;\n                    left: 10px;\n                    text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n            Les Jardins de la Palmeraie\n        \u003c/div\u003e\n        ",
  "className": "empty",
});
            marker_30529a47e1d8437166cae90656aa12c1.setIcon(div_icon_98e20af1cc5f02c864f2794a524e2fa2);
        
    
                marker_30529a47e1d8437166cae90656aa12c1.setIcon(div_icon_98e20af1cc5f02c864f2794a524e2fa2);
            
    
            var circle_marker_ccdbd6741f13fdb2fbc973a20aa18515 = L.circleMarker(
                [42.73049, 2.92979],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "white", "fillOpacity": 1, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 1.5}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            circle_marker_ccdbd6741f13fdb2fbc973a20aa18515.bindTooltip(
                `<div>
                     <div style="font-size: 13px; font-weight: bold;">Parc des Sports et Loisirs</div>
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            var marker_552e1768e55229030f20a744456dc796 = L.marker(
                [42.73149, 2.93079],
                {
  "draggable": false,
  "autoPan": true,
  "zIndexOffset": 1000,
  "id": "Parc des Sports et Loisirs",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_86b2ae5b931a82982ad415fd24a8e7bb = L.divIcon({
  "html": "\n        \u003cdiv style=\"font-size: 9px;\n                    color: black;\n                    font-weight: bold;\n                    width: 70px;\n                    position: relative;\n                    top: 10px;\n                    left: 10px;\n                    text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n            Parc des Sports et Loisirs\n        \u003c/div\u003e\n        ",
  "className": "empty",
});
            marker_552e1768e55229030f20a744456dc796.setIcon(div_icon_86b2ae5b931a82982ad415fd24a8e7bb);
        
    
                marker_552e1768e55229030f20a744456dc796.setIcon(div_icon_86b2ae5b931a82982ad415fd24a8e7bb);
            
    
            var circle_marker_37d867d454e0f5dab90f1861e563245c = L.circleMarker(
                [42.735502, 2.940409],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "white", "fillOpacity": 1, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 1.5}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            circle_marker_37d867d454e0f5dab90f1861e563245c.bindTooltip(
                `<div>
                     <div style="font-size: 13px; font-weight: bold;">La Grange</div>
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            var marker_07bd9a84208ba2b8622e5f6028673309 = L.marker(
                [42.736501999999994, 2.9414089999999997],
                {
  "draggable": false,
  "autoPan": true,
  "zIndexOffset": 1000,
  "id": "La Grange",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_654a2e380d4d61f08ef445aec91e2355 = L.divIcon({
  "html": "\n        \u003cdiv style=\"font-size: 9px;\n                    color: black;\n                    font-weight: bold;\n                    width: 70px;\n                    position: relative;\n                    top: 10px;\n                    left: 10px;\n                    text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n            La Grange\n        \u003c/div\u003e\n        ",
  "className": "empty",
});
            marker_07bd9a84208ba2b8622e5f6028673309.setIcon(div_icon_654a2e380d4d61f08ef445aec91e2355);
        
    
                marker_07bd9a84208ba2b8622e5f6028673309.setIcon(div_icon_654a2e380d4d61f08ef445aec91e2355);
            
    
            var circle_marker_5745050bc6f1c9572dbc718b6be00dbc = L.circleMarker(
                [42.723386, 2.932491],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "white", "fillOpacity": 1, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 1.5}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            circle_marker_5745050bc6f1c9572dbc718b6be00dbc.bindTooltip(
                `<div>
                     <div style="font-size: 13px; font-weight: bold;">Le fournil de l'épi d'or</div>
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            var marker_ba7303fa473cc63cbb99b67995819664 = L.marker(
                [42.724385999999996, 2.933491],
                {
  "draggable": false,
  "autoPan": true,
  "zIndexOffset": 1000,
  "id": "Le fournil de l\u0027\u00e9pi d\u0027or",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_d36bd2d5f065498d6a2c2a399162f8fa = L.divIcon({
  "html": "\n        \u003cdiv style=\"font-size: 9px;\n                    color: black;\n                    font-weight: bold;\n                    width: 70px;\n                    position: relative;\n                    top: 10px;\n                    left: 10px;\n                    text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n            Le fournil de l\u0027\u00e9pi d\u0027or\n        \u003c/div\u003e\n        ",
  "className": "empty",
});
            marker_ba7303fa473cc63cbb99b67995819664.setIcon(div_icon_d36bd2d5f065498d6a2c2a399162f8fa);
        
    
                marker_ba7303fa473cc63cbb99b67995819664.setIcon(div_icon_d36bd2d5f065498d6a2c2a399162f8fa);
            
    
            var circle_marker_8ca99bf25602a4264ae79641b63c0757 = L.circleMarker(
                [42.729476, 2.941713],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "white", "fillOpacity": 1, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 1.5}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            circle_marker_8ca99bf25602a4264ae79641b63c0757.bindTooltip(
                `<div>
                     <div style="font-size: 13px; font-weight: bold;">Maison de Santé</div>
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            var marker_40a6dfdf213607107ec413a712fa0943 = L.marker(
                [42.730475999999996, 2.942713],
                {
  "draggable": false,
  "autoPan": true,
  "zIndexOffset": 1000,
  "id": "Maison de Sant\u00e9",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_ca33fb11429cd5775b423a263346ac82 = L.divIcon({
  "html": "\n        \u003cdiv style=\"font-size: 9px;\n                    color: black;\n                    font-weight: bold;\n                    width: 70px;\n                    position: relative;\n                    top: 10px;\n                    left: 10px;\n                    text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n            Maison de Sant\u00e9\n        \u003c/div\u003e\n        ",
  "className": "empty",
});
            marker_40a6dfdf213607107ec413a712fa0943.setIcon(div_icon_ca33fb11429cd5775b423a263346ac82);
        
    
                marker_40a6dfdf213607107ec413a712fa0943.setIcon(div_icon_ca33fb11429cd5775b423a263346ac82);
            
    
            var circle_marker_5659704ca91bef069503f18701089c22 = L.circleMarker(
                [42.721492, 2.933532],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "white", "fillOpacity": 1, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 1.5}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            circle_marker_5659704ca91bef069503f18701089c22.bindTooltip(
                `<div>
                     <div style="font-size: 13px; font-weight: bold;">Super U</div>
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            var marker_0237ca7e1d5f544a1c4278f475c45268 = L.marker(
                [42.722491999999995, 2.934532],
                {
  "draggable": false,
  "autoPan": true,
  "zIndexOffset": 1000,
  "id": "Super U",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_f45b1b8552abd24c03081e1a1f2c567b = L.divIcon({
  "html": "\n        \u003cdiv style=\"font-size: 9px;\n                    color: black;\n                    font-weight: bold;\n                    width: 70px;\n                    position: relative;\n                    top: 10px;\n                    left: 10px;\n                    text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n            Super U\n        \u003c/div\u003e\n        ",
  "className": "empty",
});
            marker_0237ca7e1d5f544a1c4278f475c45268.setIcon(div_icon_f45b1b8552abd24c03081e1a1f2c567b);
        
    
                marker_0237ca7e1d5f544a1c4278f475c45268.setIcon(div_icon_f45b1b8552abd24c03081e1a1f2c567b);
            
    
            var circle_marker_3d9123985a0686ac75e9ccc3173f4ed3 = L.circleMarker(
                [42.730382, 2.925099],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "white", "fillOpacity": 1, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 1.5}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            circle_marker_3d9123985a0686ac75e9ccc3173f4ed3.bindTooltip(
                `<div>
                     <div style="font-size: 13px; font-weight: bold;">Utile & Pain du jour</div>
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            var marker_518d10319f1360d601cc6342262da682 = L.marker(
                [42.731381999999996, 2.926099],
                {
  "draggable": false,
  "autoPan": true,
  "zIndexOffset": 1000,
  "id": "Utile \u0026 Pain du jour",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_674fcff9350157ad74e9713bb66c62e3 = L.divIcon({
  "html": "\n        \u003cdiv style=\"font-size: 9px;\n                    color: black;\n                    font-weight: bold;\n                    width: 70px;\n                    position: relative;\n                    top: 10px;\n                    left: 10px;\n                    text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n            Utile \u0026 Pain du jour\n        \u003c/div\u003e\n        ",
  "className": "empty",
});
            marker_518d10319f1360d601cc6342262da682.setIcon(div_icon_674fcff9350157ad74e9713bb66c62e3);
        
    
                marker_518d10319f1360d601cc6342262da682.setIcon(div_icon_674fcff9350157ad74e9713bb66c62e3);
            
    
            var circle_marker_b6c9006632306ffa355d5459bd93fe54 = L.circleMarker(
                [42.739851, 2.926113],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "white", "fillOpacity": 1, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 1.5}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            circle_marker_b6c9006632306ffa355d5459bd93fe54.bindTooltip(
                `<div>
                     <div style="font-size: 13px; font-weight: bold;">Collège Jean Rous</div>
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            var marker_0c2cea86fb7cbd9efc7bbd2e4a10d82e = L.marker(
                [42.740851, 2.927113],
                {
  "draggable": false,
  "autoPan": true,
  "zIndexOffset": 1000,
  "id": "Coll\u00e8ge Jean Rous",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_878e9393f6f3cee77d16b65ccb99e220 = L.divIcon({
  "html": "\n        \u003cdiv style=\"font-size: 9px;\n                    color: black;\n                    font-weight: bold;\n                    width: 70px;\n                    position: relative;\n                    top: 10px;\n                    left: 10px;\n                    text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n            Coll\u00e8ge Jean Rous\n        \u003c/div\u003e\n        ",
  "className": "empty",
});
            marker_0c2cea86fb7cbd9efc7bbd2e4a10d82e.setIcon(div_icon_878e9393f6f3cee77d16b65ccb99e220);
        
    
                marker_0c2cea86fb7cbd9efc7bbd2e4a10d82e.setIcon(div_icon_878e9393f6f3cee77d16b65ccb99e220);
            
    
            var circle_marker_c51466eafeaae68c5435989480d9abd6 = L.circleMarker(
                [42.721782, 2.93939],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "white", "fillOpacity": 1, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 1.5}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            circle_marker_c51466eafeaae68c5435989480d9abd6.bindTooltip(
                `<div>
                     <div style="font-size: 13px; font-weight: bold;">Las Palades</div>
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            var marker_083cbc0b97a8f7c60159c4876e4b171c = L.marker(
                [42.722781999999995, 2.94039],
                {
  "draggable": false,
  "autoPan": true,
  "zIndexOffset": 1000,
  "id": "Las Palades",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_afeddc4c156596368cab51607896c4e8 = L.divIcon({
  "html": "\n        \u003cdiv style=\"font-size: 9px;\n                    color: black;\n                    font-weight: bold;\n                    width: 70px;\n                    position: relative;\n                    top: 10px;\n                    left: 10px;\n                    text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n            Las Palades\n        \u003c/div\u003e\n        ",
  "className": "empty",
});
            marker_083cbc0b97a8f7c60159c4876e4b171c.setIcon(div_icon_afeddc4c156596368cab51607896c4e8);
        
    
                marker_083cbc0b97a8f7c60159c4876e4b171c.setIcon(div_icon_afeddc4c156596368cab51607896c4e8);
            
    
            var circle_marker_34d1717b52ab20464d27a7b57e4b86f3 = L.circleMarker(
                [42.730056, 2.922288],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "white", "fillOpacity": 1, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 1.5}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            circle_marker_34d1717b52ab20464d27a7b57e4b86f3.bindTooltip(
                `<div>
                     <div style="font-size: 13px; font-weight: bold;">Les Cottages de Perpignan</div>
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            var marker_cf1604ea5c02f06f22959d7cf3903bbc = L.marker(
                [42.731055999999995, 2.923288],
                {
  "draggable": false,
  "autoPan": true,
  "zIndexOffset": 1000,
  "id": "Les Cottages de Perpignan",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_183b0cb960d162da7b03f9ac9029a242 = L.divIcon({
  "html": "\n        \u003cdiv style=\"font-size: 9px;\n                    color: black;\n                    font-weight: bold;\n                    width: 70px;\n                    position: relative;\n                    top: 10px;\n                    left: 10px;\n                    text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n            Les Cottages de Perpignan\n        \u003c/div\u003e\n        ",
  "className": "empty",
});
            marker_cf1604ea5c02f06f22959d7cf3903bbc.setIcon(div_icon_183b0cb960d162da7b03f9ac9029a242);
        
    
                marker_cf1604ea5c02f06f22959d7cf3903bbc.setIcon(div_icon_183b0cb960d162da7b03f9ac9029a242);
            
    
            var circle_marker_e6727d8ea2053bb6cbe77f634ea0776d = L.circleMarker(
                [42.716058, 2.932749],
                {"bubblingMouseEvents": true, "color": "black", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "white", "fillOpacity": 1, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 1.5}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            circle_marker_e6727d8ea2053bb6cbe77f634ea0776d.bindTooltip(
                `<div>
                     <div style="font-size: 13px; font-weight: bold;">Rond-point du millénaire</div>
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            var marker_8cb12deb1bcc80cd55ef1468aac4e488 = L.marker(
                [42.717057999999994, 2.9337489999999997],
                {
  "draggable": false,
  "autoPan": true,
  "zIndexOffset": 1000,
  "id": "Rond-point du mill\u00e9naire",
}
            ).addTo(map_47ff86c75c59e914af23eed7e70bae87);
        
    
            var div_icon_961844b462f065409bda96ae7004a8c8 = L.divIcon({
  "html": "\n        \u003cdiv style=\"font-size: 9px;\n                    color: black;\n                    font-weight: bold;\n                    width: 70px;\n                    position: relative;\n                    top: 10px;\n                    left: 10px;\n                    text-shadow: -2px -2px 0 #f2f2f2, -2px -1px 0 #f2f2f2, -2px 0px 0 #f2f2f2, -2px 1px 0 #f2f2f2, -2px 2px 0 #f2f2f2, -1px -2px 0 #f2f2f2, -1px -1px 0 #f2f2f2, -1px 0px 0 #f2f2f2, -1px 1px 0 #f2f2f2, -1px 2px 0 #f2f2f2, 0px -2px 0 #f2f2f2, 0px -1px 0 #f2f2f2, 0px 1px 0 #f2f2f2, 0px 2px 0 #f2f2f2, 1px -2px 0 #f2f2f2, 1px -1px 0 #f2f2f2, 1px 0px 0 #f2f2f2, 1px 1px 0 #f2f2f2, 1px 2px 0 #f2f2f2, 2px -2px 0 #f2f2f2, 2px -1px 0 #f2f2f2, 2px 0px 0 #f2f2f2, 2px 1px 0 #f2f2f2, 2px 2px 0 #f2f2f2;\"\u003e\n            Rond-point du mill\u00e9naire\n        \u003c/div\u003e\n        ",
  "className": "empty",
});
            marker_8cb12deb1bcc80cd55ef1468aac4e488.setIcon(div_icon_961844b462f065409bda96ae7004a8c8);
        
    
                marker_8cb12deb1bcc80cd55ef1468aac4e488.setIcon(div_icon_961844b462f065409bda96ae7004a8c8);
            
</script>
</html> 