# CameraXを試してみる
PreviewとImageCapture機能を実装した。

## 所感
Gradleの依存関係追加などをしたあとは、概ね下記のような流れで機能を追加していけるので使いやすいと思った

1. 実装したい機能のUseCaseクラス（Preview、ImageCaptureなど）のオプションを設定する
2. UseCaseクラス作成時にアクションを渡して、リスナーを設定する
3. 作成したUseCaseクラスをライフサイクルに紐付ける

## コード参考
[Getting Started with CameraX](https://codelabs.developers.google.com/codelabs/camerax-getting-started/#0)
