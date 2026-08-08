# Ritsuki | PHP / Laravel × Testing

PHP / Laravelを中心に、Webアプリケーション開発を学習・実践しています。  
テスト観点を活かし、仕様確認・動作検証・既存機能の小規模な改善を、変更影響を確認しながら進めることを重視しています。

## About

Laravel APIとVue.jsを組み合わせた個人開発を通じて、認証・認可、CRUD、バリデーション、DB操作、画面連携を実装しています。  
結合テストの設計・確認に加え、PHPUnitのFeature TestとPlaywrightによるブラウザテストを使い、正常系だけでなく、認証・認可、入力エラー、API失敗時の画面挙動も確認しています。  
現在は、既存コードの処理フローを読み解き、テストを根拠に安全に小さな改善を積み重ねる力を深めています。

## Core Skills

### Backend

- PHP / Laravel
  - REST API、CRUD
  - FormRequestによるバリデーション
  - API Resourceによるレスポンス整形
  - Eloquent、Migration、Relation
  - Laravel SanctumによるAPI認証
  - Role / Policyによる認可
  - CSV出力
- MySQL

### Testing

- Integration Testing
  - 画面・API・DBなどのつながりを対象とした、入出力・状態・データ反映の確認
  - 正常系・異常系・権限・前提条件を整理したテストケース設計
- PHPUnit Feature Test
  - 認証・認可、CRUD、バリデーション、DB更新の確認
- Playwright ブラウザテスト
  - 画面遷移、主要操作、エラー表示の回帰確認

### Frontend

- Vue.js 3 / Composition API
- JavaScript / HTML / CSS
- Pinia
- Axios
- Vue Router

### Development Environment

- Git / GitHub
- Docker / Laravel Sail
- WSL2

## Featured Project

### [ウタエル](https://github.com/Ritsuki-Irabu/utaeru)

カラオケ直前に音を出さず、BPMに合わせた視覚フィードバックでリズムを確認するPWAです。  
Laravel API + Vue.js SPA構成で、曲マスタとマイリストの管理、認証・認可、CSV出力、テストを実装しています。

主な実装：

- 曲マスタとマイリストのREST API CRUD
- FormRequestによる入力検証とAPI Resourceによるレスポンス整形
- Laravel Sanctumによる認証、Role / Policyによる操作権限の制御
- EloquentのリレーションとMigrationによるデータ設計
- Vue.js、Pinia、Axios、Vue RouterによるSPA画面と状態管理
- PHPUnit Feature Testと、認証・認可・CRUD・エラー表示を確認するPlaywrightブラウザテスト

主な技術：PHP / Laravel / Vue.js / MySQL / Docker / PHPUnit / Playwright

[開発振り返りレポート](https://github.com/Ritsuki-Irabu/utaeru/blob/develop/docs/development-review.md)では、設計、Issue単位の開発プロセス、実装時の課題と改善点をまとめています。

## Other Projects

### [Receptor](https://github.com/Ritsuki-Irabu/receptor)

思考ログをAIで分析し、思考傾向を可視化するWebアプリケーションです。  
Next.js / TypeScript / Auth.js / Prisma / PostgreSQLを使用し、認証付きAPI、ログ保存、Gemini API連携、スコア表示を実装しています。

### [KPI管理API](https://github.com/Ritsuki-Irabu/kpi-api)

ユーザー、KGI、KPI、日々の進捗記録を階層的に管理するREST APIです。  
Java / Spring Boot / Spring Data JPA / H2を使用し、Entityのリレーション、Request / Response DTOの分離、データの作成・取得・削除APIを実装しています。  
[実装コード（feature/apiブランチ）](https://github.com/Ritsuki-Irabu/kpi-api/tree/feature/api)

## Learning & Engineering Notes

### [Learning Lab](https://github.com/Ritsuki-Irabu/learning-lab)

学習内容だけでなく、実装時に起きた問題、原因、解決方法、動作確認済みのコードを、再利用できる技術資産として継続的に整理しています。

主なテーマ：

- Laravel / API / Eloquent
- Testing / Integration Testing / Playwright
- Docker / WSL2
- Git / GitHub
- Java / Spring Boot
- Next.js / Prisma / Auth.js

## Currently Focusing On

- Laravel既存コードの読解と、画面・API・DB間の変更影響分析
- Integration Testingによる機能間・データ間の整合性確認と、PHPUnit Feature Test・Playwrightによる回帰確認
- 認証・認可、Validation、CRUD周辺の不具合調査と小規模改修
- Webアプリケーションの責務分離と保守しやすい設計
