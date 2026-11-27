# Cloudron apps

Community app catalogue for [Cloudron](https://www.cloudron.io/) apps packaged by Frivold Digital.
Each folder holds an app's `CloudronVersions.json` and store images. The app source and Docker images
are private.

## SpaceRisk

ISO 31000 risk register with monthly team reviews. Needs Cloudron 10 or later.

1. Settings → Private registry: add `rotterdam.frivolddigital.com` with a download-only login.
2. App Store → Community apps: add
   `https://raw.githubusercontent.com/partoneoftwo/cloudron-apps/main/spacerisk/CloudronVersions.json`

## Hyperdrive

Data platform on SQLite and Datasette: CSV and REST in, a raw and a normalised layer, CSV and REST out.
Needs Cloudron 10 or later. Source: [partoneoftwo/hyperdrive-platform](https://github.com/partoneoftwo/hyperdrive-platform).

1. Settings → Private registry: add `rotterdam.frivolddigital.com` with a download-only login.
2. App Store → Community apps: add
   `https://raw.githubusercontent.com/partoneoftwo/cloudron-apps/main/hyperdrive/CloudronVersions.json`

## Agentgateway

AI control plane: one gateway between coding agents such as Claude Code and the model providers they call.
People keep their own Claude login; the gateway adds a gateway key and request logs. Needs Cloudron 10 or later.
Source: [partoneoftwo/cyberdyne-aicontrolplane](https://github.com/partoneoftwo/cyberdyne-aicontrolplane).

1. Settings → Private registry: add `rotterdam.frivolddigital.com` with a download-only login.
2. App Store → Community apps: add
   `https://raw.githubusercontent.com/partoneoftwo/cloudron-apps/main/agentgateway/CloudronVersions.json`
