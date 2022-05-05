# folk music 基于网易云音乐

**uniapp 项目。**
<a href="https://folk-music.vercel.app" target="_blank">在线演示地址</a>

# 参考项目

GitHub 网易云音乐接口开源项目
[网易云音乐接口 Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi)

# 已验证运行的平台

<table>
	<tr>
		<td>平台</td>
		<td>能否运行</td>
	</tr>
	<tr>
		<td>H5</td>
		<td>可以</td>
	</tr>
	<tr>
		<td>微信小程序</td>
		<td>可以</td>
	</tr>
	<tr>
		<td>安卓App</td>
		<td>可以</td>
	</tr>
	<tr>
		<td>IOS App</td>
		<td>没有苹果设备</td>
	</tr>
</table>
# 项目介绍

### 主要特点如下：

1. 对接口进行进一步的封装，调用接口变得简单；
2. 新增音乐播放界面，配合 globalData 全局变量，只维护一个 audioContext 上下文；
3. 使用 uniapp 提供的动画接口编写动画；
4. 配合 vuex 状态管理，监听音乐播放的状态数据；
5. 引入音乐播放进度、缓存进度条监听；
6. 解析歌曲的 lrc 歌词数据，一并展示；
7. 视频播放界面上下滑动切换；
8. nvue 原生组件解决视频层级过高问题
9. 引入搜索功能，综合、单曲、歌单、视频等；
10. 解决微信小程序一些样式兼容问题，一些第三方组件、image 都需要使用 view 组件包裹；

# 项目描述

看到了网易云接口的开源项目后，想配合做一个前端页面，顺便熟悉 uniapp；这是一个基于 uniapp 开发的媒体类项目，比较小众，主要功能点是歌曲搜索；音乐、视频播放、规范化开发、以及 animation 动画的使用等等。因为需求受众较少，只是做学习用，可参考的地方还是有的，后续应该做一些业务需求广的项目。

# 技术点

1. sass - npm install sass
2. uView - 一套不错的兼容多端的 ui 框架
3. vuex 状态监听
4. 音乐播放，uniapp animation 动画
5. lrc 歌词解析
6. 视频播放
7. 搜索功能
8. 等等...

# 项目演示

## H5 演示地址

pc 端查看按 F12。[演示地址](https://folk-music.vercel.app/#/)

# 项目预览

    这里展示微信小程序端，uniapp是多端兼容的，效果差不多

## 首页

<table >
	<tr>
		<td ><img src="./doc/images/首页-热门MV.png"></td>
		<td><img src="./doc/images/首页.png"></td>
		<td><img src="./doc/images/首页-我的.png"></td>
	</tr>
</table>

## 搜索

<table >
	<tr>
		<td ><img src="./doc/images/搜索.png"></td>
		<td><img src="./doc/images/搜索-综合结果.png"></td>
	</tr>
</table>

<table >
	<tr>
		<td ><img src="./doc/images/搜索-单曲.png"></td>
		<td><img src="./doc/images/搜索-视频.png"></td>
	</tr>
</table>

## 歌手介绍页

<table >
	<tr>
		<td ><img src="./doc/images/歌手.png"></td>
	</tr>
</table>

## 专辑/歌单

<table >
	<tr>
		<td ><img src="./doc/images/专辑.png"></td>
		<td><img src="./doc/images/专辑-评论.png"></td>
	</tr>
</table>

## 音乐播放页

<table >
	<tr>
		<td ><img src="./doc/images/音乐.png"></td>
		<td><img src="./doc/images/音乐-歌词.png"></td>
	</tr>
</table>

## 视频播放页

<table >
	<tr>
		<td ><img src="./doc/images/视频.png"></td>
		<td><img src="./doc/images/视频-评论.png"></td>
	</tr>
</table>
# 

