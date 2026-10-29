# Face Morph

顔写真を2枚選ぶと、顔のパーツを自動で対応させてモーフィングアニメを作るWebページです。
画像はブラウザの中だけで処理され、どこにも送信されません。

使う: https://<ユーザー名>.github.io/face-morph/

## 使っているもの

- [MediaPipe Tasks Vision](https://github.com/google-ai-edge/mediapipe)（顔のランドマーク検出・髪や肌の領域分け、Apache-2.0）
- [Delaunator](https://github.com/mapbox/delaunator)（三角形分割、ISC）
