# アプリケーションのディレクトリ構成

- src
  - domain（ビジネスロジックとドメインモデル）
    - models（ドメインモデル）
    - value-objects（値オブジェクト）
  - application（ドメインを使用しユースケースを実現する）
    - usecases（ユースケースの実現を行う）
  - infrastructure
    - repository（データの永続化処理）
    - api（外部APIとの連携）
  - presentation（ユーザーインタフェースを担当）
    - graphql（GraphqlのAPIを構築する）
