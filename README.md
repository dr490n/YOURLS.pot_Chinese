This page is an introduction about how to setup `Traditional Chinese` translation files in your YOURLS installation.

简体中文语言包相关的说明，请参考[简体中文语言包使用说明][6]

YOURLS Ver.1.7+ 繁體中文語言包
==========================
本語言包是根據 [YOURLS 官方翻譯模版][1] 修改的繁體中文語言包。提供給 YOURLS 1.7 以
上版本使用。

## 語言包使用方法

1. 訪問 [YOURLS 官方網站][2]或者此項目的 [Github源][3] 下載最新版本的YOURLS程式。
2. 下載本繁體中文語言包，將 `zh_Hant/zh_Hant.po` 和 `zh_Hant/zh_Hant.mo` 兩個文件複製到 YOURLS 安裝路徑下的 `user/languages` 資料夾中。
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

6. 打開瀏覽器訪問 `http://_YOURSITE_/admin/` ，就這樣！你就可以看到繁體中文版的 YOURLS 應用程式了。

## 反饋錯誤

如果你發現語言包裏面的內容有錯誤，你可以將出現錯誤的截圖等信息提交到本項目的 [Issues][5] 中，我會儘快進行修改。

## 聯繫方式

新浪微博/騰訊微博：@dr490n

Twitter: @i4mdr490n

E-mail: `cn7log`@`gmail`.com


This page is an introduction about how to setup `Traditional Chinese` translation files in your YOURLS installation. 

[1]: https://github.com/YOURLS/YOURLS.pot "YOURLS 官方翻译模版"
[2]: http://yourls.org/ "YOURLS 官方网站"
[3]: https://github.com/YOURLS/YOURLS "YOURLS 官方 Github 源"
[4]: http://yourls.org/#Install "YOURLS 安装向导"
[5]: https://github.com/dr490n/YOURLS.pot\_Chinese/issues "提交你对本项目的建议"
[6]: <https://github.com/dr490n/YOURLS.pot_Chinese/wiki/YOURLS-Ver.1.7--中文语言包> "简体中文语言包使用说明"
