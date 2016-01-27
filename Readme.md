#關於PAYDAY2 Block screen fix 的 Readme.md (使用說明)
此專案為解決PAYDAY2全螢幕開啟時可能造成黑屏的現象，上網爬文找到的方法，為了方便下一位使用者爬文，將遊戲廠商官方提供的XML及修改後的XML進行比對，並製作此專案

##授權方式
本專案選用的授權方式為GNU General Public License v2.0，詳情請訪問本目錄的LICENSE.txt檔案
本專案"全部"的文件皆適用此授權檔，包含整個PAYDAY2_Block_screen_fix主資料夾、及裏頭的Backup資料夾

##如何找到螢幕設定檔
1. 透過SETAM下載PAYDAY2並安裝完成後，並執行它，檢查是否成功啟動
說明：如果成功啟動，就算黑屏也會生成設定檔，假設閃退(開啟後沒反應)，就不會生成設定檔(請尋找其他方法)

2. 在Local資料夾找到PAYDAY2資料夾，並找到renderer_settings.xml設定檔

路徑：C:\Users\ID\AppData\Local\PAYDAY 2
路徑說明：請將ID改成自己電腦的帳號名稱




#Backup資料夾說明
裏頭有兩個檔案，分別為...
renderer_settings_original.xml
renderer_settings_new.xml

作用說明：
renderer_settings_original.xml：為下載Payday2並安裝完成後，系統所生成出來的xml螢幕配置設定檔，預設為全螢幕
renderer_settings_new.xml：為修改版xml螢幕配置設定檔，設定為視窗模式

如果要套用其中一個，請先複製到自己熟悉的資料夾(或桌面)，變更為renderer_settings.xml，再按照前面步驟複製並覆蓋原始檔即可