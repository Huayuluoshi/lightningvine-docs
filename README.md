# 简介
  闪电藤是基于LocalSend二次开发的一款局域网文件传输工具，完全兼容LocalSend，并在它的基础上进行UI交互的重新设计，以及功能上的增强和删减，使其更加符合中国用户的使用体验。有了LocalSend，还要开发闪电藤，不仅是因为LocalSend的更新迭代速度较慢，更是因为它的使用体验更多的是按国外的来设计的，国内很多需求反馈无法实现。所以我根据用户需求，征集大家的建议，和大家共同建设一个更符合用户体验的局域网文件传输工具类应用。
  您可以关注闪电藤的微信公众号，以提供建议或者反馈缺陷。
![gzh](https://github.com/Huayuluoshi/lightningvine-docs/assets/117527694/f263de61-6c7a-41c7-841c-051a9e55cdd5)

## 我们为什么需要闪电藤/localsend？
  先问大家一个问题，你们在多个设备传输文件的时候都用什么工具呢？答案似乎很明显，是微信，但微信有明显的问题。

### 微信文件助手的问题
  主要是以下几个方面：
  **必须联网：**
    某些工作，基于安全考虑，是不允许办公设备连接外网的，那么微信就无法登录，更别提传输文件了。
  **在公开场合可能造成隐私泄露：**
    微信文件传输是将文件传输到微信服务器的，这些文件都是要经过微信扫描后才能传输到别的设备。所以有些隐私性强的文件走微信文件传输助手可能造成自己隐私在公开场合泄露（换句话讲，你肯定不想自己的私人文件在工作时被别人看到吧）。
  **文件大小限制：**
    如无法发送超过60分钟的视频，见下图：
    ![mm](https://github.com/Huayuluoshi/lightningvine-docs/assets/117527694/3b917121-bab6-40c4-9a57-d43fb9302b24)
  **传输速度慢：**
    因为微信传输是基于网络的，因此它的传输速度取决于您自家的网络带宽大小以及微信服务器的稳定与否等诸多因素。稍大（超过100M）的文件用微信作为传输工具时，体验可能会大打折扣。
  **传输过程可能不太友好：**
    部分场景需要主动点“原图发送”按钮，否则会造成传输的图片的画质打印出来是一片模糊；但是图片数目足够多时，由于有数量限制，每次都点“原图发送”较为繁琐。
  **设备限制：**
    微信的机制，决定了它同一类型设备只能登录一个账户（当然安卓可以双开，但也仅仅只能登录2个账户），比如iOS给iOS传输文件，或者windows给windows传输文件就非常尴尬，只能A设备登录后将文件发个文件助手，然后在B设备上再次登录去下载，就非常的不方便。并且微信在某些设备或系统上不支持（或支持不够完善），比如机顶盒、Linux等

**微信文件助手事宜的场景：**
  有网络的环境且网络环境很好，且文件不大、视频不超过1小时，且文件无私密性，不需要2个外更多设备传输等。例如，学校上课往多媒体传输PPT文档，在家打印一些文件等等。
在这样的环境下，它的使用是非常方便的，这样子的场景我建议大家继续用微信就好。

### 闪电藤的优势
  **微信的劣势，就是闪电藤的优势**，因为它**基于局域网内的传输，安全稳定且不限速**。同时，我们在使用体验上尽量**还原用户在微信文件传输助手上的使用体验**，让大家在使用上更顺畅。

**版权声明：“微信”、“WeChat”是腾讯公司（也称为Tencent）注册的商标，其知识产权属于腾讯公司。**
