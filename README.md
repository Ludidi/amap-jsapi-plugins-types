# amap-jsapi-plugins-types

高德地图 jsapi2.0 插件类型声明

> 由于官方提供的 ts 声明文件仅包含核心文件的接口，不包含插件的接口，因此本库为插件 DTS。`在使用前请先引入核心类型库，详情可查看`[https://www.npmjs.com/package/@amap/amap-jsapi-types](https://www.npmjs.com/package/@amap/amap-jsapi-types)

拷贝 types/amap 文件夹下所引用的插件放置于自己的项目下

# Tips

1. 由于高德地图 2.0 文档上大部分类型给的不是很明确，会从 1.x 版本中查找对应的类型，实际可能会有出入，欢迎提 PR
2. 官方提供的核心声明文件与实际开发也会有出入，建议直接 copy 官方核心文件本地修改

## Plugins 列表

- [x] AMap.Geocoder
- [x] AMap.CircleEditor
- [x] AMap.PolygonEditor
- [x] AMap.MouseTool
- [x] AMap.MarkerCluster
- [x] AMap.ElasticMarker
- [x] AMap.ToolBar
- [x] AMap.Scale
- [x] AMap.HawkEye
- [x] AMap.MapType
- [x] AMap.Geolocation
- [x] AMap.AutoComplete
- [x] AMap.PlaceSearch
- [x] AMap.DistrictSearch
- [x] AMap.LineSearch
- [x] AMap.StationSearch
- [x] AMap.Driving
- [x] AMap.TruckDriving
- [x] AMap.Transfer
- [x] AMap.Walking
- [x] AMap.Riding
- [x] AMap.DragRoute
- [x] AMap.ArrivalRange
- [x] AMap.CitySearch
- [x] AMap.PolylineEditor
- [x] AMap.RangingTool
- [x] AMap.CloudDataSearch
- [x] AMap.Weather
- [x] AMap.HeatMap
- [ ] ~~AMap.AdvancedInfoWindow~~ `暂无文档`
- [ ] ~~AMap.RoadInfoSearch~~ `已停止数据更新，反馈信息仅供参考`
- [ ] ~~AMap.CloudDataLayer~~ `服务停止维护，请勿使用`
- [ ] ~~AMap.PlaceSearchLayer~~ `服务已下线，请勿使用`
