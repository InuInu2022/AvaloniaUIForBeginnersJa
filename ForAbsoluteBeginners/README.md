# Avalonia UI 超入門 : SampleApp

```cmd: 最初の一回
dotnet new install Avalonia.Templates
```

```cmd: テンプレから作る
dotnet new avalonia.app -o SampleApp
```


```txt
SampleApp
├obj	#無視
├App.axaml				#アプリ本体のAXAML
├App.axaml.cs			#アプリ本体のコードビハインド
├app.manifest			#基本的に触らない(Windowsで半透明ウィンドウ実現用)
├MainWindow.axaml		#メインウィンドウのAXAML
├MainWindow.axaml.cs	#メインウィンドウのコードビハインド
├Program.cs				#いわゆるエントリーポイント
└SampleApp.csproj		#プロジェクト設定ファイル
```

- `app.manifest`はなくても動きます

```txt:WPFのテンプレで作った場合の比較
SampleWPF
├obj	#無視
├App.xaml
├App.xaml.cs
├AssemblyInfo.cs
├MainWindow.xaml
├MainWindow.xaml.cs
└SampleWPF.csproj
```

- `AssemblyInfo.cs`はなくても動きます