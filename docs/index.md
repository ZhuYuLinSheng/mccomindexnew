---
layout: home
layoutClass: 'm-home-layout'

hero:
  name: MCCOM
  text: Minecraft交流组织
  tagline: 一个致力于Minecraft所有方面的组织</br>无论你是玩家、服主还是开发者，这里都是优秀的交流社区<br/>
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
      text: 最近活动
      link: /press/
    - theme: sponsor
      text: MCCOM开发者社区
      link: https://dev.mcflare.com

features:
  - title: 多平台
    details: 我们组织涵盖Minecraft各个方面，包括但不限于服务器交流、活动开展、付费帮助等。
    icon: 🌏
    link: /docs/versions
    linkText: 版本列表
  - title: 活动丰富
    details: 组织定期联合其他服务器开展活动，让成员们有良好参与度。 
    icon: 🛠️
    link: 
    linkText: 最近活动
  - title: 社区活跃
    details: 社区群组人员长期活跃，用户可以在Github与QQ群中提问或反馈，项目开发组将尽力解答和解决问题。
    icon: 🤗
    link: https://qm.qq.com/q/HjGlhKaM0k
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
