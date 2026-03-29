# FP3級 過去問トレーニング

FP3級（ファイナンシャル・プランニング技能検定3級）の過去問学習ツール。オフラインでも使える PWA 対応。

## 機能

- **過去問演習**: 各分野からオリジナル問題を出題（3択形式）
- **成績グラフ**: 模試の得点推移を SVG ラインチャートで表示
- **弱点分析**: 分野別の正答率を可視化し、苦手分野を特定
- **苦手問題復習**: 2回以上間違えた問題だけを集中復習
- **PWA 対応**: ホーム画面に追加してオフライン利用可能

## 技術構成

- HTML / CSS / Vanilla JavaScript（フレームワーク不使用）
- Service Worker によるオフラインキャッシュ
- localStorage でスコア履歴を保持
- GitHub Pages でホスティング

## ファイル構成

```
index.html      メインアプリ（CSS/JS インライン）
data.js         問題データ
manifest.json   PWA マニフェスト
sw.js           Service Worker
icon.svg        アプリアイコン
```

## 使い方

1. [GitHub Pages](https://ramdamain-commits.github.io/fp3-training/) にアクセス
2. 分野を選んで演習開始
3. 成績画面で推移と弱点を確認
4. 苦手問題だけ集中復習

## ライセンス

MIT
