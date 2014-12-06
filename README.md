android_gradle_script
=====================

android批量打包脚本，持续适配最新Android studio版本

使用方法：
1. 创建channel.txt，在其中输入渠道号名称以及渠道的数字，规则参考示例，当然也可以自己修改脚本替换其中manifest中不同的字段
2. 添加signing.properties文件，配置进行签名使用的参数，脚本会从这个文件中读取签名使用需要使用的参数
3. 添加proguard-rules.txt文件，添加自己的混淆规则
