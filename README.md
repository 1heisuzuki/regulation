# Regulation
@1heisuzuki がプロジェクトフォルダの階層構造や命名をする時に守っていきたい規則メモ

# 動画プロジェクト
```
<project-name>
├── docs # 企画書・コンテなどの書類系
├── ref  # 参考資料
├── prj  # 編集ソフトのプロジェクトファイル
│   ├── ae  # After Effects
│   └── pr  # Premiere Pro
├── src  # 素材生データ（編集しない）
│   ├── img
│   │   ├── logo
│   │   ├── illust
│   │   └── photo
│   ├── sound
│   │   ├── bgm
│   │   ├── se
│   │   └── voice
│   ├── mov  # 撮影素材以外の動画データ
│   └── guide
├── src-ph  # プレースホルダ用素材（最終盤を書き出す前に移動して誤爆防止）
├── work  # 素材編集データ（バージョンはファイル名_revNで管理）
│   ├── img
│   │   ├── logo
│   │   ├── illust
│   │   └── photo
│   ├── sound
│   │   ├── bgm
│   │   ├── se
│   │   └── voice
│   └── guide
├── mov　# 動画撮影データ
│   ├── YYYYMMDD_<camera-name>
│   │      :
│   │      :
│   ├── YYYYMMDD_<camera-name>
│   └── YYYYMMDD_<camera-name>
├── audio-master  # 音声マスタリングデータ
├── out-mediate   # 動画中間ファイル
├── out-master    # 動画出力用
│   ├── <project-name>_revN_<sizeH>_<format>.<ext>
│   │      :
│   │      :
│   └── <project-name>_revN_<sizeH>_<format>.<ext>
└── final   # 完パケ素材（案件終了後にout-masterからコピー）
```

## 参考資料
- プロジェクトフォルダの整理 | 麦 : Baku https://baku89.com/video-prod/structure-of-working-directory
- 【Premiere Pro】プロジェクトフォルダ整理術 | Vook(ヴック) https://vook.vc/n/662

# 研究プロジェクト
WIP

# Future Work
- 階層が生成できるshコマンドとか作りたい
