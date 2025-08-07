# 技術スタックまとめ（初心者向け）

## 🧱 ライブラリ／フレームワーク
- **React**：UIを構築するためのJSライブラリ。アプリの「骨組み」
- **Next.js**：Reactベースのフルスタックフレームワーク。動的ルーティングやSSRが可能
- **Remix**：Web標準を重視したReactフレームワーク
- **TypeScript**：型安全なJavaScript。書くときのルール・ガードレール

## 🚀 ホスティング・デプロイ
- **Vercel**：Next.jsに特化したホスティングサービス
- **Netlify**：JAMstack特化。静的サイトやSPAに強い
- **Railway**：シンプルな全体ホスティング（バックエンドもOK）
- **OpenNext**：Next.jsをAWSでセルフホストするための中間ツール

## 🗄 データベース
- **Supabase**：Firebase代替のBaaS。PostgreSQLベース
- **Neon**：サーバーレスPostgreSQL
- **Cloudflare D1**：エッジで動くSQLite
- **PostgreSQL**：本格的なリレーショナルDB

## 📦 ストレージ
- **Amazon S3／Cloudflare R2／Supabase Storage**  
　→ 画像・PDFなど重めファイルを保管。アプリの「物理倉庫」

## 🔐 認証
- **Auth.js / Clerk / Supabase Auth**  
　→ ユーザーのログイン・アクセス制御に使う。セキュリティの玄関口

## 💰 決済・課金
- **Stripe / Lemon Squeezy / Clerk Billing**  
　→ サブスクや商品販売などの金銭のやりとりを仲介してくれる

## 🔎 SEO／LLMO
- **Google Search Console / Schema.org / Next.js SEO**  
　→ アプリを検索やAIエージェントに見つけてもらうための対策群

## 🤖 AI開発ツール
- **Claude Code / OpenAI API / Gemini CLI**  
　→ コーディング補助、AIアプリ実装の道具

## 🎨 UI・デザイン
- **Tailwind CSS / shadcn/ui / Framer Motion**  
　→ 見た目の設計。画面レイアウトや動きの基本

## 🛡 セキュリティ
- **Cloudflare Turnstile / Zero Trust**  
　→ ユーザーやサーバーを守る盾。アクセス制御やCAPTCHA代替

## 🧪 テスト
- **Jest / Vitest / Playwright**  
　→ アプリを「出荷前にテスト」する自動化ツール

## 📣 通知・メール
- **SendGrid / Amazon SES / Resend**  
　→ ユーザーへのメールや通知を送る役割

## 🖼 画像最適化
- **ImageKit / Cloudflare Images**  
　→ UIで表示する画像の軽量化と高速配信

## 🌐 ドメイン
- **Cloudflare Registrar / Route 53**  
　→ 「Web上の住所」。独自URLをつけて信頼性・SEO向上