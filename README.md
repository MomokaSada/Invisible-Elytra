# Invisible-Elytra

Minecraft Bedrock Edition 用の不可視エリトラ（リソースパック）です。

![preview](docs/assets/image.png)

## インストール

1. [Releases](https://github.com/MomokaSada/Invisible-Elytra/releases) から `Invisible-Elytra.mcpack` をダウンロード
2. ダブルクリックで Minecraft にインポート

## 使い方

### 対応バージョン

- Minecraft Bedrock Edition 1.17.30 以上（manifest の min_engine_version に準拠）

### 有効化

1. `Invisible-Elytra.mcpack` をダウンロードする
2. ファイルをダブルクリックし、Minecraft にインポートする
3. Minecraft を起動し、設定 → グローバルリソース またはワールド設定 → リソースパック から「Invisible-Elytra」を有効化する

### 効果

- エリトラを装備した際、見た目が透明になります
- 他のプレイヤーからも透明に見えます

### 注意事項

- リソースパックのため、サーバー側の設定や他のパックとの競合で表示が変わる場合があります
- 透明化は見た目のみで、飛行性能などは変更されません

## リリースの作り方

`v1.0.0` のようなタグを push すると、GitHub Actions が `resource_pack/` を zip して `.mcpack` を生成し、Release に添付します。

```bash
git tag v1.0.0
git push origin v1.0.0
```