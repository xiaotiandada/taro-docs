---
title: Taro.offBeaconUpdate(callback)
sidebar_label: offBeaconUpdate
---

取消监听 iBeacon 设备更新事件

支持情况：<img title="微信小程序" src={require('@site/static/img/platform/weapp.png').default} className="icon_platform" width="25px"/> <img title="H5" src={require('@site/static/img/platform/h5.png').default} className="icon_platform icon_platform--not-support" width="25px"/> <img title="React Native" src={require('@site/static/img/platform/rn.png').default} className="icon_platform icon_platform--not-support" width="25px"/> <img title="Harmony" src={require('@site/static/img/platform/harmony.png').default} className="icon_platform icon_platform--not-support" width="25px"/>

> [参考文档](https://developers.weixin.qq.com/miniprogram/dev/api/device/ibeacon/wx.offBeaconUpdate.html)

## 类型

```tsx
(callback: (res: TaroGeneral.IBeaconError) => void) => void
```

## 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| callback | `(res: TaroGeneral.IBeaconError) => void` | iBeacon 设备更新事件的回调函数 |
