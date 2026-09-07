# Hopper Day — Research Trail

Sanitized, sourced notes behind the landing page. Full working notes live in the private `notes` repo. This file is the public, forkable version.

## The thesis

Grace Hopper spent her career lowering the barrier between human intent and software: machine code → compilers → COBOL → *talking to your computer*. Omarchy 4 ("Quattro") plus natural-language agents is the next step in that same line. The five-year-old laptop is the proof, not the point.

## Why August 14

On August 14, 2026, Omarchy 4.0 shipped — one of the most successful Linux distribution launches on record:

- ~100,000 ISO downloads in the first week, ~200,000 by day 18
- ~$15M in pledges to the Omacom Foundation (patrons including Tobi Lütke, Patrick Collison, Michael Dell, Jack Dorsey, Matthew Prince)
- DHH called it one of the greatest releases of his career

Install: under a minute on fast modern machines, no more than five minutes on older hardware. Timed installs: 45 seconds (DHH, high-end AMD), 38 seconds (Frandroid, Framework 13). On a five-year-old machine: two to three minutes. No TPM 2.0 required.

## The indictment: e-waste and the TPM lockout

- ~400 million PCs can't officially run Windows 11 (no TPM 2.0, no Secure Boot, unsupported CPU)
- Windows 10 support ended October 14, 2025
- PIRG estimates up to 1.6 billion pounds of additional e-waste from machines that still work fine
- Perfectly good hardware, headed for the dump, over a software policy — a two-dollar flash drive and two minutes away from a machine that talks back

## The hypocrisy

The same industry that spent decades preaching "green" goes quiet the moment its own power bill shows up. Carbon-tax talk vanished the second AI data centers needed electricity. Virginia started taxing data-center power in July 2026; federal proposals followed in August 2026.

## The investment gap

AI investment this year is on track for ~$1 trillion globally (Goldman Sachs, August 2026). We compared that against what the world spends on everything that keeps us alive, sane, and curious:

| Category | Annual spend | vs. AI (~$1T)
|---|---|---
| AI investment (2026) | ~$1T | —
| Global public education | ~$5.8T | ~6× (but education grows <2%/yr; AI doubles)
| Food systems (climate finance) | ~$95B | ~10×
| Private capital into agriculture | ~$2B | ~500×
| Global cancer research | ~$6–7B | ~150×
| Type 1 (juvenile) diabetes research | ~$350M | ~2,800×
| All neglected-disease R&D (malaria, TB, etc.) | ~$4.3B | ~230×
| US public arts funding | ~$1.7B | ~600×
| US EPA | ~$8.8B | ~114×
| US Fish & Wildlife Service | ~$1.65B | ~600×
| USDA APHIS Animal Welfare (42M, 77 inspectors, 17k facilities) | ~$42M | ~24,000×
| NOAA deep-ocean program | ~$46M | ~22,000×
| NASA Science | ~$7.25B | ~138×
| NASA (whole agency) | ~$24B | ~42×

**The pattern:** almost everything existentially necessary — feeding people, curing disease, stewarding the planet, protecting animals, exploring the ocean, reaching the stars, the arts, the kids — is funded at a fraction of what we spend on one speculative buildout. Education is the only public good that competes on absolute dollars, and even there the growth-rate gap is brutal and there's still a ~$100B annual hole to hit the UN's education targets.

**The synthesis:** we checked the budget for everything that keeps us alive, sane, and curious — and every one of them is a rounding error next to what we spend teaching machines to think. The machines aren't the problem. The priority is.

**DRAM angle:** ~70% of global memory now goes to data centers; HBM eats 3–4× the wafer area of standard DRAM. Every machine kept out of the landfill is one less DRAM stick the fabs have to fight over. Omarchy 4 doesn't spawn new fabs — but it relieves demand pressure by putting capable hardware back to work.

## Sources (selected)

- Goldman Sachs — AI investment ~$1T (Aug 2026)
- BCA Research — AI would need ~$10T in annual sales to justify the buildout (~global food spend)
- PIRG — 1.6B lbs e-waste estimate from Windows 11 lockout
- UNESCO — ocean is 95% of the biosphere, gets <1% of research budgets
- FY2026 US appropriations — EPA, FWS, APHIS, NASA Science figures
- Omarchy install timings — DHH (45s), Frandroid/Framework 13 (38s), official manual (<1 min / ≤5 min)

## Handoff

This is MIT licensed. Fork it, restyle it, translate it, add a demo, hand it to someone else. Hopper Day shouldn't belong to one person. The full research trail lives in the private `notes` repo.
