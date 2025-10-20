# SecuriPath — Detection Artifacts & IR Examples

This repository contains sanitized detection artifacts, incident response summaries, and reproducible lab examples developed as part of SecuriPath's defensive labs.

## Contents
- `IR-summary/` — One-page sanitised IR summaries (PDF).
- `artifacts/` — Detection rules & saved searches (Suricata, Sigma, Splunk).
- `timeline/` — Incident timelines and playbooks.
- `pcaps/` — (optional) example pcaps for reproduction.

## Example artifact
- **Token replay detection (Splunk)** — saved search in `artifacts/splunk/token_replay_saved_search.txt`.
- **Suricata rule** — `artifacts/suricata/token_replay.rule`
- **Sigma rule** — `artifacts/sigma/token_replay_sigma.yml`

## How to use
1. Review the IR summary (IR-summary/IR_summary_AI_E-Reader_Sanitised.pdf).  
2. Load the Splunk saved search into a test Splunk instance (or adapt to Elastic).  
3. Review the Suricata rule with your network sensor and tune thresholds before production use.

## Mapping to MITRE ATT&CK
Each artifact includes a short mapping to ATT&CK techniques (see each file header).

## Contact
Osama Bin Zahid — your-email@example.com — [LinkedIn](https://www.linkedin.com/in/osamakhan553)
