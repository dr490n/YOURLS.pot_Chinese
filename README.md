YOURLS Ver.1.7+ 简体中文语言包
==========================

本语言包是根据 [YOURLS 官方翻译模版][1] 修改的简体中文语言包。提供给 YOURLS 1.7 以上版本使用。

## 语言包使用方法

1. 访问 [YOURLS 官方网站][2]或者此项目的 [Github源][3] 下载最新版本的YOURLS程序。
2. 下载本简体中文语言包，将`zh_Hans/zh_Hans.po`和`zh_Hans/zh_Hans.mo`两个文件复制到 YOURLS 安装路径下的 `user/languages` 文件夹中。
3. 修改 `user/config.php` 文件，在文件中找到以下代码：
	define( 'YOURLS_LANG', '' ); 
将其修改为：
	define( 'YOURLS_LANG', 'zh_Hans' );
记住保存哦！
> 如果没有该文件，请将 `user/config-sample.php` 另存为该文件名即可。
4. 按照官方的 [安装向导][4] 对其他的设置进行修改。
> 当然也可以将服务器上已经配置好的 `user/config.php` 文件下载到本地进行修改。
5. 完成后，将 YOURLS 安装路径中的所有文件上传到你的服务器空间中。
> 如果你不是全新安装或者升级的话，可以只上传新增的语言包和修改的 `user/config.php` 文件。
6. 打开浏览器访问 `http://\_YOURSITE\_/admin/` ，就这样！你就可以看到简体中文版的 YOURLS 应用程序了。

## 反馈错误

如果你发现语言包里面的内容有错误，你可以将出现错误的截图等信息提交到本项目的 [Issues][5] 中，我会尽快进行修改。

## 联系方式

新浪微博/腾讯微博：@dr490n
Twitter: @i4mdr490n
Email: `cn7log`@`gmail`.com

YOURLS Ver.1.7+ 繁體中文語言包
==========================
本語言包是根據 [YOURLS 官方翻譯模版][1] 修改的繁體中文語言包。提供給 YOURLS 1.7 以
上版本使用。

## 語言包使用方法

1. 訪問 [YOURLS 官方網站][2]或者此項目的 [Github源][3] 下載最新版本的YOURLS程式。
2. 下載本繁體中文語言包，將`zh_Hant/zh_Hant.po`和`zh_Hant/zh_Hant.mo`兩個文件複製到 YOURLS 安裝路徑下的 `user/languages` 資料夾中。
3. 修改 `user/config.php` 文件，在文件中找到以下程式：
        define( 'YOURLS_LANG', '' );
將其修改為：
        define( 'YOURLS_LANG', 'zh_Hant' );
記住保存哦！
> 如果沒有該文件，請將 `user/config-sample.php` 另存為該文件名即可。
4. 按照官方的 [安裝說明][4] 對其他的設置進行修改。
> 當然也可以將伺服器上已經配置好的 `user/config.php` 文件下載到本地進行修改。
5. 完成後，將 YOURLS 安裝路徑中的所有文件上載到你的伺服器空間中。
> 如果你不是全新安裝或者升級的話，可以只上載新增的語言包和修改的 `user/config.php` 文件。
6. 打開瀏覽器訪問 `http://\_YOURSITE\_/admin/` ，就這樣！你就可以看到繁體中文版的 YOURLS 應用程式了。

## 反饋錯誤

如果你發現語言包裏面的內容有錯誤，你可以將出現錯誤的截圖等信息提交到本項目的 [Issues][5] 中，我會儘快進行修改。

## 聯繫方式

新浪微博/騰訊微博：@dr490n
Twitter: @i4mdr490n
E-mail: `cn7log`@`gmail`.com

This page is an introduction about how to setup `Simplified Chinese` translation files in your YOURLS installation. 

[1] https://github.com/YOURLS/YOURLS.pot "YOURLS 官方翻译模版"
[2] http://yourls.org/ "YOURLS 官方网站"
[3] https://github.com/YOURLS/YOURLS "YOURLS 官方 Github 源"
[4] http://yourls.org/#Install "YOURLS 安装向导"
[5] https://github.com/dr490n/YOURLS.pot\_Chinese/issues "提交你对本项目的建议"
