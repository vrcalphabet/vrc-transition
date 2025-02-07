# vrc-transition

[vrc 公式サイト](https://vrchat.com/home)日本語化プロジェクトの翻訳データ置き場です。

`src/`内の各ディレクトリには翻訳前後の文字列データと翻訳対象要素の場所を示すパスが含まれており、これらを[xpr-tsr-merger](https://github.com/vrcalphabet/xpr-tsr-merger/releases/latest)でバンドルしたものをGitHub経由で[vrc-translator](https://github.com/vrcalphabet/vrc-translator)から使用し、公式サイトを翻訳します。

xprファイルの仕様は[こちら](https://github.com/vrcalphabet/xpr-tsr-merger/blob/main/docs/xpr-documentation.md)で確認できます。

## 進捗表

- [ ] 各ページの対応
  - [x] /home/login
  - [x] /home/register
  - [x] /home/verify
  - [x] /home/password
  - [x] /home/forgot-email
    - 正しい手順を踏んでも確認メールが届かないため、メール内のリンク先のページは翻訳できません。
  - [x] /home/failedverify
  - etc...（随時追加予定）
