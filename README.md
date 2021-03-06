# All in XrayScan 

### Version 2.0

- XrayRad-nopush: 批量通用版，直接生成报告！
```python

                ____                        __________     .___
    \   \/  /___________  ___.__.   \______   \_____     __| _/
     \     /\_  __ \__  \<   |  |    |       _/\__  \   / __ |
     /     \ |  | \// __ \\___  |    |    |   \ / __ \_/ /_/ |
    /___/\  \|__|  (____  / ____|____|____|_  /(____  /\____ |
          \_/           \/\/   /_____/      \/      \/      \/

                                        Author:	loecho       
                                        Date:   2021/09/24      

    --------------------------------------------------------------------------------------
                 sqlin           SQL注入漏洞探测
                 cmd             命令执行漏洞探测
                 xss             XSS漏洞探测
                 xxe             XXE漏洞探测
                 base            baseline
                 path            目录穿越
                 upload          文件上传
                 brute           暴力破解
                 dir             目录扫描
                 urlred          任意uRL跳转
                 crlf            CRLF
                 thinkphp        THINKPHP系列漏洞探测
                 shiro           SHIRO系列漏洞探测
                 fastjson        FASTJSON系列漏洞探测
                 struts          STRUTS系列漏洞探测

            usage:

                 <1> allType-漏洞检测
                     python3 xrayRad.py url.txt all

                 <2> SQL注入漏洞检测
                     python3 xrayRad.py url.txt sqlin

```

- 同样支持单一类型和全部类型！

- 爬虫修改为双爬虫（RAD + CrawleGo），宗旨是宁愿多爬，也不要漏爬！

- 并发进程修改为进程池，高效并发！

- 保存CrawleGo的爬取结果以及爬取路径，后续手工测试时，重点关注一下！

- 临时完成，有Bug请及时反馈！


![](https://loecho.oss-cn-beijing.aliyuncs.com/Blog-Img20210925035255.png)

![](https://loecho.oss-cn-beijing.aliyuncs.com/Blog-Img20210925035337.png)




 ###  Version 1.0：



- XrayRad-Scan： 为高级版用户所用，利用Xray高级版，进行批量爬取及扫描！



```python2
    _  __                  ____            __     _____
   | |/ /_________ ___  __/ __ \____ _____/ /    / ___/_________ _____
   |   // ___/ __ `/ / / / /_/ / __ `/ __  /_____\__ \/ ___/ __ `/ __ \\
  /   |/ /  / /_/ / /_/ / _, _/ /_/ / /_/ /_____/__/ / /__/ /_/ / / / /
 /_/|_/_/   \__,_/\__, /_/ |_|\__,_/\__,_/     /____/\___/\__,_/_/ /_/
                 /____/

                                                     Version:    v1.0
                                                     Author:     loecho
                                                     Blog:       https://loecho.me
```

![image-20200915143541407](https://loecho.oss-cn-beijing.aliyuncs.com/Blog-Img/20200915143542.png)



### Usage：

![image-20200915143635451](https://loecho.oss-cn-beijing.aliyuncs.com/Blog-Img/20200915143635.png)

##  扫描效果：

####   [1] 全类型漏洞批量扫描：

![image-20200915151048462](https://loecho.oss-cn-beijing.aliyuncs.com/Blog-Img/20200915151058.png)



![image-20200915145541882](https://loecho.oss-cn-beijing.aliyuncs.com/Blog-Img/20200915145606.png)



#### [2] 单类型漏洞扫描：

![image-20200915150852368](https://loecho.oss-cn-beijing.aliyuncs.com/Blog-Img/20200915150852.png)

![image-20200915150903777](https://loecho.oss-cn-beijing.aliyuncs.com/Blog-Img/20200915150903.png)





## Version 1.1：



- XrayRad：为社区版用户所用，利用Rad和Xray进行批量爬取
- XrayRad-WechatPush-server： 为配合社区版扫描，实现的微信实时推送服务端



```
    ____                        __________             .___
\   \/  /___________  ___.__.   \______   \_____     __| _/
 \     /\_  __ \__  \<   |  |    |       _/\__  \   / __ |
 /     \ |  | \// __ \\___  |    |    |   \ / __ \_/ /_/ |
/___/\  \|__|  (____  / ____|____|____|_  /(____  /\____ |
      \_/           \/\/   /_____/      \/      \/      \/


                     Usage:
                            python3 Xray_rad.py -all 全类型扫描
                            python3 Xray_rad.py sqlin sql注入扫描
                            
                     Author:	Chr1sto 
                            
                     Date:	    2020/09/01

```

## 扫描效果：

#### [1] 全类型漏洞扫描

![image-20200915170512745](https://loecho.oss-cn-beijing.aliyuncs.com/Blog-Img/20200915170513.png)

#### 启动XrayRad-Wechat-Push：

![](https://loecho.oss-cn-beijing.aliyuncs.com/Blog-Img/20200916174320.png)

### 推送结果：

![image-20200915173141940](https://loecho.oss-cn-beijing.aliyuncs.com/Blog-Img/20200915173141.png)





### 具体配置文件看代码就懂了，爬取结果保存为漏洞出现时间格式！

### 没啥技术含量，大佬勿喷！



