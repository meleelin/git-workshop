![](https://miro.medium.com/max/910/1*A5zK5mklkvqFAA04vtskcg.png)
## git是什麼?
如果你問大部份正在使用 Git 這個工具的人「什麼是 Git」，他們大多可能會回答你「Git 是一種版本控制系統」，專業一點的可能會回答你說「Git 是一種分散式版本的版本控制系統」。「版本控制系統」的英文是「Version Control System」

## 優點
1. 免費、開源
Git 是由 Linux 核心的作者 Linus Torvalds 在 2005 年為了管理 Linux 核心程式碼，僅花了 10 天所開發出來的，至目前已有十幾年的歷史了。除了可免費使用外，整個 Git 的原始程式碼也可在網路上取得（當然 Git 的原始程式碼也是用 Git 在做版本控制的）。

2. 速度快、檔案體積小
如果你是使用前面提到的「複製、貼上大法」，這些備份的目錄會很佔空間。而其它大部份的版控系統大多是記錄每個版本之間的差異，而不是完整的備份整個目錄，所以整個目錄的大小就不會快速的增加。

3. 分散式系統
對我來說，這個可能是最大的優點了。在以往其它的版本控制系統，例如 CVS 或是 SVN 之類的集中式的版控系統（Centralize Version Control），都需要有一台專用的伺服器，所有的更新都需要跟這台伺服器溝通。也就是說，萬一這台伺服器壞了，或是沒有網路連線的環境，版本控制功能就沒辦法使用。

## 設定環境變數
```bash=
$ git config --global user.name "{github 名稱}"
$ git config --global user.email "{github email}"
$ git config --list
```

