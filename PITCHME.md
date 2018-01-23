
@title[Agenda]

## Nablarch

#### ・Web Application
#### ・Web Service(REST)
#### ・Batch
#### ・Workflow

---
@title[全体像]
#### Nablarchアプリケーションフレームワークの全体像

![ALT](https://nablarch.github.io/docs/5u9/doc/_images/framework.png)

---
## ・Web Application

---
@title[ウェブアプリケーションの構成]
#### ウェブアプリケーションの構成
![ALT](https://nablarch.github.io/docs/5u9/doc/_images/application_structure1.png)
#### ・Nablarchサーブレットコンテキスト初期化リスナ (NablarchServletContextListener)
#### ・Webフロントコントローラ (WebFrontController)
---
@title[ウェブアプリケーションの処理の流れ]
#### ウェブアプリケーションの処理の流れ
![ALT](https://nablarch.github.io/docs/5u9/doc/_images/web-design.png)
#### ・WebFrontController
#### ・handler queue
<a href="https://nablarch.github.io/docs/5u9/doc/application_framework/application_framework/web/architecture.html" target="_blank">ここ</a>

---
@title[アプリケーションの責務配置]
#### アプリケーションの責務配置
![ALT](https://nablarch.github.io/docs/5u9/doc/_images/application_design.png)
#### ・アクションクラス(action class)
#### ・フォームクラス(form class)
#### ・エンティティクラス(entity class)
<a href="https://nablarch.github.io/docs/5u9/doc/application_framework/application_framework/web/application_design.html" target="_blank">ここ</a>


---
@title[各画面の実装1]
#### 各画面の実装
#### 2.3.1. 登録機能の作成(ハンズオン形式)
#### 2.3.2. 検索機能の作成
#### 2.3.3. 更新機能の作成
#### 2.3.4. 削除機能の作成

---
@title[各画面の実装2]

#### 2.3.5. アップロードを用いた一括登録機能の作成
#### 2.3.6. ファイルダウンロード機能の作成
#### 2.3.7. ポップアップ画面の作成
#### 2.3.8. 一括更新機能の作成
<a href="https://nablarch.github.io/docs/5u9/doc/application_framework/application_framework/web/index.html" target="_blank">ここ</a>


---
@title[Web Service(REST)]
## ・Web Service(REST)

---
####  RESTfulウェブサービス
<a href="https://github.com/milstoney/nablarch-example-rest" target="_blank">ここ</a>
####   HTTPメッセージング
<a href="https://github.com/milstoney/nablarch-example-http-messaging" target="_blank">ここ</a>
---

@title[Batch1]
## ・Batch

---
@title[Batch2]
####  JSR352に準拠したバッチアプリケーション
<a href="https://github.com/milstoney/nablarch-example-batch-ee" target="_blank">ここ</a>
####   Nablarchバッチアプリケーション

<a href="https://github.com/milstoney/nablarch-example-batch" target="_blank">ここ</a>
---

@title[Workflow]
## ・Workflow

<a href="https://github.com/milstoney/nablarch-example-workflow" target="_blank">ここ</a>

---

@title[次回]

#### 掘り下げた内容もうちょっと書こうか
#### テスティングフレームワークとか