# uScan
## 工具介绍
uScan是一款采用Yak语言编写的脚本，用来探测网站的状态，返回网站状态码和title信息，帮助使用者快速从大量URL中定位合适的目标，从而提高挖掘src的效率。
## 免责声明
本工具仅能在取得足够合法授权的企业安全建设中使用，在使用本工具过程中，您应确保自己所有行为符合当地的法律法规。 如您在使用本工具的过程中存在任何非法行为，您将自行承担所有后果，本工具的开发者不承担任何法律及连带责任。 除非您已充分阅读、完全理解并接受本协议所有条款，否则，请您不要下载并使用本工具。 您的使用行为或者您以其他任何明示或者默示方式表示接受本协议的，即视为您已阅读并同意本协议的约束。
## 环境需求
本工具采用为网络安全而生的领域编程语言——Yak，所以需要配置yak语言环境，配置参考Yak官网：https://www.yaklang.com/
## 工具使用
工具目前功能很简单，仅有-u和-f两个参数，探测的目标不包含“http://”或“https://”，使用-h查看使用文档：  
`yak uScan.yak -h`
![image](https://github.com/SoDa-LJ/uScan/assets/59957157/d8e50b1d-f9d5-4f4d-ace6-e8e8956a68bb)  
使用-u参数对单个url进行探测：  
`yak uScan.yak -u xxx.com`
![image](https://github.com/SoDa-LJ/uScan/assets/59957157/52f941c4-dcd9-4cc7-8cfa-d850224b05a2)  
使用-f参数对txt中的url进行批量探测：  
`yak uScan.yak -f xxx.txt`
![image](https://github.com/SoDa-LJ/uScan/assets/59957157/8474541c-6258-49f4-b256-d8ae2781b56d)  
