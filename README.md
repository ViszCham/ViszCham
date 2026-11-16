# 廣野悠歌 / Yuka Hilono
ひろの ゆうか

**作曲家 / Composer**

ゲームや映像作品の音楽制作、楽曲提供を手がけています。

作品や時期に応じて、あたわめ（Atawame）、紫合ユウ、Youta Hilonoの名義で制作しています。

## 音楽

記載の日付は収録作品の発売日、または映画本編の公開日です。

**2015.09.02｜「Sunday Morning」　作曲**

あたわめ名義
セガ『初音ミク Project mirai』シリーズのルームBGMで、ボックスセット『初音ミク Project mirai こんぷり〜と』のDISC 5に収録

[収録アルバム・トラックリスト](https://store.umaa.net/items/1596946) · [発売情報（セガ公式）](https://info.miku.sega.jp/4022)

**2017.05.30｜「ピンキーリングに花飾り」　作曲・編曲**

紫合ユウ名義（クレジット表記：Y0u Yuda）
さくらシンデレラのシングル『さくらの木の下で』に収録

[制作クレジット（BeetOnics）](http://beetonics.co.jp/tracks/706) · [発売情報・収録曲（Billboard JAPAN）](https://www.billboard-japan.com/goods/detail/559015)

**2017.08.12｜「逆风飞翔」　作曲・編曲**

紫合ユウ名義です。中国の女性アイドルグループ「1931女子偶像组合」のアルバム『星火盛放』に収録

[楽曲情報・クレジット（酷狗音楽）](https://www.kugou.com/mixsong/14rxdr61.html) · [楽曲情報（百度百科）](https://baike.baidu.com/item/%E9%80%86%E9%A3%8E%E9%A3%9E%E7%BF%94/60849687) · [アルバム発売情報](https://wapbaike.baidu.com/item/1931/4600781)

**2024.01.27｜「thinKING ALIEN」　共同編曲・ストリングスアレンジ**

Youta Hilono（RiriMoo）名義です。VRChat映画『宇宙船からのSOS！』のエンディング楽曲です。日付は映画本編の公開日です。

2024年4月に発表された第2回VRCムービーアワードの「音響音楽賞」で、共同ノミネートとして名前が掲載されました。

[作品](https://www.youtube.com/watch?v=SzzDjXKkR6M) · [制作クレジット](https://smartphonefilmfestival.jimdofree.com/2024%E5%B9%B4%E5%BF%9C%E5%8B%9F%E4%BD%9C%E5%93%81/%E3%83%A1%E3%82%BF%E3%83%90%E3%83%BC%E3%82%B9-ai%E9%83%A8%E9%96%80/) · [映画公開日（制作元）](https://note.com/studiobagus/n/n86f5944e3760) · [ノミネート一覧](https://metacul-frontier.com/?p=11090)

## ソフトウェア

RustとPythonを学習中です。LLMの支援を受けながら、自分の開発を支えるツールを制作しています。

### [Epistesys](https://github.com/ViszCham/Epistesys)（Beta-7.1）

AIとの対話で整理した条件を、実装・検証・修復につなぐ開発支援ツールです。依頼した条件と、対応するコード・検証結果を結び付け、「どの版で、何を確かめたか」を追いやすくします。

仕様の相談では、守りたい条件や未決定の点を整理します。コーディングでは、ビルド、登録された公開APIの呼び出し、受入条件などを分けて確認し、変更後の再検証や作業の再開を支援します。こうした開発手順の一部を、Rustの型と状態遷移で扱っています。

解析できなかった条件や不足する検証は、未確認として残します。現在の対応範囲と確認済みの内容は、文書にまとめています。

[会話・コーディング支援の具体例](https://github.com/ViszCham/Epistesys/blob/main/docs/coding-and-conversation-assistance.md#日本語) · [実行ガイド](https://github.com/ViszCham/Epistesys/blob/main/docs/execution-guide.md#日本語) · [Beta-7.1の変更と確認範囲](https://github.com/ViszCham/Epistesys/blob/main/docs/epistesys-7.1.0-beta.1-release-notes-2026-11-06.md#日本語)

### [RepoSeiri](https://github.com/ViszCham/RepoSeiri)（v1.1.0）

READMEの記述を、Rustの公開APIやリポジトリ内の文書と照合する文書監査ツールです。実装されているのにREADMEで伝わっていない機能や、根拠より強い表現を見つけ、解析できなかった箇所は「不明」として区別します。

変更前後の意味の差分も比較し、CLIとCodexプラグインからレビュー用の情報を出力します。ファイルの書き込みやネットワーク操作は行いません。
