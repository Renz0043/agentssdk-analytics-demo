## 概要
「OpenAI Agents SDKでAIにWebマーケティングのレポートを任せてみた」という記事のハンズオン用リポジトリです。
記事URLはこちら
https://editor.note.com/notes/n54bc15263f32/edit

## 環境構築の前提条件
- Pythonがインストールされていること

## セットアップ手順

1. このリポジトリををクローンします。
```
git clone https://github.com/Renz0043/agentssdk-analytics-demo
```
2. クローンしたディレクトリに移動
```
cd [プロジェクトディレクトリ]
```
3. .env copyファイルを「.env」にリネームしてAPIキーを設定
```
OPENAI_API_KEY=sk-XXXXX
```
4. Python仮想環境を構築して有効化（※任意）
```
python -m venv .venv
source .venv/bin/activate
```
5. poetryを仮想環境にインストール
```
pip install poetry
```
6. パッケージのインストール
```
poetry install --no-root
```
7. Pythonスクリプトを実行
```
poetry run python discussMarketing.py
```
