# filemanagercn
对于无法通过SSH或FTP访问其站点的开发人员而言，这是一种管理文件和文件夹的好解决方案。XP+IE8正常。

原版https://github.com/alexantr/filemanager

修正版及汉化版https://github.com/allwaysoft/filemanagercn

filemanagercn.php use local highlight.min.js and vs.min.css

filemanagercn2.php use online highlight.min.js and vs.min.css

filemanagercn3.php 工具图标带中文文字链接

filemanager.php english version for linux and windows php, can display chinese


警告！不要将此脚本用作公共区域中的常规文件管理器。完成所有操作后，您必须从服务器删除此脚本。

要求
PHP 5.2或更高版本。
zip扩展名，用于zip和unzip操作。
强烈建议使用Fileinfo，iconv和mbstring扩展名。
如何使用
从master分支下载具有最新版本的ZIP。

将filemanager.php(英文版)或filemanagercn.php复制到您的网站文件夹，然后在网络浏览器中打开它（例如http：//yoursite/any_path/filemanager.php）。

安全
默认用户名/密码：fm_admin / fm_admin

警告！请$auth_users在使用前设置您自己的用户名和密码。

要启用或禁用设置$use_auth为true或的身份验证false。

为了提高安全性，请在Web服务器中启用HTTP身份验证。

可配置选项
FM_ROOT_PATH -默认为 $_SERVER['DOCUMENT_ROOT']
FM_ROOT_URL -默认为 'http(s)://site.domain/'
FM_SELF_URL -默认为 'http(s)://site.domain/' . $_SERVER['PHP_SELF']
FM_ICONV_INPUT_ENC -默认为 'CP1251'
FM_USE_HIGHLIGHTJS -默认为 true
FM_HIGHLIGHTJS_STYLE -默认为 'vs'
FM_DATETIME_FORMAT -默认为 'yy.m.d H:i'
