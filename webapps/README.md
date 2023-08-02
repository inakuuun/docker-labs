## Webサーバの構築  
- 参考GitHub  
https://github.com/docker/labs/blob/master/beginner/chapters/webapps.md
- pythonを使ってWebアプリを作成

## イメージのビルド  
- webappsという名前をつけてイメージをビルド  
`docker build . --tag webapps`

## コンテナの起動  
- ポートを指定して実行  
`docker run -p 8888:5000 webapps`

