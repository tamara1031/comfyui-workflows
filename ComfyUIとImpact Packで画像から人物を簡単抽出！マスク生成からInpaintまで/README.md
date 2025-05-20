# 概要
以下の記事で使用したworkflowです
* [ComfyUIとImpact Packで画像から人物を簡単抽出！マスク生成からInpaintまで](https://blog.otama-playground.com/entry/20240901/1725186131)

# ファイル
* segmentation.json - 人物の抽出とマスクの生成までを行うワークフロー
* inpaint_human.json - 人物の抽出からinpaintまでを自動で行うワークフロー, デフォルトではopenposeのcontrolnetを嚙ませています