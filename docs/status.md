# Status

Last updated: 2026-06-22

This page is the honest stocktake: what exists, what's been tested, what doesn't work yet. No polish, no "finished" product — a process in progress.

## What exists

| Component | Status | Notes |
|---|---|---|
| Sandwich base (ripstop + thermal batting) | ✅ Works | Sewn, topstitched along diagonals, holds its shape |
| Pattern (vector file) | ✅ Exists | Base: 2100 × 1000 mm + 500 mm head space, half-circle shape at the head end. Projectable via [patternprojector.com](https://patternprojector.com) |
| Sail batten mounts (loops) | ✅ Works | Sewn loops with Velcro, batten is slotted in |
| Head/foot section from kite offcut fabric | ⚠️ Works, visually inconsistent | Material comes from 4 retired kite wings donated by a kite school — colours/prints vary by donated piece |
| Continuous fabric tension | ❌ Unsolved | Only tensioned at the head end (via batten pressure), rest hangs loose — see [Open Problem #1](../README.md#open-problems) |
| Weatherproofing / seam sealing | ❌ Untested | Double-fold seam is mechanically stable, but not explicitly sealed for waterproofing |
| Long-term / field test | ❌ Not done | So far only set-up tests on hard ground (yard, plaza) |

## Materials list (current prototype)

- **Base, top layer:** Ripstop nylon, silver/metallic coated (reflects body heat)
- **Base, core:** thermal batting (insulation, not a substitute for a sleeping mat)
- **Base, bottom layer:** ripstop nylon, uncoated, 80 g/m²
- **Head/foot sections:** kite/paraglider offcut fabric (donated, material varies)
- **Battens:** sail battens, 35 × 2.9 mm profile, one each at head and foot
- **Connections:** Velcro strips (sewn onto loops, no adhesive points)
- **Seam:** double-fold seam (clean finish on both sides, more water-resistant than a simple seam)

## Tools / methods used

- Domestic sewing machine (no industrial equipment)
- Rotary cutter for fabric
- Projector + [patternprojector.com](https://patternprojector.com) to project the pattern directly onto fabric — replaces paper templates
- Baking parchment as a trick against the coated fabric side sticking while sewing (no special walking foot needed)

## Known issues in detail

### Fabric tension
The bivy currently only stands because of the batten pressing against the head section. That gives the head end some volume, but the rest of the fabric (toward the foot end) has no tension and hangs loose. Adding more battens would fix this, but increases manufacturing effort and cost — which goes against the core principle of "minimal production effort." Looking for: a geometric solution (e.g. a different arc shape, tension distributed through the pattern itself rather than extra hardware).

### Weight instead of fastening
A deliberate decision against stakes/guy lines, because these aren't practical in the intended use context (urban space, hard ground, no classic tent-pitching area). The user's own belongings (backpack etc.) are stored in the head section and provide the needed weight. Works in testing, but hasn't been checked across different wind conditions yet.

## Next steps

- [ ] Test alternative shapes for continuous tension without extra battens
- [ ] Solve seam waterproofing without adhesive tape
- [ ] First field test under real conditions (weather, uneven ground)
- [ ] Evaluate fabrication steps for small-batch production (see [Open Problem #3](../README.md#open-problems))
