# A1 Telecom — Harvey training snapshot (v2, 2026-10-25)

Config and skill files for a1call.me. v2 replaces the 2026-10-25 site scrape with the company's approved public wording:
no prices in emails, invoices without VAT, no phone number, no unverified percentages, legal CLI only (local DID + KYC),
voice-AI developers and call centres as the core segment, pilot geography Ukraine / Moldova / Georgia / Poland,
approval mode only, LinkedIn off.

Harvey keeps the live paths gitignored; this folder is the stored copy. To make A1 Telecom the active product:

```bash
cp training/a1call/harvey.local.yaml ./harvey.local.yaml
cp training/a1call/product_knowledge.md skills/product_knowledge.md
cp training/a1call/competitive_intel.md skills/competitive_intel.md
```

Before the first send: replace `persona.email` with the mailbox on the dedicated sending domain and set
`channels.email.warmup.start_date`. Keep `require_approval: true`.

Harvey runs one product at a time; switching back is the same three copies from `training/hubhide/`.
Competitor cards are category-level, not claims about specific vendors.
