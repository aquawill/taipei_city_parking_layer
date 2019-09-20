## taipei_city_parking_layer
No parking lines and on-street parking spaces.
Update date:
* No parking lines: 2019-08-23 18:27:23
* On-street parking spaces: 2019-05-07 09:43:20
 
![](https://i.imgur.com/weGIMhj.jpg)
HERE XYZ: https://xyz.here.com/viewer/?project_id=118e05eb-b0cc-46ab-ad90-f6589ae3ef47

1. Data Source: Taipei City Government (https://data.taipei/#/).
    * 臺北市路邊停車格位：https://data.taipei/#/dataset/detail?id=5a911ea5-1694-4301-808e-e1780d971611
    * 臺北市禁停紅黃線路段分布圖：https://data.taipei/#/dataset/detail?id=a9c282c5-3a43-41ed-badc-f9c1bdf1cc34
2. Project from TWD97TM to WGS84.
3. Convert to raster tiles and export GeoJSON with QGIS3.
4. Upload to HERE XYZ (https://explore.xyz.here.com/) with XYZ CLI.
