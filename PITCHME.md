# teamAIK

発表資料

---
## メンバ
ishikawa
kosuga
hatakeyama

---
## ボットの概要
飲食店をランダムで教えてくれるボットです。
PythonとSlack連携でアプリ作成しました。

　1. Slackボット
　2. Cloud9上のPython
　3. ぐるなびAPI
　4. Pythonでオススメ１店舗に絞り込み
　5. Slackで返答

---

## DialogFlowでのチャレンジ
本当はボットでの受け答えはDialogFlowを利用したかったが、、、、
アバウトな質問でも、特定のキーワードを抜き出す事ができるので、条件付き検索も柔軟に対応できる事を目論んでいた。

　1. DialogFlowにてボットで受け取った入力文字列解析
　2. 検索キーワードとして、料理やお酒の種類を抜き出し
　3. 抜き出したキーワードをもとにFulfillment（Google Cloud Function）を利用して、ぐるナビAPI経由でお店情報取得
　4. JSONでもらったデータからオススメのお店を選択してSlackボットへ回答

しかし、3のFulfillmentでの外部API呼び出しでエラー問題が解決できず、、、。

---

## 得られた知識

 * PythonのSlackClinetを使った連携
 * DialogFlowでの文字列解析手法

