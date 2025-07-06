# Unity-PackageJsonGenerator
Unityの UPM (Unity Package Manager) 対応パッケージを公開する際に必要な package.json ファイルを、簡単に生成できる Editor 拡張ツールです。

## 対応バージョン

- 6000.0.0以上

## インストール方法

#### UPM Package

1.Git URLをコピー
```
https://github.com/MAH-Lib/Unity-PackageJsonGenerator.git?path=PackageJsonGenerator
```
2.Unity Package Manager から `...form git URL`を選択

3.`Install package form git url`の欄にコピーしたGit URLをペーストしインストールを行う

#### manifest.json

`Packages/manifest.json` に以下を追加してください。  
```
"com.mah.package-json-generator":"https://github.com/MAH-Lib/Unity-PackageJsonGenerator.git?path=PackageJsonGenerator"
```

<!-- 必要な場合に記述 --> 
## 使用方法
1. メニューバーから MAH/Generator/PackageJson Generator Window を選択

   ![Image1](Image/Image1.png)

2. 表示されたEidtor Window に必要な情報を入力

   - **必須設定項目**  
     必ず入力する必要のある項目です  
     ※著者情報設定の [E-mail] [URL] は入力不要です
     
     ![Image2](Image/Image2.png)

   - **任意設定項目**  
     設定する項目のみ入力します

     ![Image3](Image/Image3.png)

3. [Browes] をクリックし package.json を生成するフォルダーを選択

   ![Image4](Image/Image4.png)
   
4. [Create package.json] をクリックし package.jsonファイルを生成

   ![Image5](Image/Image5.png)

## サポート・投稿先について

- **バグ報告・機能追加の要望** → [Issues](../../issues)
- **質問・相談・意見交換** → [Discussions](../../discussions)

ご協力ありがとうございます！

## License
see [LICENSE](LICENSE)
