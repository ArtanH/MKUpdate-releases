# MKUpdate – signierte Releases

Dieses Repository enthält nur die signierten Windows-Installer von MKUpdate, einem Update-Manager für Windows 11. Der Quellcode ist privat.

MKUpdate holt sich hier ohne Anmeldung neue Versionen (`releases/latest/download/latest.json`) und installiert nur Installer, deren minisign-Signatur zum eingebauten Prüfschlüssel passt:

```
untrusted comment: minisign public key: 7E3FAFEA5AF9C05F
RWRfwPla6q8/fgJhzKcpNlmBN0+Dvm9J0iNT4ERtoEZDDrbn4qViLxxC
```

Jedes Release enthält `MKUpdate_<Version>_x64-setup.exe`, die Signatur `.sig` und `latest.json`.
