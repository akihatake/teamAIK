# Team AIK

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

本当はDialogFlowを使いたかったが、、、

　1. 検索キーワードとして、料理やお酒の種類を抜き出し

　2. Fulfillmentを利用して、ぐるナビAPI経由でお店情報取得

　3. 取得したデータからオススメのお店を絞ってSlackボットへ

しかし、3のFulfillmentでの外部API呼び出しでエラー問題が解決できず、、、。

---

## 得られた知識

* ぐるなびAPIの利用方法
* PythonのSlackClinetを使った連携
* DialogFlowでの文字列解析手法
