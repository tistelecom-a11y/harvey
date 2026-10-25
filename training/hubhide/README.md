# HubHide VPN — Harvey training snapshot

Config and skill files produced for hubhide.com (built from the public site on 2026-10-25).
Harvey keeps these paths gitignored; this folder is a backup copy. To apply:

```bash
cp training/hubhide/harvey.local.yaml ./harvey.local.yaml
cp training/hubhide/product_knowledge.md skills/product_knowledge.md
cp training/hubhide/competitive_intel.md skills/competitive_intel.md
cp .env.example .env   # then fill GMAIL_* or SMTP_*, and an email verifier key
```

Competitor cards are category-level inferences, not claims taken from hubhide.com.
