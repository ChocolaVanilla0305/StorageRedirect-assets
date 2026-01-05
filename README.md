# StorageRedirect-assets

Assets (rules, apks etc) for Storage Isolation app.

https://sr.rikka.app

https://play.google.com/store/apps/details?id=moe.shizuku.redirectstorage

# 关于此仓库
~~此仓库解决源仓库持续不维护的问题~~
<br/>有issues请在这个仓库提出！
<br/>由于对维护工作还有点不熟悉且不会去耗费很多时间测试应用，关于规则如果读取不出来也请写一份issues！

# 如何使用
[使用指南](https://github.com/ChocolaVanilla0305/StorageRedirect-assets/blob/master/guides/how2use.md)

# 仓库文件说明
│</br>
├─app_category</br>
│  │  app_categories_data.json</br>
│  │  app_categories_description.json</br>
│  │</br>
│  └─apps</br>
│          &nbsp;com.autonavi.minimap.json</br>
│</br>
├─**app_rule    规则主入口**</br>
│  │  app_recommendation_data.json</br>
│  │  **verified_apps.json    受信应用列表**</br>
│  │</br>
│  └─ **apps    应用规则**</br>
│          &nbsp;……</br>
│</br>
├─**guides    指南文件**</br>
│      &nbsp;how2use.md</br>
│</br>
├─**imgs    指南文件引用的图片**</br>
│      &nbsp;01.png</br>
│</br>
└─tools</br>
    &nbsp;└─helper_python</br>
            &nbsp;&nbsp;.gitignore</br>
            &nbsp;&nbsp;data_converter.py</br>
            &nbsp;&nbsp;main.py</br>
            &nbsp;&nbsp;**README.md    本文档**</br>
            &nbsp;&nbsp;utils.py