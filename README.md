# Ashraff (nitroz3us)

I build AI tooling for security operations at EY in Singapore. My background is threat hunting, threat intelligence and SOC work.

[mdashraff.com](https://mdashraff.com) · [CTF writeups](https://nitrozeus.gitbook.io/ctfs/) · [LinkedIn](https://www.linkedin.com/in/muhammad-ashraff-69586a17a/) · [Mastodon](https://infosec.exchange/@nitroz3us)

## What I build

| Project | What it does | Where |
| --- | --- | --- |
| **Huntsman** | Agentic AI platform for threat hunting on live Splunk. An LLM agent runs its own searches through tool calling over MCP, inside a harness with read-only guardrails and human-in-the-loop authorization. Outputs are grounded in source citations. | Internal |
| **Heartbeat** | LLM pipeline for the weekly threat bulletin. Collects security news, CVEs, CISA KEV entries and ransomware victims, scores client relevance with an LLM, and drafts the bulletin as slides, PDF and email for human review. | Internal |
| **ShadowPulse** | Look up an IP, domain or hash once and get VirusTotal, Shodan, GreyNoise and AbuseIPDB in one view. | [Live](https://shadow-pulse-py.vercel.app/) |
| **docstack** | Merge, splice and rotate PDFs in the browser. Files never leave your device. | [Live](https://docstack.tools) · [Code](https://github.com/nitroz3us/docstack) |
| **disable-windows-defender** | PowerShell script that switches Defender off inside malware analysis VMs. | [Code](https://github.com/nitroz3us/disable-windows-defender) |
| **GPThreatIntel-Summarizer** | Summarises threat intelligence reports with OpenAI. | [Code](https://github.com/nitroz3us/GPThreatIntel-Summarizer) |
| **VoicePointGPT** | Writes a script and voiceover for each slide of a PowerPoint deck. | [Code](https://github.com/nitroz3us/VoicePointGPT) |
| **telegram-budget-tracker** | Telegram bot for logging expenses and tracking a monthly budget. | [Code](https://github.com/nitroz3us/telegram-budget-tracker) |

## What I write

- [Your Agent Is Only as Good as Its Harness](https://www.mdashraff.com/blog/harness-engineering): why the system around the model decides whether an AI agent is reliable
- [How Scattered Spider Led Me to The Com](https://www.mdashraff.com/research/scattered-spider-to-the-com): public reporting on Scattered Spider, ShinyHunters and LAPSUS$, consolidated
- [Ebolas Stealer](https://www.mdashraff.com/blog/ebolas-infostealer-overview) and [DarkCrystal RAT](https://www.mdashraff.com/blog/dcrat-disguising-as-luna-grabber/): malware analysis

More at [mdashraff.com/blog](https://www.mdashraff.com/blog).
