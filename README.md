# 🚀 优选订阅生成器 WorkerVless2sub


----

## 🔑 变量说明
| 变量名 | 示例 | 备注 | 
|--------|---------|-----|
| TOKEN | `auto` | 快速订阅内置节点的订阅路径地址 /auto （支持多元素, 元素之间使用`,`或`换行`作间隔）| 
| HOST | `edgetunnel-2z2.pages.dev` | 快速订阅内置节点的伪装域名 （支持多元素, 订阅时随机获取, 元素之间使用`,`或`换行`作间隔） | 
| UUID | `b7a392e2-4ef0-4496-90bc-1c37bb234904` | 快速订阅内置VLESS节点的UUID （与变量`PASSWORD`冲突, 共存时优先使用`PASSWORD`） | 
| KEY | `token` | 动态UUID秘钥，使用变量`KEY`的时候，将不再启用变量`UUID`|
| TIME | `7` | 动态UUID有效时间（单位:天）|
| UPTIME | `3` | 动态UUID更新时间（默认:北京时间`3`点更新） |
| PASSWORD | `bpb-trojan` | 快速订阅内置Trojan节点的password （与变量`UUID`冲突, 共存时优先使用`PASSWORD`） | 
| PATH | `/?ed=2560` | 快速订阅内置节点的路径信息 | 
| SNI | `www.10068.cn` | 快速订阅内置节点的SNI信息（留空则默认同`host`） | 
| TYPE | `splithttp` | 快速订阅内置节点的传输协议信息（留空则默认为`ws`） | 
| ALPN | `h3` | Alpn（留空则默认为`http/1.1`） | 
| ADD | `icook.tw:2053#官方优选域名` | 对应`addresses`字段 （支持多元素, 元素之间使用`,`或`换行`作间隔） | 
| ADDAPI | [https://raw.github.../addressesapi.txt](https://raw.githubusercontent.com/cmliu/WorkerVless2sub/main/addressesapi.txt) | 对应`addressesapi`字段 （支持多元素, 元素之间使用`,`或`换行`作间隔） | 
| ADDNOTLS | `icook.hk:8080#官方优选域名` | 对应`addressesnotls`字段 （支持多元素, 元素之间使用`,`或`换行`作间隔） | 
| ADDNOTLSAPI | [https://raw.github.../addressesapi.txt](https://raw.githubusercontent.com/cmliu/CFcdnVmess2sub/main/addressesapi.txt) | 对应`addressesnotlsapi`字段 （支持多元素, 元素之间使用`,`或`换行`作间隔） | 
| ADDCSV | [https://raw.github.../addressescsv.csv](https://raw.githubusercontent.com/cmliu/WorkerVless2sub/main/addressescsv.csv) | 对应`addressescsv`字段 （支持多元素, 元素之间使用`,`或`换行`作间隔） | 
| DLS | `8` |`addressescsv`测速结果满足速度下限 | 
| NOTLS | `false` | 改为`true`, 将不做域名判断 始终返回noTLS节点 | 
| TGTOKEN | `6894123456:XXXXXXXXXX0qExVsBPUhHDAbXXXXXqWXgBA` | 发送TG通知的机器人token | 
| TGID | `6946912345` | 接收TG通知的账户数字ID | 
| SUBAPI | `subapi.cmliussss.net` | clash、singbox等 订阅转换后端 | 
| SUBCONFIG | [https://raw.github.../ACL4SSR_Online_Full_MultiMode.ini](https://raw.githubusercontent.com/cmliu/ACL4SSR/main/Clash/config/ACL4SSR_Online_Full_MultiMode.ini) | clash、singbox等 订阅转换配置文件 | 
| SUBNAME | `优选订阅生成器` | 订阅生成器名称 | 
| ICO | `https://raw.cmliussss.com/favicon.ico` | 网站图标 |
| PNG | `https://raw.cmliussss.com/img/CM512.png` | 网站LOGO | 
| IMG | `https://raw.cmliussss.com/keqing1080p.jpg` | 背景图片，多张图片将随机展示 （多元素`换行`作间隔） | 
| BEIAN | `提供维护: <a href='https://t.me/CMLiussss'>CMLiussss</a>` | 主页维护信息 | 
| SOCKS5DATA | [https://raw.github.../socks5Data](https://raw.githubusercontent.com/cmliu/WorkerVless2sub/main/socks5Data) | Socks5代理池 | 
| PS | `【请勿测速】` | 节点名备注消息 | 
| PROXYIP | `proxyip.cmliussss.net` | 默认分配的ProxyIP, 多ProxyIP将随机分配（支持多元素, 元素之间使用`,`或`换行`作间隔） | 
| PROXYIPAPI | `https://raw.cmliussss.com/Serv00_ProxyIP.txt` | 不支持多元素 | 
| CMPROXYIPS | `proxyip.aliyun.cmliussss.net#HK` | 识别HK后分配对应的ProxyIP（支持多元素, 元素之间使用`,`或`换行`作间隔） | 
| CFPORTS | `2053`,`2096`,`8443` | CF账户标准端口列表 |
| URL302 | `https://t.me/CMLiussss` | 主页302跳转(支持多url, url之间使用`,`或`换行`作间隔, 小白别用) |
| URL | `https://blog.cmliussss.com` | 主页反代伪装(支持多url, url之间使用`,`或`换行`作间隔, 乱设容易触发反诈) |
| LINK | `vless://b7a39...`,`vmess://ew0K...`,`https://sub...` | 补充的**公益节点链接**（不要填入私用节点）, 可同时放入多个节点链接与多个订阅链接（支持多元素, 元素之间使用`,`或`换行`作间隔） |
| COLOR | `1-10` | 不同颜色主题 |
| KV | `绑定KV空间` | KV空间键入HOST_LIST，存储HOST变量，必设UUID |

----

## ⭐ Star 星星走起
[![Stargazers over time](https://starchart.cc/cmliu/WorkerVless2sub.svg?variant=adaptive)](https://starchart.cc/cmliu/WorkerVless2sub)

# 🙏 特别鸣谢

### 🛠 开源代码引用
- [SAKURA-YUMI](https://github.com/SAKURA-YUMI)
- [EzSync](https://github.com/EzSync)
- [ACL4SSR](https://github.com/ACL4SSR/ACL4SSR/tree/master/Clash/config)
- [3Kmfi6HP](https://github.com/6Kmfi6HP/EDtunnel/blob/main/.github/workflows/obfuscator.yml)


