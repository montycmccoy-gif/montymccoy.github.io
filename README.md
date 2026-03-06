# ClawBot Public Assets

This repository hosts **only** the minimal public-facing files needed for ClawBot's Tesla OAuth integration:

- Tesla 3P public key PEM (`.well-known/appspecific/com.tesla.3p.public-key.pem`)
- OAuth callback handler (`callback.html`)

**Full ClawBot logic, scripts, secrets, and task-autonomy code live locally** on the MacMini (`~/ClawBot-Social`).

No private keys, tokens, API credentials, or executable code are stored here.

Purpose: Enable secure, third-party OAuth flow with Tesla for vehicle-requiring errands (coffee runs, pharmacy drops, multi-stop chains) via FSD/Robotaxi substrate — reclaiming daily time through true autonomy.

Grok 4.2 core (isolated, no external LLM influence) powers the reasoning/planning brain.
