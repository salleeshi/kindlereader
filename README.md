# Kindlereader (gae)

一个定时将Google reader发送至kindle的工具，运行于 Google app engine, demo [http://reader.dogear.mobi](http://reader.dogear.mobi)

## 安装

* 修改 app.yaml 中 application id,
* 将 config.example.py 更名为 config.py 并配置其中内容
* 如果账单开启则 queue.example.billing.yaml 更名为 queue.yaml 否则 queue.example.yaml 更名为 queue.yaml
* 上传

## 许可

Kindlereader is Licensed under the MIT license: [http://www.opensource.org/licenses/mit-license.php](http://www.opensource.org/licenses/mit-license.php)