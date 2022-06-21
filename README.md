# CEIV (Chinese Earthquake Information Viewer)
🌐 一个开源的中国地震信息可视化项目。

基于HTML、JavaScript、Mapbox GL JS。

## 功能
- ℹ️ 中国地震速报信息整合
- 🚨 中国地震预警信息整合
  - ⭕️ 横、纵波可视化显示
  - 3️⃣2️⃣1️⃣ 自定位置横波抵达倒数、烈度粗估
- ℹ️ 重庆北碚测站信息整合 (https://wolfx.jp/home/rpishake.html)

## 使用方法
1. 到```js/api.js```填入对应的信息api。例：
```
//地震速报
var infoApi = "https://**.**/**" //填入地震速报api链接
var infoInstitute = "response.institute" //填入地震速报api中 发布机构 的json路径  这里已举例出
var infoOccurTime = "data.occurTime" //填入地震速报api中 地震发生时间 的json路径  这里已举例出
var infoEpicenter = "data.epicenter" //填入地震速报api中 震中 的json路径  这里已举例出
var infoMagnitude = "data.magnitude" //填入地震速报api中 地震规模 的json路径  这里已举例出
var infoDepth = "data.depth" //填入地震速报api中 震源深度 的json路径  这里已举例出
var infoMaxInt = "data.maxInt" //填入地震速报api中 最大烈度 的json路径  这里已举例出
var infoMd5 = "data.md5" //填入地震速报api中 md5 的json路径  这里已举例出

//地震预警
var eewApi = "https://**.**/**" //填入地震预警api链接
var eewInstitute = "response.institute" //填入地震预警api中 发布机构 的json路径  这里已举例出
var eewOccurTime = "data.occurTime" //填入地震预警api中 地震发生时间 的json路径  这里已举例出
var eewOccurTimestamp = "data.occurTimestamp" //填入地震预警api中 地震发生时间戳 的json路径  这里已举例出
var eewEpicenter = "data.epicenter" //填入地震预警api中 震中 的json路径  这里已举例出
var eewMagnitude = "data.magnitude" //填入地震预警api中 地震规模 的json路径  这里已举例出
var eewDepth = "data.depth" //填入地震预警api中 震源深度 的json路径  这里已举例出
var eewMaxInt = "data.maxInt" //填入地震预警api中 最大烈度 的json路径  这里已举例出
var eewMd5 = "data.md5" //填入地震预警api中 md5 的json路径  这里已举例出
```
2. 双击```index.html```运行。

## 免责声明
本开源项目仅供学习交流使用，不涉及任何 机构/私企 等的知识产权。信息源均由用户自主填写，与项目开发者无关。
