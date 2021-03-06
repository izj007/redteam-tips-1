# redteam-tips
基于PTES框架的红队渗透测试

## 1.身份匿名
### 1.1 物理隔离
  - 1.1.1 虚拟机环境隔离 <br>
  测试阶段，使用单独的虚拟机环境进行渗透测试 <br>
  - 1.1.2 单独使用测试主机

### 1.2 网络代理
  - 1.2.1 socks代理
  - 1.2.2 http代理
  - 1.2.3 tor浏览器
  - 1.2.4 跳板机

### 1.3 个人信息脱敏
  - 1.3.1 虚拟网络身份
  - 1.3.2 社交信息脱敏

### 1.4 安全防护
  - 1.4.1 终端杀毒软件安装
  - 1.4.2 浏览器无痕模式
  - 1.4.3 不明文件云沙箱检测
  - 1.4.4 不明好友链接拒绝点击
  - 1.4.5 自查社工库已泄漏信息
    
### 1.5.流量特征去除
  - 1.5.1 nmap
  - 1.5.2 masscan
  - 1.5.3 sqlmap
  - 1.5.4 metasplit
  - 1.5.5 cobalt strike
  - 1.5.6 冰蝎
  - 1.5.7 菜刀
  - 1.5.8 哥斯拉
    
## 2.信息搜集
### 2.1 横向信息搜集
- #### 2.1.1 公司信息
  - 工商信息
  - 对外投资
  - 企业关系
  - 分支机构
  - 人员架构
  - 物理位置
  - 官方微博
  - 官方微信公众号

- #### 2.1.2 业务信息
  - 经营范围
  - 产品供应链

- #### 2.1.3 第三方厂商信息
  - 合作伙伴
  - 供应商

- #### 2.1.4 产品信息
  - Android平台
  - Ios平台
  - Windows应用
  - Mac应用
  - Pos机应用
  - 微信小程序应用

- #### 2.1.5 资产信息
  - 根域名信息
  - 子域名信息
  - ip信息
  - ip段信息
  - 网络拓扑
  - 运营商信息
  - 代码托管平台信息
  - 文件云存储平台信息
  - 社交网络平台信息

- #### 2.1.6 人员信息
  - 姓名
  - 年龄
  - 工号
  - 手机号
  - 身份证
  - ......

### 2.2 纵向信息搜集
- #### 2.2.1 web应用信息
  - 指纹信息
  - 版权信息
  - 站点路径
  - 图标信息
  - 接口信息
  - 功能模块
  
- #### 2.2.2 服务器端信息
  - 主机信息
  - ip信息
  - 端口信息
  - 服务信息
  - 中间件信息
  - 基础环境信息

## 3.漏洞验证
### 3.1 常规web漏洞
- #### 3.1.1 sql注入漏洞
  - 显注
  - 盲注
- #### 3.1.2 xss跨站脚本漏洞
  - 存储
  - 反射
  - dom
- #### 3.1.3 任意文件上传漏洞
- #### 3.1.4 任意文件包含漏洞
- #### 3.1.5 远程代码执行漏洞
- #### 3.1.6 远程命令执行漏洞
  - 有回显
  - 无回显
- #### 3.1.7 ssrf服务器端请求伪造漏洞
- #### 3.1.8 xxe外部实体注入漏洞
- #### 3.1.9 csrf跨站请求伪造漏洞
  - get类型
  - post类型
- #### 3.1.10 jsonp跨域漏洞
- #### 3.1.11 clickjacking点击劫持漏洞
- #### 3.1.12 越权漏洞
  - 平行越权
  - 水平越权
- #### 3.1.13 url跳转漏洞
  - 域内跳转
  - 域外跳转
- #### 3.1.14 条件竞争漏洞
- #### 3.1.15 敏感信息泄漏
- #### 3.1.16 弱口令
  
### 3.2 通用组件漏洞
- #### 3.2.1 web应用
  - thinkphp
  - 通达OA
  - coremail
  
- #### 3.2.2 中间件
  - jboss
  - zabbix
  - redis
  - fastjson
  - nexus
  - shiro
  - solr
  - spring
  - struts2
  - tomcat
  - weblogic
  - phpmyadmin

## 4.漏洞利用
### 4.1 常规web漏洞
- #### 4.1.1 sql注入漏洞getshell
  - mysql
  - oracle 
- #### 4.1.2 任意文件上传漏洞getshell
- #### 4.1.3 远程命令执行漏洞getshell
- #### 4.1.4 任意文件包含漏洞getshell
- #### 4.1.5 xss漏洞getshell


### 4.2 通用组件漏洞

## 5.内网渗透
## 6.权限维持
## 7.横向渗透
## 8.痕迹清理
### 8.1 日志
- #### 8.1.1 操作系统
- #### 8.1.2 web应用
- #### 8.1.3 数据库日志
- #### 8.1.4 ssh日志
- #### 8.1.5 rdp日志
### 8.2 后门
- #### 8.2.1 webshell后门
- #### 8.2.2 osshell后门
- #### 8.2.3 xss payload

## 9.溯源反制
### 9.1 诱饵的诱饵
