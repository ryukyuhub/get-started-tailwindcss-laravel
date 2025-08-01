# Tailwind CSS を Laravel で始めてみよう！

## 始めかた
1. このリポジトリをクローンする
    ```bash
    git clone
    ```
1. このプロジェクトディレクトリ（リポジトリ）内で 依存パッケージをインストールする
    ```bash
    cd
    ```
    ```bash
    composer install
    ```
    ```bash
    npm install
    ```
1. .env を作る
    ```bash
    cp .env.example .env
    ```
    ```bash
    php artisan key:generate
    ```
2. ビルドもしくはホットリロード状態にする
    - ビルドの場合（本番モード）
      ```bash
      npm run build
      ```
    - ホットリロードの場合（開発モード）
      ```bash
      npm run dev
      ```
3. 開発サーバー起動させる
    ```bash
    php artisan serve
    ```
4. ブラウザからアクセスして確認する
    ```bash
    http://localhost:8000
    ```

