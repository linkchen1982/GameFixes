# Sid Meier's Civilization V

---

## 遊戲啟動之後，所有選單的中文字或其他字體無法顯示

可能原因：
- 目前所使用的 Windows 版本是英文版，並沒有內建 SimHei 字體。 參考資料：[RE:【問題】求救！跑不出任何字幕](https://forum.gamer.com.tw/Co.php?bsn=5114&sn=11106)

解決方法：
- 使用其他中文字體。找到「C:\Program Files (x86)\Steam\steamapps\common\Sid Meier's Civilization V\Assets\Gameplay\XML\NewText\Chinese.xml」，用文字編輯器打開這個檔案後，將「<FontName>SimHei</FontName>」裡面的「SimHei」改成其他中文字體即可，例如微軟正黑體、新細明體、標楷體...等。
- 安裝 SimHei 字體。如此就不用額外更動任何設定。

---
