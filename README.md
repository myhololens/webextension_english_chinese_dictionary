词典数据来源: https://github.com/skywind3000/ECDICT

#### 安装链接
- [火狐插件](https://addons.mozilla.org/zh-CN/firefox/addon/%E7%A6%BB%E7%BA%BF%E8%8B%B1%E6%B1%89%E8%AF%8D%E5%85%B8/)
- [Chrome插件](https://chrome.google.com/webstore/detail/%E7%A6%BB%E7%BA%BF%E8%8B%B1%E6%B1%89%E8%AF%8D%E5%85%B8/ndifefelacmidghjaehmhicbchbidhpe/related?hl=en)

#### 打包
使用[web-ext](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/web-ext_command_reference), 跳过测试部分, 以加速审核过程.
```
$ web-ext build --ignore-files=test
```
