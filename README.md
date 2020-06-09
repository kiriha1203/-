# README

# Job_Searcher

# 概要

求人支援サービスです。
企業側とユーザーがチャット形式で連絡を取れることで気軽にアポイントを取れます。
また、企業側同士でも連絡が取れることで、新たな協力できることを目的としています。

# コンセプト

リクルート等の求人サイトを参考に制作。

# バージョン

Ruby 2.6.5
Ruby On Rails 5.2.4
PostgreSQL 12.2

# 使用予定Gem
* devise
* devise-l18n
* letter_opener_webF
* dotenv-rails
* pry-rails
* better_errors
* ransak
* kaminari
* acts-as-taggable-on
* rspec_rails
* factory_bot_rails
* faker
* webdrivers
* capybara
* database-cleaner

# 機能一覧
* ユーザー機能
    * サインイン機能
    * サインアップ機能
    * ユーザー一覧表示(adminのみ)
    * ユーザー情報詳細表示機能
    * ユーザー情報更新機能
    * ユーザー削除機能（退会）
    * ユーザー削除機能(adminのみ)
    
* カンパニー機能
    * サインイン機能
    * サインアップ機能
    * カンパニー一覧表示(adminのみ)
    * カンパ二ー情報詳細表示機能
    * カンパニー情報更新機能
    * カンパニー削除機能（退会）
    * カンパニー削除機能(adminのみ)
    
* ブログ機能(companyが作成できる)
    * ブログ作成機能
    * ブログ一覧表示
    * ブログ情報詳細表示
    * ブログ更新機能
    * ブログ削除機能

* チャット機能
    * company間でチャット機能ができる
    * user_company間でチャット機能ができる
    * チャット作成機能
    * チャット削除機能
    
* タグ機能
    * companyにITや製造業などのタグを付けれる。
    
# カタログ設計・テーブル定義
[リンク](https://docs.google.com/spreadsheets/d/1iq2n8-OpRezVTRlMBXwJWbJZxLxpaJH1pFNUisYhAcc/edit?usp=sharing)

# ER図
[リンク](https://drive.google.com/file/d/1u1FAe5Jabs9Z_OAAqu87Z4OwONGtIkEP/view?usp=sharing)

# 画面遷移図
[リンク](https://drive.google.com/file/d/1_y-Ar_xEQ4dSnEHaQw2AQCxsuBvj6GG9/view?usp=sharing)

# ワイヤーフレーム
[リンク](https://drive.google.com/file/d/1Siv6DOOUqoHAbZo_BMsOyTGMz89O71DX/view?usp=sharing)