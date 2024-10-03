# Vymazání schránky

Vymaže všechny záznamy ve schránce (*Win+V*). Skript funguje jen ve Windows Powershell 5.0.

```powershell
[Windows.ApplicationModel.DataTransfer.Clipboard, Windows, ContentType = WindowsRuntime]::ClearHistory()
```

Spuštění skriptu odkudkoliv je možné zařídit pomocí následujícího Batch skriptu a jeho následného přidání do proměnné *PATH*.

```bat
@echo off
set SCRIPT_DIR=%~dp0
powershell -File "%SCRIPT_DIR%clear-clipboard.ps1" -WindowStyle Hidden
```