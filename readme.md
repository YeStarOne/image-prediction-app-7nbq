# image-prediction-app 帮助文档

<p align="center" class="flex justify-center">
    <a href="https://www.serverless-devs.com" class="ml-1">
    <img src="http://editor.devsapp.cn/icon?package=image-prediction-app&type=packageType">
  </a>
  <a href="http://www.devsapp.cn/details.html?name=image-prediction-app" class="ml-1">
    <img src="http://editor.devsapp.cn/icon?package=image-prediction-app&type=packageVersion">
  </a>
  <a href="http://www.devsapp.cn/details.html?name=image-prediction-app" class="ml-1">
    <img src="http://editor.devsapp.cn/icon?package=image-prediction-app&type=packageDownload">
  </a>
</p>

<description>

基于 ImageAI 框架的的目标检测

</description>

<table>

## 前期准备
使用该项目，推荐您拥有以下的产品权限 / 策略：

| 服务/业务 | 函数计算 | 对象存储               |     
| --- |  --- |--------------------|   
| 权限/策略 | AliyunFCFullAccess | AliyunOSSFullAccess |  


</table>

<codepre id="codepre">

# 代码 & 预览

- [ :smiley_cat:  源代码](https://github.com/devsapp/start-fc/blob/main/image-prediction-app)

</codepre>

<deploy>

## 部署 & 体验

<appcenter>

-  :fire:  通过 [Serverless 应用中心](https://fcnext.console.aliyun.com/applications/create?template=image-prediction-app) ，
[![Deploy with Severless Devs](https://img.alicdn.com/imgextra/i1/O1CN01w5RFbX1v45s8TIXPz_!!6000000006118-55-tps-95-28.svg)](https://fcnext.console.aliyun.com/applications/create?template=image-prediction-app)  该应用。 

</appcenter>

- 通过 [Serverless Devs Cli](https://www.serverless-devs.com/serverless-devs/install) 进行部署：
    - [安装 Serverless Devs Cli 开发者工具](https://www.serverless-devs.com/serverless-devs/install) ，并进行[授权信息配置](https://www.serverless-devs.com/fc/config) ；
    - 初始化项目：`s init image-prediction-app -d image-prediction-app`   
    - 进入项目，并进行项目部署：`cd image-prediction-app && s deploy -y`

</deploy>

<appdetail id="flushContent">

# 应用详情

本应用仅作为学习和参考使用，您可以基于本项目进行二次开发和完善，实现自己的业务逻辑。

本应用采用了 ImageAI 项目作为原型，并与 HTTP 触发器和 OSS 触发器进行结合。应用部署完成，会有两个函数资源：

- image_custom：通过url进行请求，部署完成会有相对应的测试地址，测试地址中有相对应的使用文档；
- image_python：通过oss进行触发，用户需要按照配置的前缀，上传图片到对应的存储桶，稍等片刻会生成对应的结果；


</appdetail>

<devgroup>

## 开发者社区

您如果有关于错误的反馈或者未来的期待，您可以在 [Serverless Devs repo Issues](https://github.com/serverless-devs/serverless-devs/issues) 中进行反馈和交流。如果您想要加入我们的讨论组或者了解 FC 组件的最新动态，您可以通过以下渠道进行：

<p align="center">

| <img src="https://serverless-article-picture.oss-cn-hangzhou.aliyuncs.com/1635407298906_20211028074819117230.png" width="130px" > | <img src="https://serverless-article-picture.oss-cn-hangzhou.aliyuncs.com/1635407044136_20211028074404326599.png" width="130px" > | <img src="https://serverless-article-picture.oss-cn-hangzhou.aliyuncs.com/1635407252200_20211028074732517533.png" width="130px" > |
|--- | --- | --- |
| <center>微信公众号：`serverless`</center> | <center>微信小助手：`xiaojiangwh`</center> | <center>钉钉交流群：`33947367`</center> | 

</p>

</devgroup>