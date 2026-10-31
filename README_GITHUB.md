# Copilot MES Generic Model Transfer Test

一般化したMES・装置モデルを、GitHubから社内で許可されたMicrosoft Copilot環境にテキストファイルで渡し、読み取り・再現・応用を試験する教材です。会社固有の情報は含めないでください。

## 手順
1. GitHubでこのファイル群を登録（個人PC側）。公開前に各ファイルをレビュー。
2. 会社の許可された方法で `Code > Download ZIP` か個別Rawを取得。
3. ZIPを展開し、`00_START.md` に従う。
4. Copilotには `01_INDEX.md`、`02_RULES.md`、`10_COMMON_MODEL.md`、`20_EQUIPMENT_MODEL.md`、`30_SCENARIOS.md`、`40_OPEN_ISSUES.md` を添付する（必要ならSTARTも）。
5. `50_COPILOT_TEST_PROMPTS.txt` のA/B/Cを順に貼り付ける。
6. **採点用の90と91はCopilotに添付しない**。自分で結果を採点する。

## 取り扱い
公開GitHubに置いた情報は誰でも閲覧できる可能性があります。業務上の利用・取り込みが許可されているか確認してください。GitHubから取得できることは会社の許可を意味しません。EXE、スクリプトの実行、外部パッケージの導入は不要です。

## ファイルの完全性
`manifest.json` にSHA-256が記載されています。必要な場合、会社の許可された標準機能で照合できます。ハッシュ検証のために未承認の実行ファイルを使用する必要はありません。
