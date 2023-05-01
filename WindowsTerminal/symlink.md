
## WindowsTerminal

settings.json のシンボリックリンクは下記のコマンドで作成する。(PowerShellを管理者権限で実行)

‘‘‘
New-Item -Value 'C:\Users\umasoya\windows\WindowsTerminal\settings.json' -Path "C:\Users\umasoya\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\" -Name "settings.json" -ItemType SymbolicLink
‘‘‘