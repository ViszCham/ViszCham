# Haluka Hilono / 廣野悠歌

**作曲家 / Composer**

作曲家として、楽曲提供やゲーム・映像作品の音楽制作を手がけています。

ソフトウェア開発ではRustとPythonを学習中です。LLMの支援を受けながら、開発や検証を支えるツールを作っています。

## 音楽の制作実績

### SEGA『初音ミク Project mirai』シリーズ

**「Sunday Morning」— 作曲**

あたわめ（Atawame）名義で作曲しました。ゲーム内のルームBGMとして収録されています。

[収録アルバム](https://store.umaa.net/items/1596946)

### 1931女子偶像組合（1931 Girls Group）

**「逆風飛翔」（原題：逆风飞翔）— 作曲・編曲**

紫合ユウ名義で、中国の女性アイドルグループ1931に楽曲を提供しました。

[楽曲情報・クレジット](https://www.kugou.com/mixsong/14rxdr61.html)

### VRChat映画『宇宙船からのSOS！』

**主題歌「thinKING ALIEN」— 共同編曲・ストリングスアレンジ**

Youta Hilono（RiriMoo）名義で参加しました。同作のエンディング楽曲が、第2回VRCムービーアワード「音響音楽賞」にノミネートされました。

[作品](https://www.youtube.com/watch?v=SzzDjXKkR6M) · [制作クレジット](https://smartphonefilmfestival.jimdofree.com/2024%E5%B9%B4%E5%BF%9C%E5%8B%9F%E4%BD%9C%E5%93%81/%E3%83%A1%E3%82%BF%E3%83%90%E3%83%BC%E3%82%B9-ai%E9%83%A8%E9%96%80/) · [ノミネート紹介](https://vr-lifemagazine.com/4-19vrchatmovieaward2023/)

作品や時期に応じて、複数の名義で制作しています。

## ソフトウェア開発

Rustを中心に、次のプロジェクトを開発しています。

### [Epistesys](https://github.com/ViszCham/Epistesys)

LLMへの指示、判断の根拠、実行権限、検証結果を、モデルの外部で管理する実験的な研究プロジェクトです。長い指示や複雑なタスクに含まれる制約や未解決事項を追跡する仕組みを開発しています。

公開版はアルファ段階です。ハルシネーションの低減や長期タスクの信頼性向上については、今後、ベンチマークや独立評価で検証していきます。

### [RepoSeiri](https://github.com/ViszCham/RepoSeiri)

READMEの記述と、Rustの公開APIやリポジトリ内の文書から確認できる情報を照合する、Rust製の文書監査ツールです。

説明されていない機能、根拠より強い表現、解析できず判断を保留する箇所を整理します。変更前後の意味の変化も比較し、CLIとCodexプラグインを通じてレビュー用の情報を提示します。
