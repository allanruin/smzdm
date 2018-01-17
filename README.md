# 什么值得买 每日签到奖励 #
此脚本用于 [什么值得买](http://www.smzdm.com/) 网站的每日签到.

# 如何使用? #
脚本语言是`Python`, 所以首先你要[安装Python](https://www.python.org/downloads/)

然后脚本依赖于`requests`库, 所以你要[安装requests](http://www.python-requests.org/en/latest/user/install/)

都安装完成之后, 还需要修改脚本中的`SMZDM_USERNAME`(你的账号名)及`SMZDM_PASSWORD`(你的密码)变量

最后, 只需要添加`cron`定时任务即可!

# 关于项目
项目fork自 isaymeorg的代码，但作者不怎么维护，所以自己遇到问题修改后的版本跟原来有较大区别。不想在针对异常情况整理成exception类。就是个签到脚本，默认成功的时候静默不输出。失败或异常的时候才输出。这样方便用cron定时的时候再/var/mail里收到消息。


# 联系我 #
`email`: boxoxod # gmail
