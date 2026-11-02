# kaggle-template

Kaggle コンペ用のテンプレートです。コンペごとにこのテンプレートから新しいリポジトリを作ります。

## 新しいコンペを始める

```bash
gh repo create kaggle-<コンペ名> --private --template yoshinonf/kaggle-template --clone
cd kaggle-<コンペ名>
kaggle competitions download -c <コンペ名> -p data
```

ダウンロードした zip は `data/` で展開してください。

## フォルダ構成

| フォルダ | 用途 | Git 管理 |
|---|---|---|
| `data/` | コンペのデータ | ✕ |
| `notebooks/` | EDA・実験用ノートブック | ○ |
| `src/` | 特徴量・学習・推論のコード | ○ |
| `models/` | 学習済みモデル | ✕ |
| `submissions/` | 提出ファイル | ✕ |

## セットアップ

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

---

<!-- ここから下はコンペごとに書き換える -->

## コンペ情報

- コンペ名：
- URL：
- 評価指標：
- 締め切り：

## スコア記録

| 日付 | ブランチ | 内容 | CV | Public LB |
|---|---|---|---|---|
|  |  |  |  |  |
