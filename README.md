# go_sample_api

作成
curl -i -X POST -H "Content-Type: application/json"  -d '{"content":"My first post","author":"Sau Sheong"}' http://127.0.0.1:8080/post/

検索
curl -i -X GET http://127.0.0.1:8080/post/1

更新
curl -i -X PUT -H "Content-Type: application/json"  -d '{"content":"Updated post","author":"Sau Sheong"}' http://127.0.0.1:8080/post/1

削除
curl -i -X DELETE http://127.0.0.1:8080/post/1