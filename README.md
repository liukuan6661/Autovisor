## Autovisor

智慧树视频课辅助脚本，开启挂机摸鱼时代~

### **程序介绍:**

​	这是一个可无人监督的自动化程序，由Python和JavaScript编写而成。相对于纯JS脚本，本程序可有效防止被网页检测。

​	核心原理是使浏览器模拟用户的点击操作。

**程序功能:**

- 可以自动登录
- **自动播放和切换下一集**
- **跳过弹窗和弹出的题目**
- 自动静音播放视频
- 检测当前学习进度并后台实时更新
- **检测视频是否暂停并续播** (再也不用担心视频意外暂停了~)
- 根据当前时间自动设置背景颜色(白昼/暗夜)

### 使用须知：
0. 请确保系统为windows，且具备安装在**系统默认位置**的Edge或Chrome；

​注：
- 默认启动Edge(win10以上系统会自带); 
- 如果**Edge和Chrome没有装在默认位置**，则程序会先自动下载，在此期间请耐心等待；

​1.文件夹内有**"account.json"**,请用文本编辑器打开;

2.填写配置文件 
- 前两项请输入你的 **用户名，密码**；
- 第三项指定启动的 **浏览器**；
- 第四项输入网课的 **具体网址**，保存后关闭，例如:

![image](https://github.com/CXRunfree/Autovisor/assets/79365257/4e367835-3aaf-4d7b-8231-721695d17f83)


​3.运行程序，会自动打开浏览器界面，滑块验证时请稍等片刻，进入网课界面后就可以自动刷课啦~ (~ ^-^ ~)

​	   注:登录界面的滑块验证请手动**拖动滑块验证**。

**常见问题 :** 

​	0.为什么下载的压缩包里找不到exe文件?
- 这里是源代码,如果希望直接使用请下载Releases版本

​1.为什么会出现一个黑框?  
![image](https://github.com/CXRunfree/Autovisor/assets/79365257/7e5356ce-8987-40da-bc31-c81cc54b3ad2)
- 这是程序运行的后台，你可以查看当前运行的状态

2.为什么网页还没加载出来程序就退出了? 
​- 可能是网速太慢，程序设计了超时关闭(大概80秒左右)
   
3.为什么运行程序只出现后台却没出现浏览器界面？
   - 只要后台未异常退出就不必担心，稍等一会即可

**不支持功能:**

- 由于习惯分机制对倍速检测严格, 程序不提供自动调节倍速功能

**已知Bug:**

- **长时间挂机**有概率弹出人机验证,会导致程序异常退出;
- 刷课页面若弹出智慧树**微信公众号**,会导致程序异常退出;
- 若出现其他异常崩溃，请提交issue并附上日志文件log.txt的信息；

如有其他疑问,可以提issue或者在CSDN给作者留言 (!^-^/)

**碎碎念:**

   觉得体验还不错? 来给开源项目发电支持一下吧~!

   <img src="https://github.com/CXRunfree/Autovisor/assets/79365257/3f72abfe-ce8f-4181-91fb-f321418ff60e" width="310px">




CSDN:Runfreeone

**注意：本程序遵守BSD许可证，建议仅用于学习和研究计算机原理。**
