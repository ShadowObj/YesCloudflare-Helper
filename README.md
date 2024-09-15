# YesCloudflare-Helper

查询Cloudflare反代节点小工具 [YesCloudflare](https://github.com/ShadowObj/YesCloudflare) **的 配置助手**

Demo地址: https://yescf00.pages.dev/

Full HTML5 & CSS3 & Vanilla Javascript

### 用法 Usage

1. 获取 APIKEY ([见下方教程](https://github.com/ShadowObj/YesCloudflare-Helper#%E5%A6%82%E4%BD%95%E8%8E%B7%E5%8F%96apikey)👇)
2. 打开Demo网页
3. 按提示操作

附: 
1. [config.toml 配置文件完整示例](https://github.com/ShadowObj/YesCloudflare/blob/main/config.toml)
2. [小白向 - 如何获取Cloudflare反代IP列表指北](https://telegra.ph/%E5%A6%82%E4%BD%95%E8%8E%B7%E5%8F%96Cloudflare%E5%8F%8D%E4%BB%A3IP%E5%88%97%E8%A1%A8%E6%8C%87%E5%8C%97-08-21)

### 如何获取APIKEY

进入censys的Search API汇总页
https://search.censys.io/api#/hosts/searchHosts

如果未注册：

点击右上角Register，按流程进行(需要常见邮箱，不支持临时邮箱)，进行邮箱验证，**登入时选择"Censys Search"**，重新点击上方网址

如果已注册：进入上方网址

在上述流程完成后，来到下方任意一个API块，点击Try it out，再点击Execute，在Responses中会出现用于curl的一串命令，其中"Authorization: Basic"后的一长串字符即为APIKEY。

*注意：不要复制额外的空格哟！(＾Ｕ＾)ノ~*
