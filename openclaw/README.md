# OpenClaw resources

- **Guide:** [`SETUP_OPENCLAW_VPS.md`](./SETUP_OPENCLAW_VPS.md)
- **Automation script (Ubuntu):** [`openclaw-setup.sh`](./openclaw-setup.sh)

## Quick start

```bash
# On the VPS (as root)
apt update && apt install -y curl
curl -fsSL https://raw.githubusercontent.com/noahvandal/ai_resources/main/openclaw/openclaw-setup.sh | sudo bash
```

Then follow the script’s manual steps to run:

```bash
openclaw onboard --install-daemon
```
