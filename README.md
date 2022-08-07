# 京东上车链接：https://carcloud.ml/
## 本仓库为学习使用，请在下载后24h内删除
- 收集全网未加密日常任务脚本，无开卡无变量任务。
- `encryption`文件夹为加密脚本，慎用。
## 拉库地址
- 定时 :    1 * * * *

- 任务 :
```
ql repo https://github.com/feverrun/my_scripts.git "jd_|jx_|jddj_|getCookie|getJDCookie" "backUp/activity|backUp/card|backUp/py|backUp/utils/|backUp/test|jd_fruits.js|jd_pet.js|jd_factory.js|jd_health.js|jd_sgmh.js|jd_dreamFactory.js|jd_plantBean.js" "^(jd|JD|JS)[^_]|USER|sendNotify|utils"
```


## nodejs模块安装
### 方法一: 进入青龙容器安装依赖
```
npm install -g png-js
npm install -g date-fns
npm install -g axios
npm install -g dotenv
npm install -g got
npm install -g crypto-js
npm install -g md5
npm install -g ts-md5
npm install -g tslib
npm install -g @types/node
npm install -g request
npm install -g tough-cookie
npm install -g jsdom
npm install -g download
npm install -g tunnel
npm install -g ws
npm install -g js-base64
npm install -g qrcode-terminal
npm install -g moment
```
### 方法二：进入青龙后台安装依赖
依赖管理》NodeJs》添加依赖》选择自动拆分，把以下内容全部复制到名称里，之后点击确定
```
png-js
date-fns
axios
dotenv
got
crypto-js
md5
ts-md5
tslib
@types/node
request
tough-cookie
jsdom
download
tunnel
ws
js-base64
qrcode-terminal
moment
```