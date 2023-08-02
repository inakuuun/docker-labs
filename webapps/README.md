## イメージのビルド  
- webappsという名前をつけてイメージをビルド  
`docker build . --tag webapps`

## コンテナの起動  
- ポートを指定して実行  
`docker run -p 8888:5000 webapps`

