# leaflet-canvas-test
A sample to test leaflet canvaslayer.

## 一个用来测试leaflet使用canvas渲染数据的效率

### [随机十万点在线预览](http://wandergis.com/leaflet-canvas-test/index.html)
### [12.6万数据点动态查询渲染](http://wandergis.com/leaflet-canvas-test/rtest.html)

### 随机点截图

![截图](https://raw.githubusercontent.com/wandergis/leaflet-canvas-test/gh-pages/screenshot.png)

### 12.6万数据点进行空间索引之后的查询渲染效率

![缩放等级1](https://raw.githubusercontent.com/wandergis/leaflet-canvas-test/gh-pages/zoom1.png)

![缩放等级2](https://raw.githubusercontent.com/wandergis/leaflet-canvas-test/gh-pages/zoom2.png)

![缩放等级3](https://raw.githubusercontent.com/wandergis/leaflet-canvas-test/gh-pages/zoom3.png)

![缩放等级4](https://raw.githubusercontent.com/wandergis/leaflet-canvas-test/gh-pages/zoom4.png)

### 一些思考
关于前端绘制大量数据点一直是一个老大难的问题，一方面需要在数据加载上不断优化压缩，另一方面还要考虑到前端的绘制性能，从svg到canvas到webgl。
我也对此做了很多思考，希望有兴趣的童鞋与我一起讨论这个问题。

