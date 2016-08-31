原仓库地址https://github.com/keaijohnee/OpenMDMServer.git

这个项目将其依赖改为maven管理并更新了部分比较老的语法和不规范的定义

MDM介绍

MDM的全称是Mobile Device Management，顾名思义是移动设备管理，帮助企业将IT管理能力从传统的 PC 延伸到移动设备甚至移动应用APP 。

准备工作

需要一个企业级开发者账户($299),并且开通了mdm功能(需要提交苹果申请才能开通此功能)


MDM能够做些什么？

配置

信息查询

管理

配置

账户配置(wifi、vpn、email等）

密码策略(密码复杂度等配置）

安全与隐私（是否允许发送诊断数据到Apple等）

设备功能限制（是否允许摄像头，是否允许siri）

应用限制（是否允许用iTunesstore，Safari等）

云（是否允许云备份、照片流等）


内容分级


信息查询

基本信息（UDID、设备名、imei等）

网络信息（iccid、蓝牙和wifi的mac、手机号等）

合规性和安全性(安装的profile、是否有密码保护等）

应用（已安装应用id、已安装应用名称等）


管理

管理配置（安装和删除一个profile）

管理Apps（安装和删除一个in-houseApp）

擦除设备、清除密码、锁屏


基于Java（SpringMVC＋Hibernate ＋MySQL）的iOS移动设备管理（MDM）。

一、OpenMDMServer代码实现了如下功能：

1、自动创建基于设备的mobileconfig描述文件，安装时执行CheckIn和ServerURL自动设备注册；

2、获取设备信息；

3、获取设备APP信息；

4、安装和卸载APP；

5、设备锁屏和清除密码；

6、抹去设备数据；

7、获取设备描述文件、预置描述文件、证书文件；

三、演示站及技术支持：

1、演示站：http://etest.hulai.com/OpenMdmServer/ 注意：请用邮箱注册并生成账号和mobileconfig描述文件

2、GitHub开源地址：https://github.com/keaijohnee/OpenMDMServer

3、OSChina开源地址：http://git.oschina.net/jianggege/OpenMDMServer

4、技术参考：基于IOS上MDM技术相关资料整理及汇总:http://www.mbaike.net/mdm/6.html

5、MDM咨询QQ：459104018 ，QQ群：205891305
