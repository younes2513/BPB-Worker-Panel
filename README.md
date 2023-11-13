## Cloudflare代理脚本

## 支持workers与pages两种形式部署

## 现实vless+ws+tls与vless+ws两种代理节点

## 详细说明教程请参考[甬哥博客及视频教程](https://ygkkk.blogspot.com/2023/07/cfworkers-vless.html)
--------------------------------
### CF vless代码默认修改内容

1、UUID强烈建议自定义

2、proxyIP已更新支持chatgpt的IP，可直接使用（你可以更换其他反代IP或者第三方域名，以确保可以正常访问CF类网站）

3、伪装网页默认为微软www.bing.com，可自定义

4、重点对workers与pages、有域名与无域名，这4种情况下的节点分享做了优化显示，方便小白们理解操作

---------------------------------
### CF-CDN优选域名一键脚本，苹果安卓手机平板专用，(请参考教程，在本地网络环境下运行)：
```
curl -sSL https://gitlab.com/rwkgyg/CFwarp/raw/main/point/CFcdnym.sh -o CFcdnym.sh && chmod +x CFcdnym.sh && bash CFcdnym.sh
```
------------------------------------------------------------------------
### CF-优选反代IP一键脚本，苹果安卓手机平板专用，(请参考教程，在本地网络环境下运行)：
```
curl -sSL https://gitlab.com/rwkgyg/CFwarp/raw/main/point/cfip.sh -o cfip.sh && chmod +x cfip.sh && bash cfip.sh
```

------------------------------------------------------------------------
### 感谢：CF-vless代码作者[3Kmfi6HP](https://github.com/3Kmfi6HP/EDtunnel) CF优选IP程序作者[badafans](https://github.com/badafans/Cloudflare-IP-SpeedTest)、[XIU2](https://github.com/XIU2/CloudflareSpeedTest)


