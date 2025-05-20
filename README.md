# Voice Stylist

## 洗練された音声読み上げツール

Voice Stylistは、テキストを美しい音声で読み上げるためのウェブアプリケーションです。長文を読むのが大変な時や、音声で情報を取り入れたい時に最適なツールです。

![Voice Stylist](https://example.com/voice生**: デフォルトで効率的な読み上げ速度に設定
- **スマートなテキスト分割**: 80文字単位で自然な区切りを検出し、途切れない読み上げを実現
- **複数の音声**: 利用可能な様々な言語・声質から選択可能
- **完全レスポンシブ**: スマートフォンからデスクトップまで、あらゆる画面サイズに対応
- **高級感のあるデザイン**: 美容院のような洗練されたUIで使いやすさを追求

## 使い方

1. テキストエリアに読み上げたいテキストを貼り付けます
2. 必要に応じて声の種類、速度、高さを調整します
3. 「読み上げ開始」ボタンをクリックすると読み上げが始まります
4. 読み上げ中に「一時停止」「再開」「停止」ボタンで操作できます

## 技術仕様

- **Web Speech API**: ブラウザ標準のSpeechSynthesis機能を使用
- **HTML5/CSS3**: モダンなウェブ標準に準拠
- **JavaScript**: 外部ライブラリに依存しない軽量な実装
- **レスポンシブデザイン**: Flexbox/Gridレイアウトを活用

## ブラウザ対応状況

| ブラウザ | 対応状況 | 備考 |
|---------|---------|------|
| Firefox | ◎ | 最も安定した動作 |
| Chrome | ○ | 長文で一部制限あり |
| Safari | ○ | iOS/macOSで安定 |
| Edge | ○ | Chromiumベース版で動作 |
| IE | × | 未対応 |

## インストール方法

このアプリケーションはブラウザで動作するため、特別なインストールは不要です。以下の手順でご利用いただけます。

```
1. リポジトリをクローンまたはダウンロード
2. index.htmlをブラウザで開く
```

または、以下のURLにアクセスして直接利用することもできます。
https://voice-stylist.example.com

## カスタマイズ

`style.css`を編集することで、デザインをカスタマイズできます。主な変更ポイント:

```css
:root {
    --primary-color: #9c8570; /* メインカラー */
    --secondary-color: #d4c8be; /* サブカラー */
    --accent-color: #5a4d41; /* アクセントカラー */
    /* その他の変数... */
}
```

## 今後の開発予定

- 音声ファイルとしての保存機能
- 複数言語の同時サポート
- テキスト解析による感情表現の強化
- クラウド同期機能

## 既知の問題

- Chromium系ブラウザでは長文（約15秒以上）の読み上げが途中で停止することがある
- 一部の古いブラウザでは音声が利用できない場合がある
- モバイルデバイスではバックグラウンド再生に制限がある場合がある

## ライセンス

MIT License

## 作者

Voice Stylist Team

## 謝辞

- Web Speech APIを提供するブラウザベンダー各社
- デザインインスピレーションを提供してくれた美容院関係者の皆様
- テストにご協力いただいたユーザーの皆様

Citations:
[1] https://qiita.com/shun198/items/c983c713452c041ef787
[2] https://github.com/othneildrew/Best-README-Template
[3] https://github.com/remarkablemark/web-app-template/blob/master/README.md
[4] https://www.makeareadme.com
[5] https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide/
[6] https://support.atlassian.com/ja/bitbucket-cloud/docs/readme-content/
[7] https://codechord.com/2012/01/readme-markdown/
[8] https://qiita.com/KamataRyo/items/466255fc33da12274c72
[9] https://readme.so
[10] https://www.drupal.org/docs/develop/managing-a-drupalorg-theme-module-or-distribution-project/documenting-your-project/readmemd-template

---
Perplexity の Eliot より: pplx.ai/share
