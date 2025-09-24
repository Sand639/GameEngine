# GameEngine (working title)

C++20 / DirectX 12 / Visual Studio 2022  
Unityっぽい「エディタ + ランタイム」を段階的に自作します。  
学習しつつ公開開発（Public）で進めます。

## Roadmap（ざっくり）
- [ ] DX12 最小ウィンドウ（SwapChain / コマンドキュー）
- [ ] 三角形描画（ルートシグネチャ / PSO / HLSL）
- [ ] 入力・タイマー
- [ ] コンポーネント指向の土台
- [ ] シェーダ管理 / リソース管理
- [ ] 簡易エディタ（ImGui）
- …以降アップデート

## Repo Layout（予定）
engine/ # 本体（include/ と src/）
samples/ # 動作確認用
shaders/ # HLSL
assets/ # モデル/テクスチャ（LFS）

## Build（後で詳述）
- Windows 11 / Visual Studio 2022
- CMake（予定）
- vcpkg（予定）

## License
MIT
