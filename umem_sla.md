{{indexmenu_n>15}}

# 云内存存储 UMem 服务等级协议（SLA）

UCloud UMem服务等级协议（以下简称“本协议”）规定了UCloud向客户提供UCloud
UMem云内存存储服务的一般性服务等级指标和服务注意事项。本协议是《UCloud用户协议》、《云服务法律声明及隐私条款》的补充。您通过盖章、网络页面点击确认或以其他方式（如点击确认同意用《UCloud用户协议》）选择接受本协议，即表示您与本公司已达成协议并同意接受本协议的全部约定内容。如若双方盖章文本与网络页面点击确认或以其他方式选择接受之服务条款文本，存有不一致之处，以双方盖章文本为准。在接受本协议之前，请您仔细阅读本协议的全部内容。您阅读后，如果继续使用UMem服务，即表示您接受本协议并同意受其约束；如果您不同意本协议，您可以选择不使用UMem服务。

## 1、数据存储的持久性

1.1 UMem云内存存储数据存储的持久性为99.9999％。

1.2
数据存储的持久性定义：合同期内数据保持存储状态不丢失的概率。持久性为99.9999％意指合同期内用户每月1000000字节的数据，合同期内每月数据不丢失的概率为99.9999%，即每月只有1字节的数据丢失的可能性。以自然月为统计周期，不满一个月按一个月计。

1.3 此类数据主要是指用户存储在其使用的硬盘介质内的数据，不包括内存中的数据。

## 2、数据可销毁性

2.1 在您要求删除数据或设备在弃置、转售前，UCloud将通过高级清零操作彻底删除用户所有数据且无法复原，并对报废硬盘做消磁处理。

2.2
用户数据彻底删除的场景不包括在取得UCloud同意后，UCloud为未及时续费用户的数据保留7天的情形，以防止用户由于某些原因无法及时续费导致重要数据被删除。

## 3、数据可迁移性

3.1 本公司承诺用户能够控制云内存存储中数据的迁移，保证启用或弃用该云服务时，数据能迁入和迁出。

3.2 本公司在用户迁入迁出时提供相应的工具和技术手段，与用户现有的数据格式保持最大的兼容性。具体导入导出操作步骤请参见帮助说明。

## 4、数据私密性

4.1 UCloud采用了有效的隔离方法，保证同一资源池用户数据互不可见。

4.2 云内存存储根据帐号进行隔离，通过网络隔离的技术保证不同用户间的主机和数据互不可见，无法通过内网访问。

4.3
在未经用户授权的情况下，UCloud承诺不会查看用户实例内的任何程序、配置、数据文件等。但是UCloud有权从云内存存储外部监控用户的实例的运行数据，包括CPU使用、内存使用等。为了便于运维和问题排查，UCloud保留查看云内存存储用户操作记录的权利。

4.4 在未经用户授权或非政府机构要求下，UCloud不会查看用户数据。运维人员相关操作会进行详细的记录，有日志进行查询。

## 5、数据知情权

5.1 您可在产品控制台看到云内存存储所在的地域及可用区名称，您可选择您所需要的地域及可用区。例如：北京二可用区B位于北京市。

5.2
热备类型（主备版、分布式版）的云内存存储的数据会在云内存存储所在的数据中心有两份拷贝，无冷备份，在其他数据中心无备份；无热备类型（单机版）的云内存存储数据无拷贝，无备份。

5.3 所有数据中心应遵守当地法律和中华人民共和国法律。

5.4
除政府监管部门监管审计需要或配合安全取证调查外，未经客户同意，不能将用户数据非法提供给任何第三方。为了保障您使用本服务的安全性以及不断改进服务质量的需要，本公司将记录并保存您登录和使用本服务的相关行为日志，不会对外呈现用户个人信息数据。

## 6、 业务可审查性

6.1
根据国家的法律法规要求，为配合政府监管部门的监管审查，合规或取证调查等，本公司可提供您运行在云服务上业务的相关的信息，如关键组件的运行日志、运维人员的操作记录。

## 7、业务功能

7.1 UCloud
UMem提供给用户的服务功能为www.ucloud.cn网站所展示的云内存存储服务，完整的功能介绍和操作说明详见产品使用手册和帮助说明。

7.2 UCloud若更换服务的版本或功能会及时通过短信、邮件或网站等方式通知您，以便您能及时做出相应的调整。

## 8、业务可用性

8.1 本公司向您承诺UMem云内存存储的服务可用性为99.99％。如果服务可用性没有达到承诺，将按照服务赔偿条款进行赔付。

8.2
服务可用性定义：合同期内用户每月云服务业务可用时间的概率，即每月实际可用时间／每月（实际可用时间＋不可用时间）。其中不可用时间的定义为从用户无法使用云服务起至云服务恢复正常水平结束，以自然月为统计周期，不满一个月按一个月计，以分钟为单位。可用性为99.99％指单个用户每月云服务业务可用时间应至少为30天\\\*24小时\\\*60分钟\\\*99.99%=
43195.7分钟，即每月最多存在30天\\\*24小时\\\*60分钟\\\*100%-
43195.7=4.3分钟的不可用时间。云服务业务不可用的统计单元为单台云内存存储实例，云服务业务不可用时间达到1分钟以上算作一次不可用，计入不可用时间，不可用时间若低于1分钟则不计入不可用时间。

## 9、业务资源调配能力

9.1 UMem实例支持在线升级扩展，单位为GB，具体资源范围和资费详见订单页面展示；

9.2
缓存实例数量可扩展和缩减，单位为台数，可在24小时内完成总资源20％的扩展，2天内完成总资源100%的扩展；每次最大可扩展100％容量，最小无限制。

## 10、故障恢复能力

10.1 通过故障监控、快速定位、自动化恢复、告知等一系列故障管控体系，保证云服务的故障恢复能力。

## 11、云内存存储性能指标

11.1 您可购买的单台UMem实例支持1GB\~5000GB。

11.2 用户可以得到4000QPS/GB的查询能力。

## 12、UCloud 免责条款

因以下原因导致的服务不可用，UCloud不承担任何责任：

12.1 UCloud预先通知客户后进行系统维护所引起的，包括割接、维修、升级和模拟故障演练；

12.2 任何UCloud所属设备以外的网络、设备故障或配置调整引起的；

12.3 客户的应用程序受到黑客攻击而引起的；

12.4 客户维护不当或保密不当致使数据、口令、密码等丢失或泄漏所引起的；

12.5 客户的疏忽或由客户授权的操作所引起的；

12.6 客户未遵循UCloud产品使用文档或使用建议引起的；

12.7 由于客户违反《UCloud用户协议》导致的服务被暂停或终止，包括由于欠费导致云内存存储被暂停服务或被释放等；

12.8
其他不可抗力因素引起的。不可抗力以及意外事件是指由于信息网络正常的设备维护，信息网络连接故障，电脑、通讯或其他系统的故障，电力故障，战争，天灾，政府行为等一切不能预见、不可避免、不能克服的自然、社会现象客观情况。