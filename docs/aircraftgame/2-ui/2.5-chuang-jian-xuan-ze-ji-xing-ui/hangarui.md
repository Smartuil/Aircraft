---
description: WidgetBlueprint'/Game/UI/HangarUI.HangarUI'
---

# HangarUI

在此UI中添加如下控件，控件的具体细节请参考项目文件`WidgetBlueprint'/Game/UI/HangarUI.HangarUI'`

<div data-full-width="false">

<figure><img src="../../../.gitbook/assets/image (256).png" alt=""><figcaption></figcaption></figure>

</div>

切换到Graph页面，创建如下变量

{% hint style="info" %}
AircraftList：所有的飞机

AircraftIndex：当前选择飞机的索引值

AircraftName：当前选择飞机的名字

LoopItem：循环的飞机

IndexForSetting：设置的索引项
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (224).png" alt=""><figcaption></figcaption></figure>

添加一个名为InitHangerUI的事件，如下图

{% hint style="info" %}
逻辑很简单，就是根据传入进来的飞机实例，创建出对应的UI，并绑定点击事件
{% endhint %}

<figure><img src="../../../.gitbook/assets/BPGraphScreenshot_2023Y-07M-01D-14h-13m-30s-608_00.png" alt=""><figcaption></figcaption></figure>
