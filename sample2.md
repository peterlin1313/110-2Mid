# 第二大題 
## (a) 小題
### 1. 利害人關係表
請在這邊開始作答
|  利害關係人   | 目標  |
|----|----|
|會員|註冊帳號|
|      |將資訊送給業務員|
|      |修改部分會員資料|
|      |使用面部辨識系統進入場地|
|業務員|註冊帳號|
|      |發送註冊連結給會員|
|      |協助註冊業務員|
|      |修改部分會員資料|
|      |使用面部辨識系統進入場地|
|系統管理員|協助註冊業務員|
|      |管理系統|
|      |修改資料|
### 2. 事件表
請在這邊開始作答
# 會員之事件表
|  事件名稱   | 使用案例名稱  |
|----|----|
|註冊帳號|系統註冊與修改作業|
|修改部分資料|     |
|使用面部辨識進入場地|面部辨識資料比對作業|
# 業務員之事件表
|  事件名稱   | 使用案例名稱  |
|----|----|
|註冊帳號|業務員系統註冊與修改作業|
|修改部分資料|     |
|使用面部辨識進入場地|面部辨識資料比對作業|
|取得會員註冊連結|提供註冊作業|
|協助業務員註冊|     |
# 系統管理員之事件表
|  事件名稱   | 使用案例名稱  |
|----|----|
|修改資料|系統管理作業|
|管理系統設定|     |
|協助業務員註冊|提供註冊作業|
|取得業務員註冊連結|     |
# 城集行銷公司會員系統之事件表
|  事件名稱   | 使用案例名稱  |
|----|----|
|預設系統管理者於資料庫|系統設定功能|
|提供資料修改|系統註冊與修改功能|
|提供會員進行註冊|     |
|使用面部辨識系統進行辨別|系統辨識功能|
# 面部辨識系統之事件表
|  事件名稱   | 使用案例名稱  |
|----|----|
|比對使用者資料|資料比對作業|
|透過電信提醒會員付費|付費提醒作業|
## (c) 小題
### 1. 寫出使用案例
請在這邊開始作答(若需要作圖補充，需配合sample1.drawio自己增加標籤-sheet，以課本中規則進行標註)
|||
|---|---|
|使用案例名稱|系統註冊與修改作業|
|使用案例描述|使使用者能夠加入並註冊成為會員|
|主要參與者|使用者 業務員|
|立害關係人與目標|使用者:取得註冊連結並註冊成為會員 業務員:取得註冊連結並透過line發送給欲註冊成為會員的使用者|
|前置條件|使用者取得業務員發送的註冊連結|
|後置條件|使用者輸入資料|
|主要成功情節|使用者成功成為會員|
|例外情節|無|
|其他需求|無|


|||
|---|---|
|使用案例名稱|系統管理作業|
|使用案例描述|系統管理人員能夠管理系統|
|主要參與者|系統管理員|
|立害關係人與目標|系統管理員:能夠管理系統|
|前置條件|系統灌好時預設系統管理員於資料庫中|
|後置條件|系統管理員執行系統管理|
|主要成功情節|管理員管理系統|
|例外情節|無|
|其他需求|無|


|||
|---|---|
|使用案例名稱|面部辨識作業|
|使用案例描述|透過面部辨識功能與資料中的照片比對判定是否為會員|
|主要參與者|面部辨識系統 會員 華鐘電信 騎華銀行|
|立害關係人與目標|面部辨識系統:判別是否為會員 會員:提供面部資料 華鐘電信:收到辨識系統提示會員繳費的訊息並發送給會員 騎華銀行:如會員於期限內未能付費將通知面部辨識系統|
|前置條件|會員提供資料|
|後置條件|會員付費情況|
|主要成功情節|成功促成會員付費|
|例外情節|無|
|其他需求|無|