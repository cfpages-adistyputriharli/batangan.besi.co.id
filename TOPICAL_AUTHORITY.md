# Topical Authority — batangan.besi.co.id

## Role and boundary

`batangan.besi.co.id` should be a national Indonesian reference and procurement-support hub for solid iron/steel bar products: round bar and shafting, square/nako bar, twisted decorative bar, reinforcing bar, grades, dimensions, tolerances, mass, selection, cutting, machining, forming, heat treatment, welding, corrosion, procurement, inspection, handling, use, repair, reuse, and recycling.

Existing `/as-s45c/`, `/as-st42/`, `/nako/`, `/nako-ulir/`, and `/besi-beton/` routes retain transactional intent after canonical review. Educational articles do not target city sales. The site does not replace a metallurgist, licensed structural engineer, welding engineer, machinist, laboratory, reinforcement designer, inspector, or K3 professional. It must not infer grade, capacity, weldability, heat-treatment condition, or conformity from appearance or a trade name.

## Evidence audited

- Canonical candidate `cfpages-adistyputriharli/batangan.besi.co.id`, `main`, commit `fa27743e831e75719f101f908fda7f8788ee788f`; portfolio inventory confirms Syamsul ownership and live HTTP 200, but Cloudflare source binding was unavailable.
- 3,482 tracked paths: 2,710 HTML and 26 XML files.
- 2,453 root HTML files: homepage, `hello-world.html`, and five location-swapped sales families with roughly 490 variants each—AS S45C, AS ST42, besi beton, nako, and nako ulir.
- Five product routes plus `/tentang/`, `/kontak/`, `/jangkauan/`, feed, and 404 routes.
- 252 category-tree files, two author files, and duplicated feed/archive surfaces.
- Thirteen post sitemaps list 2,441 URLs; `page-sitemap.xml` lists nine; `sitemap-complete.xml` lists 2,642; sitemap index lists 13 post maps plus page map. The surfaces are inconsistent.
- No technical article collection, mill certificates, current standards, test reports, calculations, machining/heat-treatment records, welding procedures, inspection records, or verified case studies were found.

Search Console, analytics, conversions, backlinks, actual inventory, prices, supplier approvals, and repository-to-production parity were unavailable and remain evidence gates.

## Existing coverage and risks

| Existing URL/pattern | Observed role/problem | Decision | Destination/owner | Verification needed |
|---|---|---|---|---|
| `/` | Broad bar-product commercial overview | expand | Commercial overview plus 14 knowledge hubs | Live canonical, navigation, leads, deployment source |
| Five product routes | Useful transactional owners but shallow product evidence | keep | One canonical commercial owner per product | Stock, certificates, queries, links, leads |
| About 2,450 `jual-<produk>-<lokasi>.html` pages | Location-swapped doorway risk | manual review | Relevant canonical product route | Unique local proof, indexation, traffic, leads, redirect map |
| `hello-world.html` | Default WordPress residue | remove | Homepage only if history requires redirect | Live status, links, traffic |
| Category/archive/feed routes | Repeated thin discovery surfaces | noindex | Curated product or learning hubs | Navigation dependencies and index status |
| Conflicting sitemap sets | 2,441 post URLs versus 2,642 complete URLs | manual review | One generated canonical sitemap | Search Console submission and final URL states |
| Grade-named product pages | Trade/product labels may imply unsupported equivalence/properties | expand | Commercial route plus BESB-02 evidence hub | Current standard, product form, supply condition, certificates |

## Coverage matrix

| Lens | Topic owners |
|---|---|
| Definitions, taxonomy, anatomy | BESB-01 |
| Grades, standards, certificates, traceability | BESB-02 |
| Dimensions, tolerances, mass, quantity | BESB-03 |
| Round bar, shafting, AS grades | BESB-04 |
| Nako and decorative/twisted bars | BESB-05 |
| Reinforcing bar | BESB-06 |
| Properties, selection, failure behavior | BESB-07 |
| Cutting and machining | BESB-08 |
| Forming and heat treatment | BESB-09 |
| Welding and joining | BESB-10 |
| Corrosion and surface protection | BESB-11 |
| Procurement, QA, testing, handover | BESB-12 |
| Transport, handling, storage, K3 | BESB-13 |
| Inspection, repair, reuse, recycling | BESB-14 |

## Topical map

