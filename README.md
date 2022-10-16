# Oneweb
客製購物流程之網站系統
## 優點
- CI/CD
  - Github Action自動化部屬
- Server
  - Nginx router
  - Aliyun ECS
  - Docker Containers
- Back-End System
  - Web API
  - MVC
  - Alipay API
  - SF-Express API
- Front-End Sytstem
  - Webpack
## 系統概述
### 系統架構
![系統架構圖](https://brlin-o.github.io/oneweb/Img/System/系統架構.png)
### 使用者連線架構
![使用者連線架構圖](https://brlin-o.github.io/oneweb/Img/System/使用者連線架構.png)
### CI/CD維運模式
![CI/CD維運模式圖](https://brlin-o.github.io/oneweb/Img/System/CI-CD.png)

## 介面說明
- [oneweb/pages](https://brlin-o.github.io/oneweb/pages/)

## 後端
- 主要功能
  - 提供系統服務功能API接口
  - 符合MVC架構 及 物件導向
    - Model: 
      - User
      - Order
      - Cart
      - Product
      - Rank
    - View: 
      - User
        - Login / Regist
          - [Post]PhoneNumber
          - [Post]Alipay Login
        - Info
        - Edit
      - Order
        - Info
        - Edit
    - Controller
      - User
      - Order
      - Product
      - Pay
  - 接入開放平台
    - 支付寶API
      - 會員產品
        - 登入
        - 用戶基本資訊
      - 支付產品
        - 電腦網站支付
    - 順風開放平台接口
      - 速運API