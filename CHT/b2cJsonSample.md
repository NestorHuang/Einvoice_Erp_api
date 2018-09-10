B2C存證發票範本

```
{
     "CompanyID":"89430377",
     "InvoiceID":"AA12345678",
     "InvoiceDateTime":"2016-10-27T16:27:34",
     "InvoiceFor":"C",
     "BuyerID":"0000000000",
     "BuyerName":"Nestor Huang",
     "BuyerAddress":"高雄市鳳山區光遠路226號B1",
     "BuyerTelNo":"0912345678",
     "BuyerEmail":"nestor@systemlead.com",
     "RelateNumber":"OD2017032802",
     "PrintMark":"N",
     "RandomNumber":"3716",
     "SalesAmount":5500,
     "TaxType":"1",
     "TaxAmount":0,
     "TotalAmount":5500,
     "Details":[
         {
             "DetailID":"001",
             "ProductID":"P1234",
             "ProductName":"產品名稱",
             "Quantity":5.0,
             "UnitPrice":100.0,
             "SubTotal":500.0
         },
         {
             "DetailID":"002",
             "ProductID":"P2345",
             "ProductName":"長度256個字",
             "Quantity":2.0,
             "UnitPrice":500.0,
             "SubTotal":1000.0
         },
         {
             "DetailID":"003",
             "ProductID":"P3456",
             "ProductName":"明細編號3碼",
             "Quantity":4.0,
             "UnitPrice":1000.0,
             "SubTotal":4000.0,
             "Remark":"貨品缺1件候補"
         }]
}
```

回傳結果範例：

```
[
  {
    "InvoiceID":"CA89430015",
    "InvoiceDateTime":"2017-06-12T12:34:56",
    "AuthCode":"113B2C2E-81E3-41B5-B77F-656598B8BAEF"
  },
  {
    "InvoiceID":"CA89430016",
    "InvoiceDateTime":"2017-06-12T12:34:34",,
    "Message":,"Append Inovice Error!!"
  },
  {
    "InvoiceID":"CA89430017",
    "InvoiceDateTime":"2017-06-12T12:34:34",,
    "Message":,"簽章驗證錯誤"  
  }
]
```


