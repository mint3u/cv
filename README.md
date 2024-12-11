# 業務経歴

## 基本情報

<https://www.wantedly.com/id/mint3u>

早川 優(yu hayakawa), 1993年生まれ

## 概要・大切にしていること

フリーランスのWebエンジニアとして活動しています。渋谷区在住です。

直近の業務では、主にバックエンドエンジニアとして開発を行っています(GolangやDocker、AWS)。

仕事の上では、案件を前に進めることを一番重視しています。外部ベンダーやクライアントとの調整の経験を積んでおり、開発力および要件の調整力を生かして仕事を前に進めることが強みです。

仕事で関わる他者への尊重は大事にしています。チャットやコードレビューの文章を雑に記述して、他者が委縮してしまうような事態は避けます。

## 業務経歴詳細

新しい順に記載します。

### 勤怠管理SaaSの開発(2021年-2024年)

**概要:** 勤怠管理SaaSの新規マイクロサービスの構築および改修を、主にバックエンドのエンジニアとして担当。

担当業務詳細は以下の通り。

- 開発言語はGo(gRPC/GORM2.0)。RDBはAurora(MySQL)。環境はAWS。GitHubを使用したチーム開発
- EKSを使用したKubernetes環境での開発。Helmを用いたマニフェスト管理
- SQS, SNSを用いたpub/subの構築・実装
- Github ActionsでのCI/CDの構築。TerraformでのAWSリソースのコード化
- GraphDBを使ったアプリの実装(AWS Neptune/Gremlin)
- Typescriptでの開発(Next.js/Prisma/zod)

**発揮したバリュー:** モダンな技術を好んで使う風土の中で、要件調整を行いつつバックエンドのメインエンジニアとして開発面で貢献した。とくに開発のスピード面で高い評価を頂いた。既存の仕様が多く存在する中で、仕様書やコードを読み解きつつキャッチアップを行った。

---

### 決済アプリの開発(2019年-2021年)

**概要:** 決済アプリのバックエンドにて、新規マイクロサービスの構築および既存マイクロサービスの改修を、要件の調整・設計・実装・テストまで担当。

担当業務詳細は以下の通り。

- 開発言語はGo(gin/GORM)とDocker。RDBはRDS(PostgreSQL)。GitHubを使用したチーム開発
- AWSの各サービス(S3/ECS/ECR/SQS/RDS/ElastiCache Redis/KMS/CloudWatch Logs/パラメータストア/CodeDeploy)を用いた各マイクロサービスの構築・開発。またTerraformでのAWSリソースのコード化
- CircleCIでのCI/CDの構築。DatadogでのログおよびAPMの設定

**発揮したバリュー:** RedisやTerraform、CircleCIの業務での使用は初であり、また既存のコードが多く解読に苦労したが、キャッチアップ力を発揮しスピード感のある開発で貢献した。あらかじめ要件がつめきられていない部分については、クライアントや外部ベンダーとの調整を進め、プロジェクト進行が全体最適となるようにハンドリングを行った。

---

### 業務改善プラットフォームの新規構築(2019年)

**概要:** BtoBの新規システムのサーバサイドAPI設計及び開発を担当。

担当業務詳細は以下の通り。

- 開発言語はGo。RDBはMySQL。設計にswagger、ビルドツールとしてMakefileを使用。環境はAWS。GitHubを使用したチーム開発
- grpc-gatewayを用いたRESTからgRPCへの変換処理の開発
- ファイル処理を担当するマイクロサービスの実装を担当。S3のpresignURLを使用したファイルアップロード実装

**発揮したバリュー:** GoやgRPCの業務での使用は初、かつクリーンアーキテクチャでの開発を徹底する環境であり苦労したが、現場のソースコード及び公式ドキュメントを参考に短期間でキャッチアップ。

---

### ECサイトマイクロサービス化(2018年-2019年)

**概要:** Javaで開発していた大規模でモノリシックなECサイトのマイクロサービス化。リプレース前のコードの総ステップ数は約10万行。

担当業務詳細は以下の通り。

- 開発言語はPHP(7.2)、DIコンテナとしてPimpleを使用。Dockerでのアプリコンテナ化を実施
- 主にフロントエンドのリプレースを開発リーダを担当
- 開発をメインに、顧客との要件調整、設計、テストまでを担当

**発揮したバリュー:** PHP、Dockerいずれも業務での使用は初であったが、公式ドキュメント等を使用して短期間で技術にキャッチアップ。開発量に比べ短納期なプロジェクトであったが、開発リーダとしてチームメンバーのタスク管理・フォローアップ、及び自身のコーディングスキルを発揮し、納期通りの納品を達成。

---

### ECサイト決済サービスの改修(2018年)

**概要:** 大規模ECサイトの決済サービスの改修案件を複数並行して進行。

担当業務詳細は以下の通り。

- 開発言語はJava8、RDBはAurora(MySQL互換)。環境はAWS
- 複数のサービス改修案件の顧客調整及びリードを担当。本番作業(Linuxサーバ操作)についても担当
- 見積書、要件定義書、設計書、及びテスト仕様書のドキュメント作成またはレビューを担当
- オフショアが担当するプログラミング開発内容のレビュー及び修正を担当

**発揮したバリュー:** 各案件は比較的小規模(20人日から30人日程度)でありながらも、案件の同時進行数が多い中、チームメンバーのタスク管理等を通じ、全ての担当案件について予定期日通りのリリースを達成。顧客及び開発担当(オフショア)との調整を行う中で、案件を前に進めるためのコミュニケーション能力を向上しつつ発揮。

---

### ECサイトの開発・運用(2016年-2018年)

**概要:** 大規模ECサイトの複数の改修の設計・開発および顧客調整。

担当業務詳細は以下の通り。

- 開発言語はJava8およびJavaScript(ES5/jQuery)、RDBはRDS(PostgreSQL)。環境はAWS。SVNを使用したチーム開発
- フロントエンド、サーバサイド共に設計、開発、及びテストを担当。顧客調整についても担当
- ECサイトの多言語化対応やAWSインフラの移行等、大規模な案件にも開発を含む工程で参画。本番作業(Linuxサーバ操作)についても担当
- DB設計/API設計/ファイルアップロード/多言語化対応/DBデータ移行等、様々な設計・実装を担当

**発揮したバリュー:** AWSを本格的に利用しつつプログラミングを行うことは初であったが、公式ドキュメント等のネット上の情報を参考にして、顧客の要望及び発生した問題に対応。AWSインフラの移行に伴う大規模なサイト改修の案件についてもリリースまで参画。主にプログラム改修の面で貢献。

以上
