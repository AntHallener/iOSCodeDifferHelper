
# iOSCodeDifferHelper
iOS代码差异化工具, 顾名思义, 它是对于现有iOS代码进行差异化的工具, 试用版会一直提供, 开发者一直在使用和开发ing
> 您的star是我更新最大的动力

## 个人公众号
> 公众号会分享一些App Store过审相关的思路、技术、总结，感谢关注

![QRCode.png](https://i.loli.net/2019/12/30/VqJSMD4sPeBNGW5.jpg)

## 最新版本 1.1.6 2019-12-28
```
有效期到2020年1月下旬
优化了混淆规则，生成的符号更加接近开发人员编程习惯
```

部分示例:
```
类名 ASNetworking 修改为: YawNetwork
类名 AttributeView 修改为: MulticastAttributeView
类名 AudioModel 修改为: AudioRoleModel
类名 BaseViewController 修改为: InfrastructureWatchController
类名 DDSoundWaveView 修改为: FreezingVocaliseUndulationView
类名 EttsModelTableViewCell 修改为: TaskPoseTabulariseViewCell
类名 EttsModelViewController 修改为: AvModelingViewController
类名 HeChengViewController 修改为: HeAmpersandPanoramaController
类名 InputTableViewCell 修改为: StimulationDeferHorizonCell
类名 ItemView 修改为: ItemSee
类名 MainTabBarController 修改为: PrincipalChitBarController
类名 NavigationTableViewCell 修改为: NavigationTabularizeViewCell
类名 QDAudioDataSource 修改为: MissingAudioRecordingDataSource
类名 QDDemoModel 修改为: SectorDemoModel
类名 QDPcmRecorder 修改为: SentencesTLGOTRecorder
类名 QDRealTimeRecognizeViewController 修改为: GeneratingSubstantialMetreRealizeWatch
类名 SelectionTableViewCell 修改为: ChoiceDeferSentimentCell
类名 SelectionTableViewController 修改为: NaturalSelectionRemitPositionController
类名 SliderTableViewCell 修改为: PseudemysScriptaHoldOverEyeshotCell
类名 SwitchTableViewCell 修改为: ChangeOverPostponeSightCell
类名 TTDFileReader 修改为: NecessaryChargeReader
类名 TTDFileWriter 修改为: ClustersFileWriter
类名 TTSConfigViewController 修改为: RetainPickerOpinionController
类名 XHToast 修改为: MenToast
类名 selectionCellContext 修改为: pickCellContext
```


## 1. 运行环境:

```
MacOS系统 Python 3.7.3
```

## 2. 支持混淆的语言

```
Objective-C(不支持Swift)
```


## 3. 功能介绍图「此处有张图片」
![desc.png](https://i.loli.net/2019/12/30/6A7N2nwa1HrpQP3.png)



## 4. 关于试用版

```
0. 直接下载即为试用版
1. 试用版会随机混淆30%左右的代码
2. 剩余70%部分只是简单的添加前后缀字母
```

例如：
```
- (void)hello;//方法

随机被混淆:
- (void)xxx;//混淆结果未知

随机不被混淆:
- (void)aHelloB;//大概是这样,只会有前后随机字母的差别
```


## 5. 关于VIP版

```
如需VIP版本,请联系开发者
```


### VIP版本效果展示

> 同一个demo项目两次混淆结果

![result_iOSTest-0918111304.png](https://i.loli.net/2019/12/30/LPNtGDVz4Ag8u1J.png)

![result_iOSTest-0918111430.png](https://i.loli.net/2019/12/30/gXGTv1QRfAzq9io.png)


## 6.了解更多

* [Home](https://github.com/iOSCoderMaster/iOSCodeDifferHelper/wiki)

* [功能介绍](https://github.com/iOSCoderMaster/iOSCodeDifferHelper/wiki/功能介绍)

* [安装](https://github.com/iOSCoderMaster/iOSCodeDifferHelper/wiki/安装)

* [配置文件详解](https://github.com/iOSCoderMaster/iOSCodeDifferHelper/wiki/配置文件详解)

* [使用说明](https://github.com/iOSCoderMaster/iOSCodeDifferHelper/wiki/使用说明)

* [常见错误](https://github.com/iOSCoderMaster/iOSCodeDifferHelper/wiki/常见错误)

* [更新日志](https://github.com/iOSCoderMaster/iOSCodeDifferHelper/wiki/更新日志)

* [目前缺陷和开发计划](https://github.com/iOSCoderMaster/iOSCodeDifferHelper/wiki/目前缺陷和计划)






