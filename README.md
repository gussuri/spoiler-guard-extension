# Spoiler Guard for YouTube

YouTubeのコメントやチャットリプレイに含まれるネタバレ・匂わせを、ぼかしまたは非表示にするChrome拡張です。共有ブロックリストと自分専用の条件を組み合わせ、初見の視聴体験を守ります。

[Chrome Web Storeから追加](https://chromewebstore.google.com/detail/filikhhcifickcnnihlahniajlhbokbl) ・ [公式サイト](https://spoiler-guard.vercel.app/) ・ [GitHub Releases](https://github.com/gussuri/spoiler-guard-extension/releases/latest)

現在の公開版は **v0.2.9** です。通常はChrome Web Storeからのインストールをおすすめします。

## 主な機能

- YouTubeの通常コメントとチャットリプレイをぼかし・非表示
- 対応動画向けの共有ブロックリストを自動取得
- キーワードなど、自分専用のブロック条件を追加
- 隠した理由の表示と、一時的な表示解除
- リスト作成と共有を支援するキュレーター機能
- 日本語・英語のUI

## インストール

### Chrome Web Store

[Chrome Web Storeの配布ページ](https://chromewebstore.google.com/detail/filikhhcifickcnnihlahniajlhbokbl)から追加してください。更新も自動で配信されます。

### 手動インストール

検証目的で手動インストールする場合は、[最新のGitHub Release](https://github.com/gussuri/spoiler-guard-extension/releases/latest)に添付された <code>spoiler-guard-v0.2.9.zip</code> を使用します。

1. ZIPをダウンロードして展開します。
2. Chromeで <code>chrome://extensions/</code> を開きます。
3. 「デベロッパーモード」を有効にします。
4. 「パッケージ化されていない拡張機能を読み込む」を選びます。
5. 展開した <code>spoiler-guard-v0.2.9</code> フォルダを指定します。

## 対応範囲

- PC版のChrome系ブラウザを対象としています。
- 共有ブロックリストの対応作品・動画は[公式サイト](https://spoiler-guard.vercel.app/)で確認できます。
- 共有リストがない動画でも、自分専用の条件は利用できます。
- スマートフォン版YouTubeは対象外です。

## 権限とプライバシー

| 権限・接続先 | 用途 |
| --- | --- |
| <code>storage</code> | 設定と自分専用の条件をブラウザ内に保存 |
| <code>tabs</code> | 開いているYouTube動画との連携、設定画面や公式サイトを開く |
| <code>youtube.com</code> | コメントとチャットリプレイを画面上で判定・表示制御 |
| <code>spoiler-guard.vercel.app</code> | 対応動画の共有ブロックリストを取得 |

通常のブロック処理はブラウザ内で行われ、閲覧中のコメント本文、投稿者名、視聴履歴を自動送信しません。リスト作成・共有機能で利用者自身が保存または送信したデータは、[公式サイトのプライバシー案内](https://spoiler-guard.vercel.app/privacy/)に従って扱われます。

## 注意点

- すべてのネタバレを完全に防ぐものではありません。
- 文脈によっては通常のコメントが隠れる場合があります。
- YouTubeの画面構成変更により、一時的に動作しなくなる可能性があります。
- YouTubeおよびGoogleの公式拡張機能ではありません。

## 問い合わせ

不具合や要望は[GitHub Issues](https://github.com/gussuri/spoiler-guard-extension/issues)へお願いします。対応動画や共有リストについては[公式サイト](https://spoiler-guard.vercel.app/)も確認してください。

## このリポジトリについて

このリポジトリは、手動検証用の配布ZIPと公開リリース情報を管理する配布用リポジトリです。開発・検証用リポジトリ、評価データ、実験コード、ローカルの秘密情報は公開していません。

本リポジトリにはオープンソースライセンスを設定していません。明示的に許可されていない複製・改変・再配布の権利は付与されません。
