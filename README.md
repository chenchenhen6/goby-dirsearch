# 更新日志：新增dirsearch自定义参数用法

例如：过滤目录扫描404,301状态码，调节线程为10，可将dirsearch自定义参数设置为 -x 404,301 -t 10,更多用法请通过github项目地址查看使用文档
<img width="799" alt="图片" src="https://user-images.githubusercontent.com/35289748/118425639-2e50e780-b6fc-11eb-8e66-55016ae69186.png">




# 1、快速开始

通过git下载最新项目
git clone https://github.com/maurosoria/dirsearch.git

安装依赖
pip3 install -r requirements.txt
# 2、设置并使用插件
设置dirsearch.py路径，即可在ip详情页与webfinder使用dirsearch

![dir1](https://user-images.githubusercontent.com/35289748/116570891-2f80c700-a93d-11eb-8d0e-c7169a983a4a.gif)

注意:默认值为python3，Windows下请确认cmd窗口输入python，能调用python3，或者设置成可以调用python3的命令。

<img width="980" alt="图片" src="https://user-images.githubusercontent.com/35289748/116520801-c598fb00-a905-11eb-87a7-1caef9c1bdfa.png">

# 3、可能遇到的问题

由于github项目作者更新导致参数有变化，插件更新将直接支持新参数，遇到dirsearch.py: error: no such option: --format 报错，请重新通过git下载最新版本

# 4、致谢
感谢叶落凡尘表哥和go0p表哥在插件开发过程中给予的耐心指导。后续会将插件逐渐完善，如遇到问题也欢迎反馈，我会尽力去解决。

