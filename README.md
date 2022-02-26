![Awakening 2022](./images/awking.png)
# アプリ開発チャレンジ Awakening 2022 のドラフト案

自走できるエンジニアになるために

## Awakening とは

Awakening（アウェイクニング）とは、翻訳すると「目覚め」のこと。

Awakeninng は、アプリ開発未経験、またはそれに近い人向けのアプリ開発チャレンジプログラム。

次々に突き付けられるミッションをこなして、アプリの完成を目指す。

アプリの完成を達成するまでに、考える力、問題解決能力、Web アプリの開発に必要となる数多くの知識を身に付けることを目的としている。

## ミッション一覧

### ■ 開発環境を構築する

Windows の場合:
- Windows Terminal を winget でインストールする
- Git を winget でインストールする
- Windows Terminal で Git Bash を使えるようにする
- OpenJDK 11 を winget でインストールする
- VSCode を winget でインストールする

macOs の場合:
- Git を HomeBrew でインストールする
- OpenJDK 11 を HomeBrew でインストールする
- VSCode を HomeBrew でインストールする
- VSCode に Java Extension Pack をインスト―ルする
- VSCode を使って Java でコンソールに Hello World を表示する

### ■ GitHub でコードを管理する

- GitHub でアカウントを作成する
- Git コマンドチュートリアル(GCT)をやってみる
GCT でコマンドの素振りを通しで3回ほどやってみる
- GCT をフォークする

Git コマンド チュートリアル:  
https://github.com/fs5013-furi-sutao/git.command.tutorial

### ■ Web ページを表示する

- VSCode に Spring Boot Extension Pack をインストールする
- Gradle で Spring Boot プロジェクトを作成する
- ./gradlew bootRun コマンドを実行してブラウザに Hello World を表示する

### ■ DB に接続する

- ローカルに PostgreSQL をインストールする
- A5M2 をインストールする
- PostgreSQL に DB を作成する
- A5M2 にローカル PostgreSQL のDB を追加する
- DB に employees テーブルを作成する
- employees テーブルに従業員を3人登録する
- ブラウザにランダムで従業員を1人表示する（Spring Data JPA を使う）

### ■ DB を Docker 化する

- Docker Compose で PostgreSQL コンテナを起動する
- A5M2 でコンテナのDBに接続する

### ■ テーブルを作成する

- VSCode で PlantUML を使って ER図を作成する
 氏名、年齢、性別、役職、部署を正規化してテーブル設計する
- DB にテーブルを登録する
- テストデータを作成・登録する
- １つ部署テーブルのデータを削除してみる
- テーブルを順番に drop して全テーブルを削除する

### ■ CRUD アプリを作成する

- 従業員の氏名、年齢、性別、部署、役職を CRUD できるアプリの要望・仕様を明確にする
- Spring Boot で従業員管理システムを作成する
- VSCode の Remote Container 拡張機能でコンテナ開発環境を構築する

### ■ REST API を作成する

- Chrome 拡張機能に Talened API Tester をインストールする
- Spring Boot の RestController を使って従業員情報 REST API を作成する
- Swagger UI を使えるようにする
- フロントエンド（クライアント側）で従業員情報の CRUD ができるようなエンドポイントを作成する

### ■ CRUD アプリのフロントエンドを作成する

- React を使って従業員管理システムのフロントエンドを作成する

### ■ デプロイする

- AWS に従業員管理システムをデプロイする

### ■ ログイン機能を追加する

- 従業員管理システムにログイン機能を追加する

### ■ CI/CD 環境を構築する

- GitHub Actions によってプッシュをきっかけに自動ビルド、デプロイができるようにする 
