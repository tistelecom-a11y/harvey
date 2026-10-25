# A1 Telecom — Harvey training snapshot

Config and skill files produced for a1call.me (built from the public site, en/ru, on 2026-10-25).
Harvey keeps the live paths gitignored; this folder is the stored copy. To make A1 Telecom the active product:

```bash
cp training/a1call/harvey.local.yaml ./harvey.local.yaml
cp training/a1call/product_knowledge.md skills/product_knowledge.md
cp training/a1call/competitive_intel.md skills/competitive_intel.md
```

Harvey runs one product at a time; switching back is the same three copies from `training/hubhide/`.
Competitor cards are category-level inferences, not claims taken from a1call.me.
