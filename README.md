# wechaty-Robot

基于 wechaty-puppet-padplus

## 结构

```js
|-- src/
|---- index.js				# 入口文件
|---- config.js		  	# 配置文件
|---- onScan.js				# 机器人需要扫描二维码时监听回调
|---- onRoomJoin.js 	# 进入房间监听回调
|---- onMessage.js		# 消息监听回调
|---- onFriendShip.js	# 好友添加监听回调
|-- package.json
```

## 使用
* cnpm i 
* cnpm install wechaty@latest
* cnpm install wechaty-puppet-padplus@latest
* npm run serve

