```
/my-next-app
│── app/              # ページごとのフォルダ（ルートページ）
│   ├── layout.tsx    # アプリ全体のレイアウト
│   ├── page.tsx      # ルートページ（"/"）
│   ├── dashboard/
│   │   ├── page.tsx  # "/dashboard" ページ
│   │   ├── layout.tsx # "/dashboard" 内のレイアウト
│   ├── about/
│   │   ├── page.tsx  # "/about" ページ
│
│── components/       # 再利用可能なコンポーネント
│   ├── Button.tsx    # ボタンコンポーネント
│   ├── Header.tsx    # ヘッダーコンポーネント
│   ├── Footer.tsx    # フッターコンポーネント
│   ├── Card.tsx      # カードコンポーネント
│
│── hooks/            # カスタムフック
│   ├── useAuth.ts    # 認証用カスタムフック
│   ├── useFetch.ts   # APIフェッチ用カスタムフック
│
│── lib/              # ユーティリティ関数やAPIクライアント
│   ├── apiClient.ts  # APIリクエストのラッパー
│   ├── utils.ts      # 便利関数（フォーマット変換など）
│
│── styles/           # グローバルCSSやTailwind設定
│   ├── globals.css   # 全体のCSS
│   ├── variables.css # CSS変数
│
│── public/           # 静的ファイル（画像・アイコンなど）
│   ├── logo.png
│
│── middleware.ts     # ミドルウェア（認証チェックなど）
│── next.config.js    # Next.jsの設定ファイル
│── package.json      # npmパッケージ管理
```
