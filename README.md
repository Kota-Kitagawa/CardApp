## 概要
タロットカードによる占いアプリ

### 開発環境
- Next.js
- MySQL
- Nginx
- Docker
- Gemini (free planのAPIを使用)

### 起動説明

1. Linuxの場合、以下のコマンドでマシンのIPアドレスを確認する
    ```
    hostname -I
    ```

2. 下記コマンドでDockerコンテナを起動する
    ```
    docker-compose build
    docker-compose up -d
    ```

3. ブラウザで `https://<マシンのIPアドレス>` にアクセスする

> このSSL証明書は自己署名証明書<br>
> ブラウザで警告が表示されますが、「詳細設定」→「リンクにアクセス」などを選択すると表示できる