| Topic ID | Parent topic | Reader outcome | Required subtopics/questions | Evidence/formats | Boundary | Article target |
|---|---|---|---|---|---|---:|
| BESB-01 | Solid bar taxonomy and terminology | Distinguish bar products and trade labels | Round, square, hex, flat, shafting, rebar, nako, twisted bar, wire rod; hot/cold finished; rolled/forged/drawn; product versus component | Taxonomy; cross-sections; glossary | Grade belongs to BESB-02; product sales remain existing routes | 6 |
| BESB-02 | Grades, standards, certificates, traceability | Verify material identity | Standard/grade/form/edition; chemistry/properties; supply condition; mill certificate; heat/batch; marking; substitutions; unknown stock | Annotated certificate; evidence chain; crosswalk template | No equivalence/conformity without current documents and competent approval | 6 |
| BESB-03 | Dimensions, tolerances, mass, and quantity | Measure and calculate a checkable order | Nominal/actual size; diameter/across-flats; ovality; straightness; length; mass; density assumptions; piece count; calibration; cutting allowance | Diagrams; formulas; measurement sheet; calculator specification | Does not select grade/size; BESB-07 owns selection | 6 |
| BESB-04 | Round bar, shafting, S45C and ST42 labels | Compare round-bar products by evidence | AS/assental; S45C/ST42 ambiguity; surface finish; dimensional precision; straightness; machining; heat treatment; shaft use; receiving | Product matrix; label audit; receiving checklist | No shaft design or grade equivalence; BESB-07 owns selection | 6 |
| BESB-05 | Square/nako and twisted decorative bars | Select and fabricate square/twisted bar responsibly | Square geometry; corner radius; straightness/twist; nako ulir; decorative versus structural role; forging/twisting; welds; coatings; gates/grilles | Profile atlas; process diagrams; decision matrix | No security/structural design; competent system designer owns it | 6 |
| BESB-06 | Reinforcing bar systems | Verify and manage rebar from delivery to placement | Plain/deformed bar; markings; diameter/mass; ribs; bendability; cutting/bending; couplers/weld limits; storage; placement traceability; corrosion | Marking guide; receiving/forming checklists | Reinforced-concrete design remains with licensed designer | 6 |
| BESB-07 | Properties, selection, and failure behavior | Translate function into material evidence | Strength; stiffness; ductility; toughness; hardness/wear; fatigue; temperature; corrosion; machinability; weldability; availability; substitutions | Requirements matrix; failure map; decision tree | Does not prescribe grade or capacity; BESB-02 verifies identity | 6 |
| BESB-08 | Cutting and machining | Plan controlled material removal | Saw/thermal cutting; drilling; turning; milling; stock allowance; datum; hardness/condition; heat effects; burrs; distortion; coolant/contamination; inspection; traceability | Process matrix; route card; inspection map | No machine parameters; approved process owns them | 6 |
| BESB-09 | Bending, twisting, forging, and heat treatment | Control shape/property changes | Bendability; direction; tooling; springback; hot/cold work; twisting; forging; anneal/normalize/quench/temper concepts; distortion; hardness; trials; records | Process flow; trial plan; condition map | No temperatures/radii/cycles without qualified procedure | 6 |
| BESB-10 | Welding and mechanical joining | Request qualified joining evidence | Weldability; carbon-equivalent concept; WPS/PQR; welder; consumables; fit-up; preheat/interpass concepts; defects/NDT; repair; threads; keys; couplers | Evidence chain; joint diagrams; defect atlas | Not welding instructions; approved design/procedure owns values | 6 |
| BESB-11 | Corrosion, coatings, and storage preservation | Match protection to exposure and geometry | Atmospheric/galvanic/crevice corrosion; scale; surface preparation; paint/plating/galvanizing/oil; cut ends; threads; contacts; storage stains; inspection/repair | Mechanism map; exposure survey; coating checklist | No service-life or coating prescription without verified system evidence | 6 |
| BESB-12 | Procurement, QA, testing, and handover | Buy and release traceable bar stock | RFQ/BOM; quote normalization; supplier; certificates; receiving; sampling; chemistry/tensile/hardness/impact; dimensions; calibration; NCR; dossier; lifecycle cost | Templates; ITP; test map; bid matrix | No live price, supplier endorsement, or acceptance value | 6 |
| BESB-13 | Transport, handling, storage, and K3 | Protect long/heavy stock and people | Bundle identity/mass; lifting points; rolling/whip/sharp hazards; restraint; racks/chocks; segregation; weather; manual handling; cutting/hot-work risks; rescue | Logistics plan; rack layout; hazard map | No lift/stack limits or rigging selection without competent plan | 6 |
| BESB-14 | Inspection, repair, reuse, and end of life | Decide whether stock/component can remain, be repaired, reused, or recycled | Baseline; corrosion; bends/cracks/wear; unknown steel; repair; straightening; weld repair; reuse qualification; salvage; sorting; contamination; recycling; records | Condition map; decision tree; reuse dossier | Visual inspection never proves grade/capacity/reuse suitability | 6 |

