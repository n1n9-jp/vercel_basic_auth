# vercel_basic_auth

## 目的

VercelでBasic認証を実現する。

## 主な特徴
  - @vercel/edge依存性使用
  - middleware.tsでEdge Middlewareを実装

## 環境変数の設定
Project Settings -> Environment Variablesにて以下の変数を設定する
- BASIC_AUTH_USER
- BASIC_AUTH_PASSWORD
