# 用語集

| 用語 | 意味 | 詳しく |
| --- | --- | --- |
| **MCP**（Model Context Protocol） | LLM アプリと外部の機能・データをつなぐ共通ルール | [01](01-what-is-mcp.md) |
| **ホスト** | LLM アプリ本体。Claude Desktop、ChatGPT など | [02](02-architecture.md) |
| **クライアント** | ホストの中の接続係。サーバーと 1 対 1 でつながる | [02](02-architecture.md) |
| **サーバー** | 機能やデータを提供する側 | [02](02-architecture.md) |
| **データ層** | 何をどんな形式でやり取りするかを決める層 | [02](02-architecture.md) |
| **トランスポート層** | メッセージをどう運ぶかを決める層 | [02](02-architecture.md) |
| **ツール** | LLM が自分の判断で呼ぶ操作 | [03](03-server-features.md) |
| **リソース** | 利用者やアプリが選んで LLM に渡すデータ。URI で指し示す | [03](03-server-features.md) |
| **プロンプト** | 利用者が選ぶ依頼文のひな形 | [03](03-server-features.md) |
| **JSON-RPC** | MCP のメッセージの書き方。依頼・返事・通知の 3 種類 | [04](04-communication.md) |
| **capabilities** | 「この機能に対応しています」という宣言 | [04](04-communication.md) |
| **ステートレス** | サーバーが依頼と依頼の間の状態を覚えていなくてよい作り | [04](04-communication.md) |
| **stdio** | 同じ PC 上のプログラムと標準入出力でやり取りする運び方 | [04](04-communication.md) |
| **Streamable HTTP** | ネット越しに HTTP でやり取りする運び方 | [04](04-communication.md) |
| **elicitation** | サーバーが、クライアントを通じて利用者に入力を頼む仕組み | [05](05-asking-the-user.md) |
| **フォームモード** | アプリの入力欄で聞く。秘密ではない情報用 | [05](05-asking-the-user.md) |
| **URL モード** | 利用者に URL を開いてもらう。秘密情報用 | [05](05-asking-the-user.md) |
| **MRTR** | 「必要なものを返す → アプリが集める → 元の依頼をやり直す」流れ | [05](05-asking-the-user.md) |