## Related-domain opportunities

| Domain | Distinct role | Safe relationship |
|---|---|---|
| `besi.co.id` | Parent material hub | Link for broad steel fundamentals while retaining bar-specific depth here |
| `batang.besi.co.id` | Independent long-product subdomain | Cross-domain overlap is allowed; coordinate viewpoint without suppressing topics |
| `kawat.besi.co.id` | Wire products | Link when bar diameter/manufacturing transitions into wire products |
| `konstruksi.besi.co.id` and `struktural.besi.co.id` | Whole structural systems | Link for member/reinforcement design; retain product identity here |
| Welding/fabrication properties | Service/process delivery | Link for workshop services while keeping bar-process literacy here |

## Consolidation plan

1. Confirm Cloudflare project and production source.
2. Join all URLs with Search Console, analytics, backlinks, leads, and product-stock evidence.
3. Preserve one transactional owner for each five product families.
4. Consolidate unsupported location variants to product owners with mapped redirects or remove/noindex based on evidence.
5. Remove/default-redirect `hello-world.html`; curate useful hubs and noindex thin archives/feeds.
6. Replace conflicting sitemap sets with one final canonical inventory.
7. Collision-check every article against retained routes, titles, H1s, redirects, and Search Console queries.

## Internal-link architecture

- Homepage → five commercial routes and 14 topic hubs.
- BESB-01 → BESB-02 → BESB-03 → relevant product hub BESB-04 to BESB-06.
- Product hubs → BESB-07 selection → BESB-08/BESB-09 processing → BESB-10 joining → BESB-11 protection.
- BESB-12 procurement → BESB-13 delivery/storage → BESB-14 inspection/reuse.
- Every article links to its hub and context-specific `Related IDs`; geographic pages never spawn local educational copies.

## Evidence and editorial standards

1. Label observations, sourced facts, formulas, examples, judgments, and hypotheses.
2. Use current primary standards, manufacturer data, certificates, laboratory reports, approved drawings/procedures, and original inspection evidence with edition/date/scope.
3. Never infer grade, properties, condition, capacity, weldability, or conformity from appearance, sparks, magnet response, hardness alone, or trade name.
4. Equivalence requires edition-aware comparison of product form, supply condition, chemistry, properties, tests, tolerances, and competent approval.
5. Quantity calculations state geometry, units, density assumption, tolerance, measured/theoretical basis, waste, and rounding.
6. Machining/forming/welding articles require verified identity, approved procedures, qualified personnel where applicable, calibrated equipment, traceability, inspection, and NCR control.
7. Corrosion claims require exposure, base metal, preparation/protection system, geometry, contacts, damage, maintenance, and inspection evidence.
8. Structural/rebar use requires licensed design and governing documents; no generic capacities or detailing values.
9. Procurement/testing pages distinguish certificate, supplier report, third-party test, sampling limits, laboratory competence, uncertainty, and acceptance owner.
10. Handling/K3 requires verified bundle mass/geometry, stable racks/restraint, rolling/whip/sharp/hot-work controls, competent lifting plan, exclusion, and rescue.
11. Reuse requires provenance, identity, dimensions, condition, history, defects, new use, testing, and competent approval.
12. Safety/standards/test/price-sensitive pages show author, reviewer, sources, review date, and correction path.

## First bounded publication cluster

Publish 12 P0 assets: BESB-01-A01, BESB-01-A02, BESB-02-A01, BESB-02-A02, BESB-03-A01, BESB-03-A02, BESB-04-A01, BESB-05-A01, BESB-06-A01, BESB-10-A01, BESB-12-A01, and BESB-13-A01. This connects taxonomy, identity, measurement, all existing product families, qualified joining, purchasing, receiving, and safe handling. Monitor valid indexation, impressions by intent, checklist/tool use, qualified enquiries, and query overlap—not ranking alone.

## Definition of done

- Fourteen hubs and 84 distinct briefs are published.
- Every retained route/archive/location has one canonical owner; no geographic brief exists.
- One canonical sitemap contains only final indexable URLs.
- Identity, process, joining, corrosion, testing, handling, K3, and reuse claims pass evidence gates.
- First cluster is published and internally linked before later waves.
- Repository-to-production parity and route/link/canonical/sitemap checks are documented.
