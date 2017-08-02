2017-07-19 11:34发布于 h t t p : / / git.oschina.net/vigiles/LibGDX2DGameGuideNorth
<br/>
<br/>

# LibGDX2D游戏开发指北
<br/>

 ![libgdxGuideNorth](https://github.com/731942771/LibGDX2DGameGuideNorth/blob/master/badlogic.jpg)
 
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
#### 　<a href="mdbook/1.1.md#1项目创建器" target="_blank">1.项目创建器</a>
#### 　<a href="mdbook/1.1.md#2设置资源仓库" target="_blank">2.设置资源仓库</a>
#### 　<a href="mdbook/1.1.md#3选择android后生成" target="_blank">3.选择“Android”后生成</a>
#### 　<a href="mdbook/1.1.md#4as中编译应用" target="_blank">4.AS中编译应用</a>

<br/>
<br/>

## <a href="mdbook/2.1.md" target="_blank">二.代码</a>
#### 　<a href="mdbook/2.1.md#1androidlauncher" target="_blank">1.AndroidLauncher</a>
#### 　<a href="mdbook/2.1.md#2androidapplicationconfiguration " target="_blank">2.AndroidApplicationConfiguration</a>
#### 　<a href="mdbook/2.1.md#3mygdxgame" target="_blank">3.MyGdxGame</a>
#### 　<a href="mdbook/2.1.md#4生命周期" target="_blank">4.生命周期</a>

<br/>
<br/>

## 三.2D世界
#### 　<a href="mdbook/3.1.md#1可视元素" target="_blank">1.可视元素</a>
###### 　　<a href="mdbook/3.1.md#1纹理texture" target="_blank">1）纹理（Texture）</a>
###### 　　<a href="mdbook/3.1.md#2区域纹理textureRegion" target="_blank">2）区域纹理（TextureRegion）</a>
###### 　　<a href="mdbook/3.1.md#3映射图pixmap" target="_blank">3）映射图（Pixmap）</a>
###### 　　<a href="mdbook/3.1.md#4精灵sprite" target="_blank">4）精灵（Sprite）</a>
###### 　　<a href="mdbook/3.1.md#5动画animation" target="_blank">5）动画（Animation）</a>
###### 　　<a href="mdbook/3.1.md#6精灵脚本纹理画布spritebatch" target="_blank">6）精灵脚本/纹理画布（SpriteBatch）</a>
#### 　<a href="mdbook/3.1.md#2演员actor" target="_blank">2.演员Actor</a>
#### 　<a href="mdbook/3.1.md#3导演舞台stage" target="_blank">3.导演/舞台Stage</a>
###### 　　<a href="mdbook/3.1.md#1演员和舞台的事件" target="_blank">1）演员和舞台的事件</a>
###### 　　<a href="mdbook/3.1.md#2演员的动作action" target="_blank">2）演员的动作（Action）</a>
###### 　　<a href="mdbook/3.1.md#3执行导演经纪人group" target="_blank">3）执行导演/经纪人（Group）</a>
###### 　　<a href="mdbook/3.1.md#4视窗viewport" target="_blank">4）视窗（Viewport）</a>
#### 　<a href="mdbook/3.1.md#4幕场景screen" target="_blank">4.幕/场景Screen</a>
###### 　　<a href="mdbook/3.1.md#1启动页" target="_blank">1）启动页</a>
###### 　　<a href="mdbook/3.1.md#2关卡1" target="_blank">2）关卡1</a>
###### 　　<a href="mdbook/3.1.md#3游戏总控" target="_blank">3）游戏总控</a>
###### 　　<a href="mdbook/3.1.md#4生命周期日志" target="_blank">4）生命周期日志</a>
#### 　<a href="mdbook/3.1.md#5游戏game" target="_blank">5.游戏Game</a>

<br/>
<br/>

## 四.控件Widget
#### 　<a href="mdbook/4.1.md#1个体控件widget" target="_blank">1.个体控件（Widget）</a>
###### 　　<a href="mdbook/4.1.md#1图片image" target="_blank">1）图片（Image）</a>
###### 　　<a href="mdbook/4.1.md#2标签label" target="_blank">2）标签（Label）</a>
###### 　　<a href="mdbook/4.1.md#3文本框textfield" target="_blank">3）文本框（TextField）</a>
###### 　　<a href="mdbook/4.1.md#4文本域textarea" target="_blank">4）文本域（TextArea）</a>
###### 　　<a href="mdbook/4.1.md#5列表list" target="_blank">5）列表（List）</a>
###### 　　<a href="mdbook/4.1.md#6进度条progressbar和滑动条slider" target="_blank">6）进度条（ProgressBar）和滑动条（Slider）</a>
###### 　　<a href="mdbook/4.1.md#7下拉列表selectbox" target="_blank">7）下拉列表（SelectBox）</a>
###### 　　<a href="mdbook/4.1.md#8虚拟摇杆touchpad" target="_blank">8）虚拟摇杆（Touchpad）</a>
#### 　<a href="mdbook/4.1.md#2群体控件widgetgroup" target="_blank">2.群体控件（WidgetGroup）</a>
###### 　　<a href="mdbook/4.1.md#1滚动窗格scrollpane" target="_blank">1）滚动窗格（ScrollPane）</a>
###### 　　<a href="mdbook/4.1.md#2树tree" target="_blank">2）树（Tree）</a>
###### 　　<a href="mdbook/4.1.md#3拆分窗格splitpane" target="_blank">3）拆分窗格（SplitPane）</a>
###### 　　<a href="mdbook/4.1.md#4垂直组合verticalgroup和水平组合horizontalgroup" target="_blank">4）垂直组合（VerticalGroup）和水平组合（HorizontalGroup）</a>
###### 　　<a href="mdbook/4.1.md#5容器container" target="_blank">5）容器（Container）</a>
###### 　　<a href="mdbook/4.1.md#6堆stack" target="_blank">6）堆（Stack）</a>
#### 　<a href="mdbook/4.1.md#3复合控件表格table" target="_blank">3.复合控件/表格（Table）</a>
###### 　　<a href="mdbook/4.1.md#1窗体window" target="_blank">1）窗体（Window）</a>
###### 　　<a href="mdbook/4.1.md#2按钮button" target="_blank">2）按钮（Button）</a>
###### 　　<a href="mdbook/4.1.md#3弹窗dialog" target="_blank">3）弹窗（Dialog）</a>
###### 　　<a href="mdbook/4.1.md#4图文按钮imagetextbutton" target="_blank">4）图文按钮（ImageTextButton）</a>
###### 　　<a href="mdbook/4.1.md#5文本按钮textbutton" target="_blank">5）文本按钮（TextButton）</a>
###### 　　<a href="mdbook/4.1.md#6复选框checkbox" target="_blank">6）复选框（CheckBox）</a>
###### 　　<a href="mdbook/4.1.md#7图片按钮imagebutton" target="_blank">7）图片按钮（ImageButton）</a>

<br/>
<br/>

## 五.资源管理
#### 　<a href="mdbook/5.1.md#1资源管理器assetmanager" target="_blank">1.资源管理器（AssetManager）</a>
#### 　<a href="mdbook/5.1.md#2文件的操作filehandle" target="_blank">2.文件的操作（FileHandle）</a>
#### 　<a href="mdbook/5.1.md#3kv存储preferences" target="_blank">3.K-V存储（Preferences）</a>
#### 　<a href="mdbook/5.1.md#4网络net" target="_blank">4.网络（Net）</a>
###### 　　<a href="mdbook/5.1.md#1get请求" target="_blank">1）get请求</a>
###### 　　<a href="mdbook/5.1.md#2post请求" target="_blank">2）post请求</a>

<br/>
<br/>

## 六.高级
#### 　<a href="mdbook/6.1.md#12d相机orthographiccamera" target="_blank">1. 2D相机（OrthographicCamera）</a>
#### 　<a href="mdbook/6.1.md#22d粒子系统" target="_blank">2. 2D粒子系统</a>

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

 [威格灵博客](http://www.cuiweiyou.com "http://www.cuiweiyou.com")  
 
<br/> 

 ![libgdxGuideNorth](https://github.com/731942771/LibGDX2DGameGuideNorth/blob/master/weixin.png)
 
<br/>
