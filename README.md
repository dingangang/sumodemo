# sumodemo
版本1：实现寻找特定公交并将轨迹绘制出功能

# 用法
下载后直接运行index.html即可

# tips
1、index.html 80行指定的是长沙经纬度，即初始化显示区域在长沙。如需改变，请在
####  http://api.map.baidu.com/lbsapi/getpoint/index.html 
进行查询选定对应的经纬度即可。

2、229行 new BMap.BusLineSearch（XX市）请换成需要的城市，才能对应返回正确的巴士线路。

3、head中我是申请了百度地图的API，也可以自行成为百度地图的开发者。功能很多很强大
