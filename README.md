Anti-China-Anit-virus
=====================

国产安全软件免疫补丁（一键干掉（免疫）国产安全软件）

Introduction / 简介
=====================
国产安全软件免疫补丁利用CRL，将这些软件开发商的证书导入吊销列表中，在运行含有这些证书的程序时会自动被系统阻止的原理制作而成的。
（包含百度，360以及腾讯）
Installation / 安装
=====================
点击下面的URL下载，按照提示导入注册表即可。

Dependencies / 依赖
====================
Windows 7或更新版本的UAC组件
强化免疫可能需要使用本地安全策略？

How Anti-China-Anti-virus Work? / 工作原理
===========================================
注册表文件中包含了软件开发商的证书，双击后自动添加至CRL（证书吊销列表）中，使得软件在触发UAC时被系统阻止。
"强化免疫中.reg"用于打开本地安全策略里的“软件限制策略"，使得无论UAC是否工作软件都无法运行。
Side effects / 副作用
==========================================
该软件开发商的所有产品均会被阻止，例如在导入“Tencent.reg"后，QQ也将被阻止运行。
Cancel / 撤销方法
=========================================
打开“反免疫”文件夹，阅读里面的使用说明。
Screenshot / 使用截图
=========================================
![image](https://github.com/SCFWSE-Ye/Anti-China-Anti-virus/raw/master/1.jpg)
