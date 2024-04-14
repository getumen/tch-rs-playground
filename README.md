# tch-rs playground

## 実行方法

```
# CUDAがある場合はCUDAのバージョンを指定する。
# CUDA 11.7を使うならば、cu117と指定する
export TORCH_CUDA_VERSION=cu117

cargo run
```

`cargo run`により実行する。featuresでlibtorchをダウンロードする設定をしているので、依存を用意しなくても実行できる。ビルドして実行したい場合は必要なlibtorchを落としてきて設定する必要がある。詳細はドキュメント参照。

https://github.com/LaurentMazare/tch-rs?tab=readme-ov-file#getting-started
