## CMCC Technical Specifications

> CMCC 是 Chinese Minecraft Community Commons 的缩写  
> （不是 China Mobile Communications Company）

> cmcc-specs 的非正式英文全名是 Chinese Minecraft Community Commons (Technical Specification Branch)  
> cmcc-specs 的非正式中文名称是 中文 Minecraft 社区技术规范

本组织的创立目的是收集并整理中文 Minecraft 社区已经广泛使用中的事实标准，并编制索引。

---
### 已确认的事实标准：

同一个归口单位使用同样的代号前缀。

#### BMCLAPI（BMCLAPI 和原 MCBBS 镜像源）
BMCLAPI 是一个镜像服务，分发绝大多数 Minecraft 热点资源。
- [BMCLAPI-1](https://bmclapidoc.bangbang93.com/)  BMCLAPI 请求和响应格式

#### Authlib-Injector（外置登录）
Authlib-Injector 是最流行的外置登录注入工具，维护了一套用于自定义 Yggdrasil 服务端和相应启动器的技术规范。
- [AUTHINJ-S](https://github.com/yushijinhun/authlib-injector)  一组基于Authlib-Injector的外置登录实现方案
  - [AUTHINJ-S-1](https://github.com/yushijinhun/authlib-injector/wiki/Yggdrasil-%E6%9C%8D%E5%8A%A1%E7%AB%AF%E6%8A%80%E6%9C%AF%E8%A7%84%E8%8C%83)  Authlib-Injector 兼容的 Yggdrasil 服务端技术规范
  - [AUTHINJ-S-2](https://github.com/yushijinhun/authlib-injector/wiki/%E5%90%AF%E5%8A%A8%E5%99%A8%E6%8A%80%E6%9C%AF%E8%A7%84%E8%8C%83)  Authlib-Injector 兼容的启动器技术规范
- [AUTHINJ-24](https://github.com/yushijinhun/authlib-injector/issues/24)  AUTHINJ-S 的扩展：启动器公告
- [AUTHINJ-110](https://github.com/yushijinhun/authlib-injector/issues/110)  AUTHINJ-S 的扩展：验证服务器图标
- [AUTHINJ-136](https://github.com/yushijinhun/authlib-injector/issues/136)  [WIP]AUTHINJ-S-2 的修订：预读元数据从命令行参数变更为临时文件
- [AUTHINJ-163](https://github.com/yushijinhun/authlib-injector/issues/163)  [WIP]AUTHINJ-S 的修订：将登录流程移动到启动器外部

#### MCLF（中国MC启动器联盟）
MCLF 发布的规范主要关注启动器需要标准化的实现，主要中文启动器作者均参与。
- [MCLF-1](https://github.com/MCLF-CN/docs/issues/1)  Authlib-Injector 兼容的 Yggdrasil 服务端的公告扩展
- [MCLF-2](https://github.com/MCLF-CN/docs/issues/2)  BMCLAPI 客户端 UA 字符串
- [MCLF-5](https://github.com/MCLF-CN/docs/issues/5)  公共依赖项
- [MCLF-6](https://github.com/MCLF-CN/docs/issues/6)  OptiFine 兼容性警告
- [MCLF-7](https://github.com/MCLF-CN/docs/issues/7)  默认的离线 UUID
- [MCLF-14](https://github.com/MCLF-CN/docs/issues/14) / [MCLF-19](https://github.com/MCLF-CN/docs/pull/19) MCBBS 整合包格式
- [MCLF-20](https://github.com/MCLF-CN/docs/issues/20) 联机客户端之间的数据交换协议 

#### PCL（PCL 启动器）
PCL 较少参与初期阶段的标准化进程。其在封装协议时一般考虑其在编程上是否是最简洁，无心智负担而容易实现的。
- [PCL-W-2](https://github.com/Meloong-Git/PCL/wiki/%E7%AE%80%E6%B4%81%E8%81%94%E6%9C%BA%E6%A0%87%E8%AE%B0%E7%BA%A6%E5%AE%9A) 简洁联机标记约定（Pure Connect Labeling）

#### CurseForge、Modrinth、MultiMC
分别定义了一组整合包格式。后续将补全。

#### MCIM（模组镜像源）
MCIM 是一个镜像服务，缓存并分发来自 CurseForge 和 Modrinth 的热门模组信息
- [MCIM-1](https://mod.mcimirror.top/docs)  MCIM 请求和响应格式

#### Open93AtHome
尚未提供明文规范
