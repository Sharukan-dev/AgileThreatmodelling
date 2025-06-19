# Threagile Docker Setup

Dies ist ein einfaches Docker-Setup zur Nutzung von [Threagile](https://threagile.io/).

## 🚀 Start

```bash
docker compose up
```

Oder manuell:

```bash
docker build -t threagile-local .
docker run --rm -v $PWD:/app threagile-local -model model.yaml -output output
```

## 📁 Dateien

- `model.yaml`: Dein Threat-Modell
- `output/`: Enthält Berichte (PDF, JSON, Excel)

## 🐳 Quelle

Verwendet das offizielle Image: `ghcr.io/threagile/threagile`
