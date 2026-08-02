<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/LIVCK/.github/main/profile/assets/livck-logo-light.svg">
  <img alt="LIVCK" src="https://raw.githubusercontent.com/LIVCK/.github/main/profile/assets/livck-logo-dark.svg" width="230">
</picture>

### Uptime monitoring and incident communication for digital services.

**Detect, inform, resolve.**

<br>

[//]: # ()
[//]: # ([![Self-Hosted]&#40;https://raw.githubusercontent.com/LIVCK/.github/main/profile/assets/badge-self-hosted.svg&#41;]&#40;https://livck.com/statuspage&#41;)

[![Cloud · Beta](https://raw.githubusercontent.com/LIVCK/.github/main/profile/assets/badge-cloud.svg)](https://livck.cloud)

[//]: # ([![Docs · Self-Hosted]&#40;https://raw.githubusercontent.com/LIVCK/.github/main/profile/assets/badge-docs-self-hosted.svg&#41;]&#40;https://help.livck.com&#41;)

[//]: # ([![Docs · Cloud]&#40;https://raw.githubusercontent.com/LIVCK/.github/main/profile/assets/badge-docs-cloud.svg&#41;]&#40;https://docs.livck.cloud&#41;)

[![Discord](https://raw.githubusercontent.com/LIVCK/.github/main/profile/assets/badge-discord.svg)](https://discord.livck.com)

[//]: # ()
[//]: # ([![LIVCK Status]&#40;https://status.livck.com/api/v3/badge/status?style=flat&#41;]&#40;https://status.livck.com&#41;)

[//]: # ([![LIVCK Uptime]&#40;https://status.livck.com/api/v3/badge/uptime?style=flat&days=90&#41;]&#40;https://status.livck.com&#41;)

[//]: # (<sub>Every badge on this page is served by LIVCK, the two above live from our own status page. No third party involved.</sub>)

</div>

[//]: # (---)

<table>
<tr>
<td width="62%">

### Hi, we're LIVCK 👋

Most teams pay two vendors: one that checks whether things are up, and another that tells customers when they aren't. We built both into one tool: monitoring, incidents, and a status page your customers are willing to look at.

We're a German company. Data protection isn't a checkbox we added late, it's why the product is shaped the way it is. Run it on your own box and nothing leaves your network. Run it in our cloud and it stays in German data centres.

Two editions. **Both start at €0**, and neither is crippled to sell you the other.

</td>
<td align="center">

<img src="https://raw.githubusercontent.com/LIVCK/.github/main/profile/assets/livi-wave.svg" width="150" alt="LIVI waving">

<sub>This is **LIVI**.<br>She waves while everything's green.</sub>

</td>
</tr>
</table>

---

## Two ways to run it

<table>
<tr>
<th width="50%">🖥️ &nbsp; LIVCK Self-Hosted</th>
<th width="50%">☁️ &nbsp; LIVCK Cloud</th>
</tr>
<tr>
<td valign="top">

**Your server. Your network. Your data.**

Docker Compose on any Linux box, live in about five minutes. The free tier is free forever: no trial clock, no feature gating, every check type included.

The honest entry point: if your compliance people say "nothing leaves the building", this is the one.

`livck.com` · [Install guide →](https://livck.com/statuspage)

</td>
<td valign="top">

**No server, no maintenance, considerably more depth.**

Checks from several independent locations, tighter intervals, server agents reporting from inside your hosts, backups and updates handled for you.

Currently in **beta**. The free plan covers 20 services without a credit card; access runs through the waitlist for now.

`livck.cloud` · [Join the beta →](https://statuspage.de/en#waitlist)

</td>
</tr>
</table>

> [!NOTE]
> **Self-hosted and Cloud differ in more than who runs the server.**
>
> Self-hosted watches your services from one vantage point and does that job well. The Cloud sees things a single box can't: agents reporting from inside your servers, distributed probes that vote before an alert goes out, longer history, deeper integrations.
>
> Same brand, same green, different depth.

---

## From weekend project to enterprise

|                      | Self-Hosted                                    | Cloud                                                 |
| -------------------- | ---------------------------------------------- | ----------------------------------------------------- |
| **Starts at**        | €0, forever, 20 monitors                       | €0 in beta, 20 services                                |
| **Runs on**          | Your Docker host                               | German data centres, managed                           |
| **Vantage point**    | One: your server                               | Several independent locations, majority vote           |
| **Check interval**   | Minute-level                                   | 30 s on standard plans, down to 10 s on Enterprise     |
| **Server agents**    | –                                              | ✅ Metrics from inside the host                        |
| **Updates, backups** | Auto-updater, the box is yours                 | Handled for you                                        |
| **Your data**        | Never leaves your network                      | Stays in Germany, GDPR by design                       |
| **Scales to**        | Enterprise plans, own infrastructure           | Enterprise, dedicated setup, priority support          |
| **Good fit for**     | Homelabs, agencies, regulated or isolated envs | Teams who want monitoring as a platform, not a widget  |

Every check type is included in **every** plan, including the free one. We don't sell uptime back to you in slices.

## Meet LIVI

<table>
<tr>
<td align="center" width="26%">

<img src="https://raw.githubusercontent.com/LIVCK/.github/main/profile/assets/livi-idle.svg" width="130" alt="LIVI">

</td>
<td>

LIVI is our mascot. The antenna is reception, the lamp on top is transparency, and that lamp carries the same five states your status page does.

Deliberately **no eye** as a metaphor. Monitoring plus an eye reads as surveillance, which is the wrong signal for a product built around GDPR by design.

One rule matters more than the rest: **LIVI only moves while everything is green.** During an incident she stands perfectly still. A mascot that waves and hops through an outage doesn't look friendly, it looks clueless.

</td>
</tr>
</table>

| State           | Colour    | LIVI does                            |
| --------------- | --------- | ------------------------------------ |
| 🟢 Operational  | `#00E091` | Breathes, blinks, waves now and then |
| 🟡 Degraded     | `#FFC53D` | Wide eyes, still                     |
| 🟠 Partial      | `#FF9040` | Worried, antenna low                 |
| 🔴 Major        | `#FF5C5C` | Worried, no movement at all          |
| 🔵 Maintenance  | `#5B9BFF` | Awake and busy, this one is on purpose |

Every asset is a single self-contained SVG: CSS animation, no Lottie, no JavaScript, no web font to download, under 4 KB gzipped, and `prefers-reduced-motion` is built in.

---

## How we compare

We keep a side-by-side against Atlassian Statuspage, Better Stack, UptimeRobot, Instatus, Uptime Kuma, Hyperping, Oh Dear, incident.io and others, including the parts where they beat us.

**[See all comparisons →](https://statuspage.de/en/alternatives)**

---

<div align="center">

### Say hi

[Discord](https://discord.livck.com) · [X / Twitter](https://twitter.com/LIVCKCOM) · [Self-Hosted docs](https://help.livck.com) · [Cloud docs](https://docs.livck.cloud) · [Status](https://status.livck.com) · [support@livck.com](mailto:support@livck.com)

<br>

<img src="https://raw.githubusercontent.com/LIVCK/.github/main/profile/assets/livi-cheer.svg" width="80" alt="LIVI">

<sub>**LIVCK** — Made in Germany · GDPR by design · © 2020–2026</sub>

</div>
