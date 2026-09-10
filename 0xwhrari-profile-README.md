<div align="center">

# rari

`onchain dev` · `robinhood chain` · `tools`

building random useful shit around markets, wallets and new launches.

</div>

---

### working on

- new token scanners
- sniper / execution tools
- wallet tracking
- launch analytics
- CLI / TUI stuff
- Robinhood Chain infra & experiments

mostly interested in what happens **before the chart gets obvious**.

---

### projects

#### `SNIPE`

Robinhood Chain terminal for new launches.

Tracks fresh tokens and looks for early activity from strong / hot wallets.

```text
new token
   ↓
wallet activity
   ↓
GMGN / Pons / fomo / onchain data
   ↓
LOCK / TRACK / DROP
```

currently building.

---

#### `crowd`

CLI for checking who's actually behind token activity.

```bash
npx crowd read <token>
```

wallet count, holder activity, repeat wallets, sells, concentration.

no dashboard required.

---

### stack

```text
TypeScript
JavaScript
Node.js
Solidity

EVM
Robinhood Chain
RPC / logs / contracts

CLI / TUI
onchain data
market tooling
```

---

### rn

```text
Robinhood Chain
├─ launches
├─ wallets
├─ sniping
├─ Pons
├─ GMGN
├─ fomo
└─ raw chain data
```

trying to turn all of that into small tools i'd actually use myself.

---

<div align="center">

`0xwhrari`

build shit → test it → ship it

</div>
