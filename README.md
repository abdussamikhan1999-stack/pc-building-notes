# PC Building Notes

Notes distilled from a `/pcbg/` (PC Building General, 4chan `/g/`-style)
thread — part recommendations by category and tier, as of the thread date
(2026-09-12).

See [LINKS.md](LINKS.md) for the full raw link list.

## Read this before trusting the part picks below

`/pcbg/`'s general OP is a running community copypasta that gets reposted
thread-to-thread, and it's known for carrying **strong, often exaggerated
brand bias** — this instance is no exception:

- **"AVOID: AM5 CPUs and AMD CPUs in general until burning issues are
  resolved"** — there was a real socket-burning issue with some AM5
  boards/CPUs at one point, but "avoid AMD CPUs in general" is a sweeping
  overgeneralization from that, not a neutral engineering conclusion.
- **"Do not under any circumstances buy an AMD GPU for productivity
  applications"** — this is flatly not defensible as general advice. AMD
  GPUs are widely and successfully used for video editing, Blender (HIP/
  ROCm), and plenty of other productivity workloads; the *real* caveat is
  narrower — AMD lacks Nvidia's DLSS and dedicated path-tracing hardware
  specifically, which matters for gaming with those features, not
  productivity broadly.

Treat the CPU/GPU "AVOID" lines as this thread's opinion/meme, not settled
fact. The category-by-tier picks below (case, cooler, RAM, SSD, monitor,
PSU) are much more mundane/uncontroversial and worth taking at face value;
the CPU/GPU brand-exclusivity claims are the part to independently verify
before acting on.

## The actual process (per the thread's own instructions)

Before asking for build advice anywhere, the thread insists you post: a full
parts list (via **PCPartPicker**), your **monitor** (resolution/refresh rate
drives GPU tier choice), your **specific use case**, and your **budget +
country** (parts availability/pricing varies enormously by region) — posts
missing these get ignored. That's a genuinely good discipline to bring to
any build-advice request, on this thread or elsewhere.

## Part picks by category (09/2026 snapshot — this ages fast, re-verify before buying)

- **Case**: mATX picks (AP201, Lian Li A3, O11 Air Mini, XT M3, CH260), ATX
  picks (XT PRO Ultra, AIR 903, Lancool 217, Flux Pro, Y40, Meshify 3, 4000D
  FRAME), dual-chamber picks (Y60/70, Vision Compact, Antec C8) — dual-
  chamber cases separate the PSU/cables from the main compartment for
  cleaner airflow/cable routing.
- **CPU**: Core Ultra 5 250K Plus (budget) → Core Ultra 7 270K Plus (gaming)
  → Core Ultra 9 285K (workstation). *(See the bias caveat above — this
  list is Intel-only by the OP's own framing, not because AMD lacks
  competitive options at each tier.)*
- **Cooler**: AIO — Thermalright Frozen Edge (best value), Lian Li GA II
  Lite (premium), TRYX Panorama (if you want an LCD on the pump). Air/tower
  — Thermalright Phantom Spirit 120 SE, Noctua NH-D15 G2 (Noctua's
  successor to their long-standing flagship air cooler).
- **RAM**: DDR5 2×16GB CL30-6000 for gaming; step up to 2×32GB for
  workstation/high-end use.
- **SSD (OS drive)**: NM790 (budget) → SN7100 (mid) → SN850X (premium) →
  SN8100 (flagship) — a fairly standard budget-to-flagship NVMe ladder.
- **GPU, by target resolution**: RTX 5060 16GB (1080p) → RTX 5070 Ti 16GB
  (1440p) → RTX 5080 (4K) → RTX 5090 (path tracing/DLSS5-focused builds).
  *(Again: the blanket AMD-GPU exclusion is the thread's opinion, not fact —
  see caveat above.)*
- **PSU**: linked to hwbusters' ATX v3/PCIe 5-ready PSU picks (page didn't
  load from this environment — 403 — open directly; PCIe 5/ATX v3 matters
  specifically for the 12V-2x6 GPU power connector on newer high-end cards).
- **Monitor**: pcmonitors.info — an actively maintained review site
  covering panel type (OLED/IPS/VA), size/resolution combos (27"–34"
  ultrawide), and refresh rate (160–560Hz) with current-generation reviews
  (QD-OLED work/play hybrids, dual-mode-resolution monitors).
- **Case fans**: the thread's one-line advice — buy a case with good stock
  PWM fans rather than assuming you'll need to replace them immediately;
  reasonable, since case-fan upgrades are a common but often unnecessary
  first purchase.

## Build guide

Linked: `wiki.installgentoo.com/index.php/Build_a_PC` (redirects to
`igwiki.lyci.de` per this thread's own domain migration — the same wiki
family referenced in the earlier `/cyb/erpunk` and `/sqt/` threads' security
guides). Could not be fetched from this environment (404 after the
redirect) — open directly for the step-by-step assembly walkthrough.
