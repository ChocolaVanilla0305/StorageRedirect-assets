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
<div>
│
├─app_category
│  │  app_categories_data.json
│  │  app_categories_description.json
│  │
│  └─apps
│          com.autonavi.minimap.json
│
├─**app_rule    规则主入口**
│  │  app_recommendation_data.json
│  │  **verified_apps.json    受信应用列表**
│  │
│  └─ **apps    应用规则**
│          ……
│
├─**guides    指南文件**
│      how2use.md
│
├─**imgs    指南文件引用的图片**
│      01.png
│
└─tools
    └─helper_python
            .gitignore
            data_converter.py
            main.py
            **README.md    本文档**
            utils.py
</div>