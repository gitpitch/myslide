

# GitPitch用リポジトリ

---

<pre>
GitPitchの公式ドキュメント
https://gitpitch.com/docs/about/
</pre>

## GitPitch一覧

### [インフラ勉強会](https://wp.infra-workshop.tech/)

- [2018/08/01 CISSP取得のためにしたこと](https://gitpitch.com/yuki476/myslide?p=20180801_CISSP)
- [2018/08/19 セキュリティの考え方＠CISSP](https://gitpitch.com/yuki476/myslide?p=20180819_security-framework)

---

## 使い方

`Markdownファイル`の中に`.md`ファイルを保存し、
GitPitchで見せたいスライド毎にフォルダ/ブランチ分けして
以下のURLでアクセス。

[https://gitpitch.com/yuki476/myslide/<ブランチ>?p=<フォルダ名>]

---

## OBS使用時の注意点

- ブラウザのハードウェアアクセラレーション有効だとOBSで見えない
- 配信 > サービス > "Mixer.com - *FTL*"を使用すること。
　RTMPは遅延が大きい
- エンコーダは"NVENC H.264"　CBR ビットレート1800ぐらい。
- 

---

## 書式例：よく使うもの

- Markdown書式例

@size[14pt](font size)

@color[#DC143C](HEX color)

@color[orange](name color)

- 画像添付
![Picture](/img/logo_circle96.png)




