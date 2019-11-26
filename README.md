![CLEVER DATA GIT REPO](https://raw.githubusercontent.com/LiCongMingDeShujuku/git-resources/master/0-clever-data-github.png "李聪明的数据库")

# SQL Server连接SQL 2005失败
#### SQL Server Connection Failure SQL 2005
**发布-日期: 2005年10月03日 (评论)**

![#](images/##############?raw=true "#")

## Contents

- [中文](#中文)
- [English](#English)
- [Build Info](#Build-Info)
- [Author](#Author)
- [License](#License) 


## 中文
我们将使用以下内容来纠正此握手问题。

SQL Server配置管理器：

转到“SQL Server 2005网络配置”，然后查找“SQL2005协议”，
并确保启用TCPIP。

现在检查“Native SQL Client Configuration”，然后查找“Client Protocols”
并再次确保启用TCPIP。

下一步

SQL表面区域配置管理器：

单击“服务和连接的表面区域配置”和“远程连接”，确保使用“TCPIP”启用“本地和远程连接”。

现在重启你的服务器，应该可以了。

如果没有，请发布下一条错误消息。

## English
we’ll be working with the following to correct this handshake issue.

SQL Server Configuration Manager:

Start – Programs – SQL Server 2005 – SQL Server Configuration Manager

go to ‘SQL Server 2005 Network Configuration’, and look for ‘Protocols for SQL2005’,
and make sure TCPIP is enabled.

now check the ‘Native SQL Client Configuration’, and look for ‘Client Protocols’
and again make sure TCPIP is enabled.

next…

SQL Surface Area Configuration Manager:

Start – Programs – SQL Server 2005 – Configuration Tools – SQL Server Surface Area Configuration Manager
click on ‘Surface Area Configuration for Services and Connections’ and under ‘Remote Connections’ make
sure to enable ‘Local and Remote Connections’ using ‘TCPIP’

now restart your service and that should work.

if not please post the next error message.


[![WorksEveryTime](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](https://shitday.de/)

## Build-Info

| Build Quality | Build History |
|--|--|
|<table><tr><td>[![Build-Status](https://ci.appveyor.com/api/projects/status/pjxh5g91jpbh7t84?svg?style=flat-square)](#)</td></tr><tr><td>[![Coverage](https://coveralls.io/repos/github/tygerbytes/ResourceFitness/badge.svg?style=flat-square)](#)</td></tr><tr><td>[![Nuget](https://img.shields.io/nuget/v/TW.Resfit.Core.svg?style=flat-square)](#)</td></tr></table>|<table><tr><td>[![Build history](https://buildstats.info/appveyor/chart/tygerbytes/resourcefitness)](#)</td></tr></table>|

## Author

- **李聪明的数据库 Lee's Clever Data**
- **Mike的数据库宝典 Mikes Database Collection**
- **李聪明的数据库** "Lee Songming"

[![Gist](https://img.shields.io/badge/Gist-李聪明的数据库-<COLOR>.svg)](https://gist.github.com/congmingshuju)
[![Twitter](https://img.shields.io/badge/Twitter-mike的数据库宝典-<COLOR>.svg)](https://twitter.com/mikesdatawork?lang=en)
[![Wordpress](https://img.shields.io/badge/Wordpress-mike的数据库宝典-<COLOR>.svg)](https://mikesdatawork.wordpress.com/)

---
## License
[![LicenseCCSA](https://img.shields.io/badge/License-CreativeCommonsSA-<COLOR>.svg)](https://creativecommons.org/share-your-work/licensing-types-examples/)

![Lee Songming](https://raw.githubusercontent.com/LiCongMingDeShujuku/git-resources/master/1-clever-data-github.png "李聪明的数据库")

