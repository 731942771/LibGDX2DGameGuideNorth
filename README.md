2017-07-19 11:34发布于 h t t p : / / git.oschina.net/vigiles/LibGDX2DGameGuideNorth
<br/>
<br/>

# LibGDX2D游戏开发指北
<br/>
![LibGDX2D游戏开发指北](badlogic.jpg)<br/>
<br/>
开源书籍。<br/>
在AndroidStudio环境基于1.9.6版gdx进行2D游戏开发。<br/>
<br/>
<hr/>
<hr/>
<br/>
无特殊说明，代码中的类都是gdx中的api。
<br/>

## 一.常见生成项目方法
#### 　<a href="mdbook/1.1.md#1-项目创建器" target="_blank">1.项目创建器</a>
#### 　<a href="mdbook/1.1.md#2-设置资源仓库" target="_blank">2.设置资源仓库</a>
#### 　<a href="mdbook/1.1.md#3-选择-android-后生成" target="_blank">3.选择“Android”后生成</a>
#### 　<a href="mdbook/1.1.md#4-as中编译应用" target="_blank">4.AS中编译应用</a>

<br/>
<br/>

## <a href="mdbook/2.1.md" target="_blank">二.代码</a>
#### 　<a href="mdbook/2.1.md#1-androidlauncher" target="_blank">1.AndroidLauncher</a>
#### 　<a href="mdbook/2.1.md#2-androidapplicationconfiguration " target="_blank">2.AndroidApplicationConfiguration</a>
#### 　<a href="mdbook/2.1.md#3-mygdxgame" target="_blank">3.MyGdxGame</a>
#### 　<a href="mdbook/2.1.md#4-生命周期" target="_blank">4.生命周期</a>

<br/>
<br/>

## 三.2D世界
#### 　<a href="mdbook/3.1.md#1-可视元素" target="_blank">1.可视元素</a>
###### 　　<a href="mdbook/3.1.md#1-纹理-texture-" target="_blank">1）纹理（Texture）</a>
###### 　　<a href="mdbook/3.1.md#2-区域纹理-textureRegion-" target="_blank">2）区域纹理（TextureRegion）</a>
###### 　　<a href="mdbook/3.1.md#3-映射图-pixmap-" target="_blank">3）映射图（Pixmap）</a>
###### 　　<a href="mdbook/3.1.md#4-精灵-sprite-" target="_blank">4）精灵（Sprite）</a>
###### 　　<a href="mdbook/3.1.md#5-动画-animation-" target="_blank">5）动画（Animation）</a>
###### 　　<a href="mdbook/3.1.md#6-精灵脚本-纹理画布-spritebatch-" target="_blank">6）精灵脚本/纹理画布（SpriteBatch）</a>
#### 　<a href="mdbook/3.1.md#2-演员actor" target="_blank">2.演员Actor</a>
#### 　<a href="mdbook/3.1.md#3-导演-舞台stage" target="_blank">3.导演/舞台Stage</a>
###### 　　<a href="mdbook/3.1.md#1-演员和舞台的事件" target="_blank">1）演员和舞台的事件</a>
###### 　　<a href="mdbook/3.1.md#2-演员的动作-action-" target="_blank">2）演员的动作（Action）</a>
###### 　　<a href="mdbook/3.1.md#3-执行导演-经纪人-group-" target="_blank">3）执行导演/经纪人（Group）</a>
###### 　　<a href="mdbook/3.1.md#4-视窗-viewport-" target="_blank">4）视窗（Viewport）</a>
#### 　<a href="mdbook/3.1.md#4-幕-场景screen" target="_blank">4.幕/场景Screen</a>
###### 　　<a href="mdbook/3.1.md#1-启动页" target="_blank">1）启动页</a>
###### 　　<a href="mdbook/3.1.md#2-关卡1" target="_blank">2）关卡1</a>
###### 　　<a href="mdbook/3.1.md#3-游戏总控" target="_blank">3）游戏总控</a>
###### 　　<a href="mdbook/3.1.md#4-生命周期日志" target="_blank">4）生命周期日志</a>
#### 　<a href="mdbook/3.1.md#5-游戏game" target="_blank">5.游戏Game</a>

<br/>
<br/>

