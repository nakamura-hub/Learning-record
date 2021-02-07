# プロジェクト概要

## 概要
``学習時間を管理するアプリ``

##  仕様

### モデル
- User
  - name: string
  - email: string
  - password_digest: string
- Task
  - title: string
  - discription: text
  - user_id: references

### 機能
- ユーザー
  - 新規登録
  - ログイン
  - ログアウト
  - 詳細
  - 編集
  - 退会
- タスク
  - 登録
  - 詳細確認
    - 記録
  - 一覧表示
  - 編集
  - 削除

### 画面
- HOME画面
- ユーザー(ログイン有無問わず)
  - 一覧画面
  - 詳細画面
  - プロフィール編集画面
  ※ ログインユーザーのみ
- タスク
  - 登録画面
  - 編集画面
  - 詳細確認
    - 記録
  - 一覧表示

## 技術

### フロントエンド
  - 未定

### バックエンド
- Ruby and Rails
  - Devise
  - RSpec
### その他
- テストフレームワーク(Jest)


### 備考
- 

- 
