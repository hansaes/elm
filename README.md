# elm脚本 本地自建sign

docker run --name elmsign -d -p 30880:8080 hansaes/elmsign

## 更换地址或者端口

在common.js文件中修改  自行替换对应的ip
process.env.HOST = 'http://localhost:30880'

## 拉库即用
```
ql repo https://github.com/hanses/elm.git "^ele" "" "USER|common|ql|sendNotify1|ele_coupon_rely"
```
环境变量：ms 设置多少秒提前抢券（单位毫秒），默认 1000 毫秒 export ms="1000" <br />
环境变量：delayTime 请求间隔（单位毫秒）默认 300 毫秒 export delayTime="300"  <br />
环境变量：allTime 请求总时长单位（秒）默认 20 秒 export allTime="20" <br />

[![Page Views Count](https://badges.toozhao.com/badges/01HCPMWWDQF3D4WM8Y3JRM1N09/green.svg)](https://badges.toozhao.com/stats/01HCPMWWDQF3D4WM8Y3JRM1N09 "Get your own page views count badge on badges.toozhao.com")

## 联系方式
437477052