# Amazon Kinesis

即時收集、處理和分析影片與資料串流

官網連結：[https://aws.amazon.com/tw/kinesis/](https://aws.amazon.com/tw/kinesis/)

* Kinesis Video Streams：擷取、處理和存放影片串流
* Kinesis Data Streams：擷取、處理和存放資料串流
* Kinesis Data Firehose：將資料串流載入 AWS 資料存放區
* Kinesis Data Analytics：使用標準 SQL 分析資料串流

## Amazon Kinesis Data Firehose

準備即時資料串流並載入資料存放區和分析工具

官網連結：[https://aws.amazon.com/tw/kinesis/data-firehose/](https://aws.amazon.com/tw/kinesis/data-firehose/)

運作方式：![](https://d1.awsstatic.com/diagrams/product-page-diagrams/diagram-how-it-works-kinesis-data-firehose-splunk.977c40fd40f3f5f5ba9c2491b1e57620917292e7.png)使用案例１：物聯網分析

* Kinesis Data Firehose 可以持續從連線裝置擷取資料。
* Kinesis Data Firehose 將資料載入 S3 和 Redshift，讓客戶能以近乎即時的速度存取metrics, insights 和 dashboards。

使用案例２：日誌分析

* 安裝和設定 Amazon Kinesis 代理器，自動查看應用程式和伺服器日誌檔，並將資料傳送到 Kinesis Data Firehose。
* Kinesis Data Firehose 可持續將日誌資料串流到 Elasticsearch，並透過 Kibana 視覺化資料並進行分析。



