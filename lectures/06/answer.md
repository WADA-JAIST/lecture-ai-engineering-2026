# 第6回 解答

## 演習

<!-- [tool call] の行は、表示された行をそのまま貼り付けてください。終わらなかった STEP は、空欄のままでかまいません。 -->

- STEP 1 のツールの名前：
- STEP 2 の [tool call]：
- STEP 3 の [tool call]：
- STEP 4 の [tool call]：
- 気づき・疑問：

## 宿題

<!-- 基礎・実装・発展のどれか1つに取り組めば完了です。 -->

- 取り組んだレベル：基礎
- やったこと：`app/mcp_server.py` に `server.tool()(tools.get_lecture_summary)` を追加した。
- 結果：`glossary_get_lecture_summary` が MCP サーバーのツール一覧に公開された。ツール呼び出しのトレースは、Gemini API から 2 回とも HTTP 503（モデル混雑）が返され、実行できなかった。
- 気づき・疑問：サーバー側への登録を変えるだけで、エージェント側の設定はそのままにツール一覧へ反映された。
