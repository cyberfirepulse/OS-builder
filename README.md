# OS-builder

Releases en updates van **OS-builder** (Snoop OS Builder) door CyberFirePulse.

## Downloaden

De installers staan onder **[Releases](https://github.com/cyberfirepulse/OS-builder/releases)**.
Bij elke installer hoort een `.sha256`-bestand waarmee je kunt controleren of de download klopt:

```
certutil -hashfile SnoopOSBuilder_v<versie>_Setup.exe SHA256
```

Voor het gebruik van OS-builder is een licentiesleutel nodig (`OSB-…`).

## Automatische updates

OS-builder kijkt bij het opstarten in [`update.json`](update.json) of er een nieuwere versie is
(en via **Help → Controleren op updates…**). De nieuwe setup wordt alleen gestart als de
SHA-256 uit `update.json` overeenkomt met de download.
