### 查詢授權e首發票下載之發票字軌與期號 

```
POST api/Inquire/GetInvoiceIDList
```
[傳送格式說明](https://slproject.gitbook.io/sl-einv-project/cht/getinvoiceidlist)

### 上傳空白發票號
```
POST api/Append/TrackBlank
```
[傳送格式說明](https://slproject.gitbook.io/sl-einv-project/cht/trackblank)

### 更新空白發票號
```
POST api/Update/SetBlankInvoiceID
```
[傳送格式說明](https://slproject.gitbook.io/sl-einv-project/cht/setblankinvoice)

### 單筆訂單上傳(即時開立發票)
```
POST api/Append/Order
```
[傳送格式說明](https://slproject.gitbook.io/sl-einv-project/cht/receipt)

### 多筆發票批次上傳
```
POST api/Append/Invoices
```
[傳送格式說明](https://slproject.gitbook.io/sl-einv-project/cht/receipt)

### 多筆發票批次更新
```
POST api/Update/Invoices

```
<font color="red">
注意: 
1.發票號為鍵值，除發票號與發票開立日期外其餘欄位皆可異動
2.發票若已啟動上傳將無法更新發票
</font>
[傳送格式說明](https://slproject.gitbook.io/sl-einv-project/cht/receipt)

### 新增發票並列印
```
POST api/Append/PrintInvoices
```
[傳送格式說明](https://slproject.gitbook.io/sl-einv-project/cht/receipt)

### 查詢多筆發票最新處理狀態
```
POST api/Inquire/GetInvoicesStatus
```
[傳送格式說明](https://slproject.gitbook.io/sl-einv-project/cht/getinvoicesstatus)

### 查詢多筆發票上傳狀態
```
POST api/Inquire/GetInvoicesAppendStatus
```
[傳送格式說明](https://slproject.gitbook.io/sl-einv-project/cht/getinvoicesappendstatus)

### 批次作廢發票
```
POST api/Update/CancelInvoices
```
[傳送格式說明](https://slproject.gitbook.io/sl-einv-project/cht/cancelinvoice)

### 批次作廢空白發票(發票號跳號用)
```
POST api/Append/BlankCancel
```
[傳送格式說明](https://slproject.gitbook.io/sl-einv-project/cht/cancelinvoice)
### 發票折讓
```
POST api/Update/AllowanceInvoice
```
[傳送格式說明](https://slproject.gitbook.io/sl-einv-project/cht/insertallowance)




