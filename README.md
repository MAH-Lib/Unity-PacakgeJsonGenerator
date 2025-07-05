# Unity-PacakgeJsonGenerator
Unityの UPM (Unity Package Manager) 対応パッケージを公開する際に必要な package.json ファイルを、簡単に生成できる Editor 拡張ツールです。

## 対応バージョン

- 6000.0.0以上

## インストール方法

#### UPM Package

1.Git URLをコピー
```
https://github.com/MAH-Lib/Unity-PacakgeJsonGenerator.git?Path=packageJson Generator
```
2.Unity Package Manager から `...form git URL`を選択

3.`Install package form git url`の欄にコピーしたGit URLをペーストしインストールを行う

#### manifest.json

`Packages/manifest.json` に以下を追加してください。  
```
"com.mah.package-json-generator":"https://github.com/MAH-Lib/Unity-PacakgeJsonGenerator.git?Path=packageJson Generator"
```

<!-- 必要な場合に記述 --> 
## 使用方法
<!-- アセット・汎用機能モジュールの操作方法 --> 
