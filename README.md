# chargefrance

Publishes **https://fastchargefrance.com** (Fast Charge France) on GitHub Pages.

This repo holds only `.github/workflows/deploy.yml`, a copy of
[`sites/france/deploy.yml`](https://github.com/PartyTrix/madeira-chargers/blob/main/sites/france/deploy.yml)
from [PartyTrix/madeira-chargers](https://github.com/PartyTrix/madeira-chargers), where all the code lives.
Every 15 minutes it builds the site from that repo with France's open charger data and live status, and deploys it.
Run it by hand from the Actions tab to publish a change straight away.
