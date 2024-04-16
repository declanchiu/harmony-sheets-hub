<p>
  <img src="https://assets.solidjs.com/banner?project=Library&type=core" alt="SolidJS" />
</p>

<p align="center">
  <a href="https://github.com/declanchiu/harmony-sheets-hub" target="_blank" rel="noopener noreferrer">
    <img width="180" src="https://s21.ax1x.com/2024/04/16/pFxgRWd.png" alt="HarmonySheetsHub logo">
  </a>
</p>
<br/>
<p align="center">
  <a href="https://github.com/vitejs/vite"><img src="https://img.shields.io/badge/vite-7E85FF?style=for-the-badge&logo=vite&logoColor=FFCE26" alt="vite badge"></a>
  <a href="https://nodejs.org/en/about/previous-releases"><img src="https://img.shields.io/badge/solid-0D4082?style=for-the-badge&logo=solid&logoColor=76B3E1" alt="solid badge"></a>
  <a href="https://github.com/tailwindlabs/tailwindcss"><img src="https://img.shields.io/badge/tailwindcss-000000?style=for-the-badge&logo=tailwindcss&logoColor=38BDF8" alt="build status"></a>
   <a href="https://github.com/microsoft/TypeScript"><img src="https://img.shields.io/badge/typescript-2F74C0?style=for-the-badge&logo=typescript&logoColor=38BDF8" alt="build status"></a>
</p>
<br/>

# HarmonySheetsHub 🎼
> 北半球不一定最厉害的谱子视奏、学习工具。

- 💡 解决图片和 pdf 谱子不好自动播放视奏的问题
- ⚡️ 使用 solid 获取更好性能
- 🔑 不止是一个看谱工具，未来还有更多惊喜！！！！

HarmonySheetsHub 诞生的原因主要是在使用图片类型的曲谱或者 pdf 类型的曲谱他没办法像类似吉他谱的 guitar pro 8 这种工具可以播放谱子按照谱子的符号或者每个小节的音符进行播放，方便用户进行学习或者视奏。所以该工具主要解决练习、视奏场景上的曲谱使用问题以及一些好用的辅助工具。

# Feature 🧐
可以随时关注这份需求池的变化，我把这个需求池进行公开化，有兴趣的小伙伴可以随时联系我探讨这个工具，如果您愿意可以随时和我一起共创它。

https://flowus.cn/declanchiu/share/393fa5a2-37ec-487e-8a10-b077f34424f9?code=C8XEAH

# Deployment 💻

```shell
pnpm install

pnpm dev
```

# FAQ
#### 为什么版本号取的那么奇怪？
因为个人风格的原因，版本号没有遵从普遍的 semver 规范，而是取用了[化学元素表]("https://www.talbica.com/")进行版本迭代。 

### 这个工具维护的频繁吗？
不好说，因为该项目存粹是首先为了解决作者本身练琴的问题而规划诞生的，该工具的迭代是否频繁主要看贡献人员和作者本人的时间精力。

### 这个项目的 LOGO 是自己设计的吗？
不是，不好意思，作者本人不会设计 LOGO, 并且 AI 生成的太丑了接受不了，所以在[dribbble]("https://dribbble.com/") 随便找了一个觉得好看的抠图中间的元素形成的。如果侵权了您的作品请随时告知我。我会进行更换处理。

### 当前项目会有服务端进行存储曲谱吗？
🤔其实服务端存储并不在很 top 的考虑范围内，但是也不会说 pass 这个方案，考量就是该工具想尽量的离线化，依靠的曲谱存储是来源于使用者比如 icloud, 百度网盘，图床等其他第三方存储设备导入数据来实现的。但是其实也是可以供服务端私有化的方案也说不定，因为曲谱毕竟是他人的知识作品，当前工具不太适合暴露到公网上。

### 只能支持吉他谱吗？
当然不，憧憬就是支持例如乐队的级数谱、吉他谱、钢琴谱、等等任何图片类型或 pdf 类型的曲谱都可以纳入支持范围内，只要有客户有视奏需要。这也是当前项目命名没有太固定的原因。