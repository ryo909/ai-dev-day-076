# Day076 Story — Friend Intro Card

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day076専用にテーマをseed固定して再生成時の見た目を安定化
- utility用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: intro_hint_deck
- Mechanic: flow_pick
- Input/Output: people_nodes -> request_card
- Audience Promise: 話し始めの不安を、持てる短い札にできる。
- Publish Hook: 相手の文脈と避けたい話題を入れると、最初の一言と次の橋渡しだけが札になる。
- Complexity Tier: medium
- Selected components: none
- Complexity hint: Implement the locked brief with one clear hero interaction and keep the main screenshot readable.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day076｜初対面ひと言札
初対面の最初の一言を決めるツールです。
