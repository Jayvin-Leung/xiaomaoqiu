# 小毛球——森之国度生活助手

【一、免责声明】

1、该脚本仅为作者本人学习，测试使用

2、凡以任何方式使用该脚本而产生的一切账号问题，作者概不负责

3、凡以任何方式使用该脚本者，均被视为自愿接受该声明


【二、使用说明】

1、“按键精灵手机助手”本地调试

(1)、本地安装“按键精灵手机助手”

(2)、手机或模拟器上安装“按键精灵安卓版”

(3)、打开“按键精灵手机助手”并导入此脚本，同时将“lib”下的命令库文件复制到“按键精灵手机助手”安装目录下的“CommandLib”文件夹中

(4)、将“按键精灵手机助手”连接上需调试的手机或模拟器，点击调试即可

2、打包成APP后在手机或模拟器上直接运行

(1)、本地安装“按键精灵手机助手”

(2)、打开“按键精灵手机助手”并导入此脚本，同时将“lib”下的命令库文件复制到“按键精灵手机助手”安装目录下的“CommandLib”文件夹中

(3)、执行打包，方式多样，自行探索

(4)、将打包出来的APP导入手机或模拟器，正常安装使用即可


【三、模拟器设置】

1、推荐使用“MuMu模拟器”，以下设置均以该模拟器为准，其他模拟器自行摸索

2、分辨率选择“1600 * 900”

3、开启手机ROOT权限


【四、游戏设置】

1、关闭“点击地面移动”

2、关闭“自动锁定屏幕”

3、关闭“开关天气效果”

4、同屏人数设置为“1人”

5、家园耕地布置参考下图1，其中第一块基准耕地坐标：“91,69”（重要，请严格执行）

6、家园作物，一键种植数量调至60，参考下图2、3

7、创建队伍，保持1人即可
![图1](https://github.com/Jayvin-Leung/xiaomaoqiu/icon/pic/图1.png)
![图2](https://github.com/Jayvin-Leung/xiaomaoqiu/assets/118683529/8fc4c121-de09-4ff7-9e77-402f7719d791)
![图3](https://github.com/Jayvin-Leung/xiaomaoqiu/assets/118683529/6a367b95-8531-4b21-b790-dc4ad6c4bdbe)


五、脚本设置

1、“按键精灵手机助手”本地调试

(1)、“按键精灵手机助手” - “界面” - “竖屏预览”，根据提示完成设置，保存设置

(2)、点击调试，在出现的悬浮窗中选择需要的操作，点击继续即可开始脚本

2、手机或模拟器上运行APP

(1)、打开APP，根据提示完成设置

(2)、点击“启动浮窗”，如果第一次启动，需根据提示进入应用设置，打开“允许显示在其他应用的上层”，即“允许开启悬浮窗”

(3)、点击悬浮的蚂蚁图标，点击开启，然后选择需要的操作，点击继续即可开始脚本


六、高级进阶用法

1、目前该脚本仅支持：
    
a、采集“Ⅴ级”及以下材料
    
b、“18级”及以下工匠手艺
    
c、“13级”及以下炼金师手艺
    
d、“13级”及以下料理师手艺

2、如需获取更高级支持，请等待下一版本更新，具体时间不确定

3、故建议自行添加对应数据以获取更高级支持

(1)、更新“数据库”信息，其中“com.jl.xiaomaoqiu” - “data” - “db”下存放数据信息
    
a、打开“db”，获取该目录下的四个Excel文件
    
b、编辑对应的Excel文件，将编辑好的Excel文件转换为json文件（提供一个在线转换工具：https://wejson.cn/excel2json/）
    
c、将新转换出来的json文件覆盖“db”目录下对应名称的旧json文件即可

(2)、添加匹配图片，其中“com.jl.xiaomaoqiu” - “data” - “pic”下存放匹配时所需的图片
    
a、根据“pic”目录下原有的图片，按照原有图片的方式进行图片截取和图片命名
    
b、将新的制作好的图片放入“pic”目录下即可

(3)、因受字数限制，详细的操作方法请移步查看：（需科学上网）
