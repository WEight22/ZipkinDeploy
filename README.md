# ZipkinDeploy

EC2 建議中等量級, 因為有開到 ElasticSearch
```
docker-compose up -d
```

開放 80 port 對使用者網段  

開放 9411 對監控環境網段  

參考資料  
https://github.com/openzipkin/zipkin  
  
Spring Cloud 已整合好 暫時先不作調整或整合
