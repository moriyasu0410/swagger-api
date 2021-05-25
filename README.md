# swagger-api

# サンプル
- https://github.com/OAI/OpenAPI-Specification/blob/main/examples/v3.0/petstore.yaml

# APIクライアント自動生成
- docker run -v ${PWD}:/local openapitools/openapi-generator-cli:v5.1.1 generate -i /local/openapi.yml -g go -o /local/out/go

# スタブサーバー起動
- docker run -v ${PWD}:/local openapitools/openapi-generator-cli:v5.1.1 generate -i /local/openapi.yml -g go-server -o /local/out/go
