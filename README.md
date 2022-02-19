![Awakening 2022](./images/awk.png)
# アプリ開発チャレンジ Awakening 2022 のドラフト案

## ■ 開発環境を構築する

Windows の場合:
- Git を winget でインストールする
- OpenJDK 11 を winget でインストールする
- VSCode を winget でインストールする

macOs の場合:
- Git を HomeBrew でインストールする
- OpenJDK 11 を HomeBrew でインストールする
- VSCode を HomeBrew でインストールする
- VSCode に Java Extension Pack をインスト―ルする
- VSCode を使って Java でコンソールに Hello World を表示する

## ■ GitHub でコードを管理する

- GitHub でアカウントを作成する
- Git コマンドチュートリアル(GCT)をやってみる
GCT でコマンドの素振りを通しで3回ほどやってみる
- GCT をフォークする

Git コマンド チュートリアル:  
https://github.com/fs5013-furi-sutao/git.command.tutorial

## ■ Web ページを表示する

- Code に Spring Boot Extension Pack をインストールする
- Gradle で Spring Boot プロジェクトを作成する
- ./gradlew bootRun コマンドを実行してブラウザに Hello World を表示する

## ■ DB に接続する

- ローカルに PostgreSQL をインストールする
- A5M2 をインストールする
- PostgreSQL に DB を作成する
- A5M2 にローカル PostgreSQL のDB を追加する
- DB に employees テーブルを作成する
- employees テーブルに従業員を3人登録する
- ブラウザにランダムで従業員を1人表示する（JPA を使う）

## ■ DB を Docker 化する

- Docker Compose で PostgreSQL コンテナを起動する
- A5M2 でコンテナのDBに接続する

## ■ テーブルを作成する

- VSCode で PlantUML を使って ER図を作成する
 氏名、年齢、性別、役職、部署を正規化してテーブル設計する
- DB にテーブルを登録する
- テストデータを作成・登録する
- １つ部署テーブルのデータを削除してみる
- テーブルを順番に drop して全テーブルを削除する

## ■ CRUD アプリを作成する

- Spring Boot で従業員の氏名、年齢、性別、部署、役職を CRUD できるアプリを作成する

## ■ REST API を作成する

- Chrome 拡張機能に Talened API Tester をインストールする
- Spring Boot の RestController を使って従業員情報 REST API を作成する
- Swagger UI を使えるようにする
- フロントエンド（クライアント側）で従業員情報の CRUD ができるようなエンドポイントを作成する

## ■ CRUD アプリのフロントエンドを作成する

- React を使って従業員管理システムのフロントエンドを作成する

## ■ デプロイする

- AWS に従業員管理システムをデプロイする

## ■ ログイン機能を追加する

- 従業員管理システムにログイン機能を追加する

## ■ CI/CD 環境を構築する

- GitHub Actions によってプッシュをきっかけに自動ビルド、デプロイができるようにする 
