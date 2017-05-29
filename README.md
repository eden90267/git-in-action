# Git

## 什麼是Git?

### GIT的功能

- 分散式多人專案合作管理系統
- 程式的版本控管
- 資料的復原機制
- 查詢程式的修改記錄

### GIT的優勢

- 非線性開發模式
- 相容於現有OS
- 有效率的處理大型專案
- 資料復原機制
- 歷史紀錄保護

### Github

是一個基於Git的程式碼管理服務商。除了允許個人和組織建立儲存庫之外，也提供了一些方便社會化軟體開發的功能，包括允許用戶追蹤其他用戶、組織、以及儲存庫的動態。亦可對程式碼的改動和bug提出評論。GitHub也提供了圖表功能，用於顯示開發者們在儲存庫上的工作進度以及軟體開發的活躍程度。

簡單說，Github就是程式開發者的社交平台。

## 使用SSH與GITHUB做連線

1. 產生SSH的金鑰：

    `$ ssh-keygen -t rsa -b 4096 -C "youEmail@example.com"`

2. 測試連線

    `$ ssh -T git@github.com`