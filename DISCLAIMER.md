# ⚠️ Disclaimer & Liability Limitation

**Use at your own risk.** The code, workflows, and scripts in this repository (`n8n-smartlead-campaign-ab-test-winner-auto-promoter`) are provided for educational and architectural demonstration purposes.

## No Liability

The author and dhRobin Systems accept no responsibility or liability for any direct, indirect, incidental, or consequential damages that result from using, misusing, or deploying these scripts. This includes, without limitation, campaigns left paused, interrupted or delayed sending, changed or lost variant splits, promotion of a variant that performs worse, lost pipeline or revenue, deliverability or domain reputation damage, anti-spam or privacy regulatory claims, exposure of API keys or webhook URLs, service interruptions, and API rate-limit or quota exhaustion.

## No Warranty

All software, n8n JSON blueprints, JavaScript modules and prompts are provided "AS IS", without warranty of any kind, express or implied. This includes, but is not limited to, warranties of merchantability, fitness for a particular purpose, and non-infringement.

No warranty is given that statistical decisions are correct; that significance tests, corrections and thresholds suit your data, volumes or repeated daily evaluation; that Smartlead analytics are complete, timely or attributed to the right variant; that the sequence save payload matches Smartlead's current API contract; that existing copy, delays and splits are preserved; that a paused campaign is resumed; or that notifications are delivered.

## Production Testing Required

Always test thoroughly in an isolated staging environment, such as a dedicated Smartlead test campaign, with `SANDBOX_MODE=true` and `DRY_RUN=true` enabled, before you connect live Smartlead credentials or set `PROMOTE_WINNERS=true`. Compare the per-variant counts with the Smartlead Analytics tab, inspect every save payload against the live campaign, apply the first live change to a single campaign, and confirm in Smartlead that the copy is unchanged and the campaign is active again.

Treat every automated decision as a recommendation that a person must be able to review and reverse. Statistical significance is not proof that one message is better for your business.

## Third-Party APIs & Compliance

You alone are responsible for complying with the terms of service, rate limits, data privacy regulations (GDPR/CCPA and equivalents), anti-spam and electronic marketing laws (CAN-SPAM, PECR, CASL and equivalents), and security policies of Smartlead, Slack, your webhook receiver and any connected services. That includes:

- limiting automation to campaigns your team has explicitly opted in;
- keeping a valid unsubscribe mechanism and accurate sender identity in every variant;
- securing, rotating and restricting access to the Smartlead API key, Slack webhook URL and alert webhook token;
- limiting access to n8n execution data and applying a retention period that matches your policies;
- monitoring deliverability after volume shifts to a single variant;
- reviewing every automatically changed campaign.

## No Affiliation

Smartlead, Slack and n8n are trademarks of their respective owners. This project is independent and is not affiliated with, endorsed by, or sponsored by any of them. All campaigns, identifiers, subject lines, email bodies and figures in the fixtures, sample payloads and pinned data are fictitious.

## Not Professional Advice

Nothing in this repository constitutes legal, statistical, marketing-compliance, security, or financial advice. Consult qualified professionals for your specific circumstances.

---

Released under the MIT License. Copyright (c) 2026 DH Robin (dhRobin Systems). See [LICENSE](LICENSE).

Full text: DISCLAIMER.md · Licensed under the MIT License. License: MIT © 2026 dhRobin Systems · Provided as-is, see the disclaimer.