## 四.控件Widget
#### 　<a href="mdbook/4.1.md#1-个体控件-widget-" target="_blank">1.个体控件（Widget）</a>
###### 　　<a href="mdbook/4.1.md#1-图片-image-" target="_blank">1）图片（Image）</a>
###### 　　<a href="mdbook/4.1.md#2-标签-label-" target="_blank">2）标签（Label）</a>
###### 　　<a href="mdbook/4.1.md#3-文本框-textfield-" target="_blank">3）文本框（TextField）</a>
###### 　　<a href="mdbook/4.1.md#4-文本域-textarea-" target="_blank">4）文本域（TextArea）</a>
###### 　　<a href="mdbook/4.1.md#5-列表-list-" target="_blank">5）列表（List）</a>
###### 　　<a href="mdbook/4.1.md#6-进度条-progressbar-和滑动条-slider-" target="_blank">6）进度条（ProgressBar）和滑动条（Slider）</a>
###### 　　<a href="mdbook/4.1.md#7-下拉列表-selectbox-" target="_blank">7）下拉列表（SelectBox）</a>
###### 　　<a href="mdbook/4.1.md#8-虚拟摇杆-touchpad-" target="_blank">8）虚拟摇杆（Touchpad）</a>
#### 　<a href="mdbook/4.1.md#2-群体控件-widgetgroup-" target="_blank">2.群体控件（WidgetGroup）</a>
###### 　　<a href="mdbook/4.1.md#1-滚动窗格-scrollpane-" target="_blank">1）滚动窗格（ScrollPane）</a>
###### 　　<a href="mdbook/4.1.md#2-树-tree-" target="_blank">2）树（Tree）</a>
###### 　　<a href="mdbook/4.1.md#3-拆分窗格-splitpane-" target="_blank">3）拆分窗格（SplitPane）</a>
###### 　　<a href="mdbook/4.1.md#4-垂直组合-verticalgroup-和水平组合-horizontalgroup-" target="_blank">4）垂直组合（VerticalGroup）和水平组合（HorizontalGroup）</a>
###### 　　<a href="mdbook/4.1.md#5-容器-container-" target="_blank">5）容器（Container）</a>
###### 　　<a href="mdbook/4.1.md#6-堆-stack-" target="_blank">6）堆（Stack）</a>
#### 　<a href="mdbook/4.1.md#3-复合控件-表格-table-" target="_blank">3.复合控件/表格（Table）</a>
###### 　　<a href="mdbook/4.1.md#1-窗体-window-" target="_blank">1）窗体（Window）</a>
###### 　　<a href="mdbook/4.1.md#2-按钮-button-" target="_blank">2）按钮（Button）</a>
###### 　　<a href="mdbook/4.1.md#3-弹窗-dialog-" target="_blank">3）弹窗（Dialog）</a>
###### 　　<a href="mdbook/4.1.md#4-图文按钮-imagetextbutton-" target="_blank">4）图文按钮（ImageTextButton）</a>
###### 　　<a href="mdbook/4.1.md#5-文本按钮-textbutton-" target="_blank">5）文本按钮（TextButton）</a>
###### 　　<a href="mdbook/4.1.md#6-复选框-checkbox-" target="_blank">6）复选框（CheckBox）</a>
###### 　　<a href="mdbook/4.1.md#7-图片按钮-imagebutton-" target="_blank">7）图片按钮（ImageButton）</a>

<br/>
<br/>

## 五.资源管理
#### 　<a href="mdbook/5.1.md#1-资源管理器-assetmanager-" target="_blank">1.资源管理器（AssetManager）</a>
#### 　<a href="mdbook/5.1.md#2-文件的操作-filehandle-" target="_blank">2.文件的操作（FileHandle）</a>
#### 　<a href="mdbook/5.1.md#3-k-v存储-preferences-" target="_blank">3.K-V存储（Preferences）</a>
#### 　<a href="mdbook/5.1.md#4-网络-net-" target="_blank">4.网络（Net）</a>
###### 　　<a href="mdbook/5.1.md#1-get请求" target="_blank">1）get请求</a>
###### 　　<a href="mdbook/5.1.md#2-post请求" target="_blank">2）post请求</a>

<br/>
<br/>

## 六.高级
#### 　<a href="mdbook/6.1.md#1-2d相机-orthographiccamera-" target="_blank">1. 2D相机（OrthographicCamera）</a>
#### 　<a href="mdbook/6.1.md#2-2d粒子系统" target="_blank">2. 2D粒子系统</a>

<br/>
<br/>

## 七.声音：音乐（Music）和音效（Sound）
#### 　<a href="mdbook/7.1.md" target="_blank">音乐（Music）和音效（Sound）</a>

<br/>
<br/>

## 八.工具

<br/>
<br/>

## 九.文献参考




















<br/>
<hr/>
<hr/>
<br/>
v0.01<br/>
崔维友<br/>
2017.07<br/>
[www.cuiweiyou.com](http://www.cuiweiyou.com)<br/>
<br/>
![微信号](weixin.png)<br/>
<br/>
