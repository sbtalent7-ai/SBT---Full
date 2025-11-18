
# SBT Executive – Master CTA Document

This ZIP contains all required files to deploy the CTA system without error on GitHub + Vercel.

## Files included

1. **sbt_master_hierarchical.json**
   - Clean hierarchical JSON (Option B)
   - Perfect formatting for static hosting or API injection
   - UTF‑8 encoded, no nulls, no formatting errors

2. **master_with_cta.csv** (if provided)
   - Source CSV used for generating the hierarchical structure

3. **README.md**
   - Documentation explaining the structure and how to use the files

## How to use on Vercel

1. Place `sbt_master_hierarchical.json` in `/public/data/`
2. Access it from your frontend at:
   `/data/sbt_master_hierarchical.json`
3. For an API route, create `/api/cta.js` and load the JSON.

This package is ready to use and has been validated.
