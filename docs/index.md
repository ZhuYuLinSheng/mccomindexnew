---
layout: home
layoutClass: 'm-home-layout'

hero:
  name: MCCOM
  text: 服务器交流组织
  tagline: 一个致力于Minecraft技术交流和服务器宣传的组织</br>无论你是玩家还是服主，这里都是优秀的交流社区
  image:
    src: /logo.png
    alt: MCCOM组织
  actions:
    - text: 加入社区群组
      link: https://qm.qq.com/q/HjGlhKaM0k
    - theme: sponsor
      text: 社区MC导航
      link: /nav/
    - theme: sponsor
      text: 组织专栏
      link: /press/
    - theme: sponsor
      text: MCCOM开发者社区
      link: https://dev.mcflare.com

features:
  - title: 多平台
    details: 作为服务端插件 / 模组，OPanel支持多个主流服务端平台的多个Minecraft版本，包括Bukkit、Fabric、Forge和Neoforge。
    icon: 🌏
    link: /docs/versions
    linkText: 版本列表
  - title: 功能丰富
    details: 与服务端深度融合，支持功能包括存档管理、玩家管理、游戏规则编辑、后台终端、日志管理等等。
    icon: 🛠️
  - title: 社区活跃
    details: 项目组人员长期活跃，用户可以在Github与QQ群中提问或反馈，项目开发组将尽力解答和解决问题。
    icon: 🤗
    link: https://qm.qq.com/q/1t1VHv1eHa
    linkText: 加入QQ群
---


<style>
/*爱的魔力转圈圈*/
.m-home-layout .image-src:hover {
  transform: translate(-50%, -50%) rotate(666turn);
  transition: transform 40s 10s cubic-bezier(0.3, 0, 0.8, 1);
}

.m-home-layout .details small {
  opacity: 0.8;
}

.m-home-layout .bottom-small {
  display: block;
  margin-top: 2em;
  text-align: right;
}
</style>
