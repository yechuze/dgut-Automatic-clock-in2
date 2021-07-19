
<p align="center">
 <h1 align="center">东莞理工学院疫情打卡脚本</h1>
 <p align="center">利用GitHub actions实现每日自动签到，教程对新手极度不友好</p>
</p>
  <p align="center">
  <a href="https://github.com/mimiranda0111/covid19-2021/watchers"><img alt="GitHub" src="https://badgen.net/github/watchers/mimiranda0111/covid19-2021?label=Watchers&color=0088ff&style=for-the-badge" /></a>
 <a href="https://github.com/mimiranda0111/covid19-2021/issues"><img alt="GitHub" src="https://badgen.net/github/issues/mimiranda0111/covid19-2021?label=Issue&color=0088ff&style=for-the-badge" /></a>
    <a href="https://github.com/mimiranda0111/covid19-2021/stargazers"><img alt="GitHub" src="https://badgen.net/github/stars/mimiranda0111/covid19-2021?label=Stars&style=for-the-badge"></a>
    <a href="https://github.com/mimiranda0111/covid19-2021/network/members"><img alt="GitHub" src="https://badgen.net/github/forks/mimiranda0111/covid19-2021?label=Fork&style=for-the-badge"></a>
 <br />
  </p>
<p align="center">感谢你的<a href="">捐赠❤</a>来帮助它完善！
<br />
<h3 align="center">默默关注也是鼓励的话，希望你能在右上角给颗⭐！你的支持是我最大的动力😎！</h3>


### 免责申明
    
该项目仅供学习使用，严禁用于商业用途，由此造成的一切后果，本人概不负责。

### 食用方法
- 首先注册一个GitHub账号

- [小白请直接点击此处查看图文教程](https://share.weiyun.com/C8Av7vpu)

- 环境变量配置：`Settings`=>`Secrets`=>点击`new repository secrets`在里面里面添加3个环境变量

 |   | Name | Value |
 | - | - | - |
 |1| `USERNAME` | 202041231212(学号)|
 |2| `PASSWORD` | 账号密码 |
 |3| `SCKEY` | server酱的key |
 |4| `PAT` | PAT申请的key（用于同步） |


- server酱如何使用请[点击这里](https://zhuanlan.zhihu.com/p/108201220?from_voters_page=true)，[server酱地址点击直达](http://sc.ftqq.com/3.version)用GitHub授权登录，然后获得SCKEY，扫码绑定微信即可收到通知，或者使用[server酱turbo版](https://sct.ftqq.com/)，进入后点击[消息通道](https://sct.ftqq.com/forward)进行配置，推荐使用微信企业来进行通知。
- 通知可以不使用，等班干过来跟你讲。

### 手动运行一次

- 点击`Actions`=>`Enable workflows`=>查看workflows是否有两项分别为 “HealthyPunch” 和 “A🔄自动同步🔄A” 点击第一行，在右边找到run workflows即可
![微信图片_20210701112955.png](https://i.loli.net/2021/07/05/HVXImoLlkNyu6Mr.png)
- 然后star ⭐星标本仓库即可运行或者修改一下`README.md`文件的内容，然后就能自动运行一次

### 新增字段无法正常打卡（已使用自动同步，请删除原有仓库再fork本仓库）
- 若要使用自动同步功能，请在`Secrets`处添加`PAT`如何申请PAT[点击这里](https://gitee.com/miranda0111/JDscret/blob/main/backup/reposync.md)此处借用jdsecret的同步进行说明，感谢搬运 大佬的支持！
- 若不使用，请将`Keys.json`文件中的内容复制到自己的仓库中（最笨的方法）。

### 其他

- 不懂得使用请加q:[591944012](https://im.qq.com/index)
- 


