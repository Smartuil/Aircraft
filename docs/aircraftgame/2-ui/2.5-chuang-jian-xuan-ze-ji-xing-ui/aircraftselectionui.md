---
description: WidgetBlueprint'/Game/UI/AircraftSelectionUI.AircraftSelectionUI'
---

# AircraftSelectionUI

在此UI中添加如下控件，控件的具体细节请参考项目文件`WidgetBlueprint'/Game/UI/AircraftSelectionUI.AircraftSelectionUI'`

<figure><img src="../../../.gitbook/assets/image (271).png" alt=""><figcaption></figcaption></figure>

切换到Graph页面，添加如下变量，并将新添加的变量的`InstanceEditable`和`ExposeonSpawn`打开

{% hint style="info" %}
Name：当前的名字

Index：当前选择的编号

Aircraft：当前选择飞机的实例

SelectAircraft：这是一个代理，当按下按钮的时候调用这个代理
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (272).png" alt=""><figcaption></figcaption></figure>

给`SelectionButton`创建一个点击事件，逻辑如下

<figure><img src="../../../.gitbook/assets/image (238).png" alt=""><figcaption></figcaption></figure>
