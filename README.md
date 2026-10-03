# middleware-app-practice

## 概要
COACHTECH 教材 Tutorial 10-2「ミドルウェア ハンズオン演習」で作成した成果物です。
管理者ページを管理者にのみ表示
それ以外の人が管理者ページを見ようとログインしても「403エラー」表示

## 使用技術
- PHP 8.x
- Laravel 10.x
- カスタムミドルウェア
- Laravel Fortify（認証）

## 学んだこと
- カーネル、ミドルウェア登録、ミドルウェア適用したルーティング記載

## 動作確認
- http://localhost/ にアクセス
- それぞれでログイン
  管理者: admin@example.com / password 管理者ページ表示されることを確認
  一般: user@example.com / password　「403権限ありません」表示されることを確認
