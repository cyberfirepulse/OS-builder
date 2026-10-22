# OS-builder

Releases and updates of **OS-builder** (Snoop OS Builder) by CyberFirePulse.

## Download

Installers are published under **[Releases](https://github.com/cyberfirepulse/OS-builder/releases)**.
Each installer comes with a `.sha256` file so you can verify the download:

```
certutil -hashfile SnoopOSBuilder_v<version>_Setup.exe SHA256
```

A license key (`OSB-…`) is required to use OS-builder.

## Automatic updates

At startup, OS-builder checks [`update.json`](update.json) for a newer version
(also available via **Help → Check for updates…**). A downloaded setup is only started
when its SHA-256 matches the value in `update.json`.

## Contact

CyberFirePulse — [cyberfirepulse@gmail.com](mailto:cyberfirepulse@gmail.com)

## Languages

OS-builder follows the Windows display language when a translation is available
(currently English and Dutch) and falls back to English otherwise.
The language can be changed via **Help → Language**.

---

### Nederlands

Installers staan onder **Releases**; bij elke installer hoort een `.sha256`-bestand om de download
te controleren. Voor OS-builder is een licentiesleutel (`OSB-…`) nodig. OS-builder controleert bij het
opstarten zelf op updates (of via **Help → Controleren op updates…**) en start een nieuwe setup alleen
als de SHA-256 klopt. De taal volgt Windows en is te wijzigen via **Help → Taal / Language**.
Contact: cyberfirepulse@gmail.com
