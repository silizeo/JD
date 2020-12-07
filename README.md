# *---------------------- 安卓用户企鹅阅读 Cookies修改指南 ----------------------*

### 安卓用户抓包Secrets格式如下所示  ：
#### 样例 QQREAD_BODY:  
###### 小黄鸟关键词：book_read
  ```
{"common":{"appid":111,"areaid":5,"qq_ver":"8.4.18.4945","os_ver":"Android 10","mp_ver":"0.31.0","mpos_ver":"1.21.0","brand":"Xiaomi","model":"Mi 10 Pro","screenWidth":393,"screenHeight":835,"windowWidth":393,"windowHeight":781,"openid":"111","guid":11,"session":"111","scene":3001,"source":"11","hasRedDot":"false","missions":-1,"caseID":-1},"dataList":[{"click1":"push_limitYes_suc_C","click2":"bookStore_newCl_nextPage_C","route":"pages/book-read/index","refer":"pages/index/index","options":{"bid":"11"},"dis":11,"ext6":8,"eventID":"onHide_O","type":"others","ui_pos":2}]}

  ```
#### 样例 QQREAD_TIMEURL:  
###### 小黄鸟关键词：TimeWithBid
  ```
https://mqqapi.reader.qq.com/mqq/addReadTimeWithBid?scene=***&refer=-1&bid=***&readTime=***&read_type=0&conttype=1&read_status=0&chapter_info=%5B%7B%221%22%3A%7B%22readTime%22%3A***%2C%22pay_status%22%3A0%7D%7D%5D&sp=-1
  ```
#### 样例 QQREAD_TIMEHD :   
###### 小黄鸟关键词：ck2
  ```
{"ywsession":"填写你的ywsession信息","Cookie":"填写你QQREADHEADERKEY的cookie,长一点的，带openid的","Connection":"keep-alive","Content-Type":"application/json","Accept":"*/*","Host":"mqqapi.reader.qq.com","User-Agent":"你抓到的UserAgent","Referer":"Referer链接","Accept-Language":"zh-cn","Accept-Encoding":"gzip, deflate, br","mpversion":"这个安卓和IOS的不一致，自己填"}
  ```
### 多账号直接换行就行  

### 安卓抓包工具  
HttpCanary（我用的）

#### 感谢sazs34大佬的替换思路和脚本  https://github.com/sazs34  
#### 感谢ZIYE制作的企鹅阅读脚本  https://github.com/ziye12/JavaScript/  
#### 感谢telegram群的Money Mr提供脚本 https://t.me/qhqcz
#### 感谢Addr大佬指导的安卓抓包教程 https://github.com/paopaoya
