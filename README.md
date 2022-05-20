> 地图底部抽屉，可以拖拽，使用简单。免费，无广告，通用适配
**直接导入插件或者导入项目运行即可**  


> 使用简单，[使用参考demo跳转到uniapp插件市场](<https://ext.dcloud.net.cn/plugin?id=7921>)

```js
<ww-bottom-drawerapp :proportionShow='proportionvc' :dragHandleHeight="handleHeight">
	<slot>
		<!--填入你的抽屉View-->
		<view>
			
		</view>
	</slot>
</ww-bottom-drawerapp>
```
| 参数 | 类型 | 默认值 | 说明 |
| --- | --- | --- | --- |
| proportionShow |Number  |0.5|收缩后显示在外面的比例，内容高度比例 如：proportionvc:0.4  |
| dragHandleHeight |Number  |20|抽屉上的handle的高度px |
| dragLength |Number  |50|收缩或者展开需要滑动的最短距离px |
| isExpand |Boolean  |false|初始是否展开状态和动态控制展开收缩另提供状态监听@callExpand |
| transitionTime |Number  |0.5|完成剩下的展开收缩时间秒s |
| canDrag |Boolean  |true|当前是否响应外部滑动，目前使用场景：支付宝小程序 |
> 效果

![1.gif](https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/988d99a07ac046ed849132ac6cf1c7fe~tplv-k3u1fbpfcp-watermark.image?)

> 提供简洁demo
**直接导入插件或者导入项目运行即可**

![demo.png](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/6877738e778e4802a7bc4f8c6f2ef3b0~tplv-k3u1fbpfcp-watermark.image?)
> 另外添加支付小程序的效果（其他端的效果一样） 

![支付宝效果.gif](https://p9-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/558d08b74a464f2ca2b3d5c9c33e0713~tplv-k3u1fbpfcp-watermark.image?)

