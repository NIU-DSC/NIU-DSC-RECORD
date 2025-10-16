# 每日英文新聞
## [每日英文新聞傳送](./每日英文新聞傳送.json)
### 主工作流 - 功能與流程
1. 網路請求
2. XML to JSON (方便後面節點讀取)
3. 程式碼節點 - 保留連結和標題
4. Sub Workflow
5. AI Agent 彙整資訊
6. 傳出

## [[Sub] Check data not exist](./[Sub]%20Check%20data%20not%20exist.json)
### 副工作流 - 功能與流程
1. 檢查是否存在於資料庫
   - 若存在於資料庫，就移除
2. 插入新的新聞到資料庫中，避免重複新聞