# getting started PowerShell

## Version check

```powershell
$PSVersionTable.PSVersion
```

## Windows PowerShellとPowerShellの違い

Windows PowerShellとPowerShellは異なる製品です。

Windows PowerShellの特徴は以下の通りです。

- Windows PowerShell は、Windows に付属する PowerShell
- Windows PowerShell は、Windows でのみ実行され.NET Framework が使用される
- 最新バージョンは Windows PowerShell 5.1であり、サポートはOSによって異なる

PowerShellの特徴は以下の通りです。

- PowerShell は、Windows、Linux、macOS で実行される
- PowerShell は、.NET Core という新しいバージョンの .NET 上に構築される

[参考：what-is-windows-powershell](https://learn.microsoft.com/ja-jp/powershell/scripting/what-is-windows-powershell?view=powershell-7.5)

## PowerShellの基本

PowerShellのコマンドはコマンドレットと呼ばれます。
コマンドレットの特徴は以下の通りです。

- ネイティブのPowerShellコマンドであり、スタンドアロンの実行可能ファイルではありません
- 必要に応じて読み込むことができる PowerShellモジュールにまとめられている
- 任意のコンパイルされた .NET 言語または PowerShellスクリプト言語自体で記述可能
- PowerShellのコマンドレット名には、"動詞-名詞" という名前のペアが使われる

```powershell
Get-Command
```
