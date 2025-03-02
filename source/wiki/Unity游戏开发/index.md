---
layout: wiki
wiki: Unity游戏开发
title: Unity游戏开发_地形系统
h1: Unity游戏开发_地形系统
order: 0
---
## 制作地形

### 下载导入地形资源包

{% tabs active:1 align:center %}

<!-- tab 下载位置 -->
{% link https://assetstore.unity.com/ Unity资源商店 %}

<!-- tab 导入 -->
{% mark  方法1: color:red%} 在 `菜单栏 > 窗口 > 包管理器` 导入

{% mark  方法2: color:red%} 导入已下载的资源目录为 `C:\Users\用户名\AppData\Roaming\Unity\Asset Store-5.x` (格式为*.unitypackage*)
{% endtabs %}

### 创建地形(Terrain)

{% mark 创建: color:red%} 右键左侧 `层级菜单 > 3D对象 > 地形` 创建地形

### 绘制地形(Terrain组件)

<img src="https://pic.imgdb.cn/item/65162397c458853aefe78515.png" alt="Terrain" />

#### (1)创建相邻地形

不常用,此处省略

#### (2)绘制地形

- {% mark Raise or Lower Terrain color:red%} 升高或降低地形 (左键提升高度,shift+左键降低高度)<br>

- {% mark Paint Holes color:red%} 绘制坑洞<br>

- {% mark Paint Texture color:red%} 绘制纹理 (点击编辑地形层,添加贴图)<br>

- {% mark Set Height color:red%} 将某一块区域设置为同一高度(高原)<br>

- {% mark Smooth Height color:red%} 平滑地形高度,使其更加圆润<br>

- {% mark Stamp Terrain color:red%} (不常用,此处省略)<br>

#### (3)绘制树

通过 `编辑树 > 添加树 > Tree Prefab右侧圆点 > 选择模型 > Add` 加入树模型

调整画笔参数(大小,密度,树高)来绘画出树木

#### (4)绘制细节

通过 `编辑细节 > 添加草纹理 > Detail Texture右侧圆点 > 选择模型 > Add` 加入草模型 

调整画笔参数(笔刷,大小,不透明度,目标强度)来绘画出草

#### (5)地形设置

对树和细节对象进行一系列设置,此处省略

