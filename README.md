# dongguan-map-echart-concentration
东莞坐标某物浓度热力图
可根据某坐标浓度生成热力图，支持缩放。

## 库
引用echart及百度地图api，目前只支持在线状态生成热力图。

## 数据结构 
主体浓度分布数据结构如下：
```javascript
var dataday =[
[113.538056,23.031111,10156.63],
[113.807778,22.787778,2465.69],
[113.76271,23.125278,2048.69],
[113.500833,22.656111,2000.91],
[113.889508,23.091308,1981.98]
]
```
数据说明：
[经度,纬度,浓度] 匀为数值类型。

## 效果
![image](https://github.com/miracleren/dongguan-map-echart-concentration/blob/master/pic/pic1.png)
