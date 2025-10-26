## Windows 10/11

### Bật/Tắt Windows Defender
```powershell
powershell -Command "Set-MpPreference -DisableRealtimeMonitoring $true"
powershell -Command "Set-MpPreference -DisableRealtimeMonitoring $false"
```
