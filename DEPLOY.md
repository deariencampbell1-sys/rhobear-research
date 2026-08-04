# research — static research/landing docroot

Live path: `/var/www/research` on rhobear-vps.
Served by Caddy: `research.rhobear.ai`.
Pure static HTML — no build step, no backend, no secrets.

## Deploy
```bash
ssh rhobear-vps 'cd /home/slang/rhobear-research && git pull && ./deploy.sh'
```
