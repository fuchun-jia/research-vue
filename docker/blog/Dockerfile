# ビルド環境
FROM node:lts
# コンテナ内の作業ディレクトリを設定
WORKDIR /var/www/blog

# アプリケーションのソースコードをコンテナ内にコピー
COPY ./blog /var/www/blog

# アプリケーションの依存関係をインストール
RUN npm install

# Vue アプリケーションをビルド
RUN npm run build
    