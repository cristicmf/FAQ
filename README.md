# hackathon
## 通关秘籍

 ### 系统要求

| 配置     | 最低配置          | 推荐配置                                                     |
| -------- | ----------------- | ------------------------------------------------------------ |
| CPU      | 2核 1.5GHz        | 4核 2.4GHz                                                   |
| 内存     | 2G                | 4GB                                                          |
| 带宽     | 1M                | 5M                                                           |
| Java     | Java(TM) 1.8      | 推荐`Oralce JDK`；<br />如果在`CentOS`中使用`Open JDK`，请先升级到`1.9` |
| 操作系统 | 能正常运行JVM即可 | 快速安装Bash脚本在以下环境测试通过：<br />`CentOS7.2`、`Ubuntu16.04`、`RedHat7.4`<br />`Java`服务在以下环境测试通过：<br />`CentOS7.2`、`Ubuntu16.04`、`RedHat7.4` |

### 文档

#### 2.单机部署区块链
- [操作手册](https://fisco-bcos-documentation.readthedocs.io/zh_CN/latest/docs/installation.html)

- [源码地址](https://github.com/FISCO-BCOS/FISCO-BCOS)

#### 3.区块链开发工具集
 - web3sdk
[操作文档](https://fisco-bcos-documentation.readthedocs.io/zh_CN/latest/docs/sdk/sdk.html)

[源码地址](https://github.com/FISCO-BCOS/web3sdk)

- 控制台console
[操作文档](https://fisco-bcos-documentation.readthedocs.io/zh_CN/latest/docs/installation.html#id7)

[源码]https://github.com/FISCO-BCOS/console

#### 4.区块链通用组件

- 展示工具: 
[区块链浏览器](https://github.com/FISCO-BCOS/fisco-bcos-browser)

- 上链组件：
[WeBASE](https://github.com/WeBankFinTech/WeBASE)

#### 5.应用场景案例
- 区块链存证示例
FISCO-BCOS区块链存证是聚焦于企业级应用服务的区块链技术平台，从电子数据的全生命周期介入，实现区块链存证、取证、维权、核证，让司法机构参与到业务过程中，实时见证，为后续的证据核实、纠纷解决、裁决送达提供了可信、可追溯、可证明的技术保障。适用场景：金融行业网络信贷、消费金融、理财等，重点解决可信和司法认可。

[案例说明](https://github.com/FISCO-BCOS/evidenceSample)

- WeIdentity(DID): 
WeIdentity是基于区块链实现的符合W3C DID和Verifiable Credential规范的分布式身份解决方案。

[源码地址](https://github.com/WeBankFinTech/WeIdentity)

- WeEvent(EDA): 
WeEvent是一套分布式事件驱动架构，实现了可信、可靠、高效的跨机构、跨平台事件通知机制。

[源码地址](https://github.com/WeBankFinTech/WeEvent)

#### 6.	更多材料

- FISCO BCOS技术文档

[文档地址](https://fisco-bcos-documentation.readthedocs.io/zh_CN/latest/)

- 智能合约开发介绍

[智能合约开发说明文档](https://fisco-bcos-documentation.readthedocs.io/zh_CN/latest/docs/manual/smart_contract.html)

[语法介绍](https://solidity.readthedocs.io/en/v0.4.25/solidity-by-example.html)


### 常见问题

1. Install  mysql-python
```
Installing collected packages: mysql-python
  Running setup.py install for mysql-python ... error
```
install
```
yum install python-devel mysql-devel zlib-devel openssl-devel
```

2. SDK使用
- [sample](https://github.com/FISCO-BCOS/evidenceSample)
- [参数说明和配置解释](https://fisco-bcos-documentation.readthedocs.io/zh_CN/latest/docs/sdk/sdk.html)

#### 部署合约
- 合约修改之后需要重新部署，取最新的address
