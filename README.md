# 專案管理系統 Bonita Middleware
### 功能說明
為了讓專案管理系統能與Bonita串接而獨立出來的微服務。
### 架構說明
將流程圖與其配置建置於BonitaStudio，接著佈署至BonitaRuntime實現運行，並將Bonita引擎所生成的API透過go建立函式庫(Gonita)，由中間層golang調用函式來連接兩端的資料。
![image](https://user-images.githubusercontent.com/69799370/236863886-b082fdc3-6f5f-4d7b-84e4-4ab815277b1c.png)
### 系統使用框架、工具
1. 以Golang語言撰寫之Bonita函式庫(Gonita)
2. 匯入專案管理主要API之專案，進行調用
