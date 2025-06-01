# asciidoctorj-gradle-template

Asciidocを使った仕様書の雛形。

- Java開発者向けにGradle+AsciidoctorJで構築
- textlintはNode.jsで構築
- DOCX出力用のPandoc/rsvg-convertは別途導入が必要
- 出力形式はHTML5/DOCXに対応

## 実行例

```
$ gradlew asciidoctor
```

./build/docs/にdocx/html5が出力される。

## 校正例

```
npm run lint
```

textlintの校正結果が出力される。
