# Supply-Secure High-Temperature Magnets

**A technical and commercial white paper from Colour**

Version 1.0 | 31 October 2026 | Author: Malik, Founder

**Evidence status:** Colour is pre-experimental. This paper separates what is established in the literature from what is a hypothesis we intend to test. It contains no Colour test data yet. Items marked *Proposed* are design targets we chose to test, not results. They must be confirmed with customers and our technical advisor before external distribution.

## 1. Executive summary

Sintered neodymium-iron-boron (NdFeB) magnets sit inside most high-performance electric motors, robots, drones and wind turbines. Their heat resistance depends on dysprosium (Dy) and terbium (Tb), heavy rare earths whose processing is concentrated in China and has been subject to export controls since April 2025.

Colour is developing a laboratory-scale route to high-temperature NdFeB magnets that use less heavy rare earth and incorporate recycled magnet scrap. Our approach combines two techniques that are individually documented in the literature: hydrogen-based processing of magnet scrap, and grain boundary diffusion of Dy/Tb.

Whether the combination can meet customer specifications repeatably, and whether it can be done without infringing existing patents, is not yet known. This paper sets out the reasoning, the risks, and the 18-month validation plan that will answer those questions.

## 2. The problem

**Demand is growing.** The IEA reports that demand for the magnet rare earths (Nd, Pr, Dy, Tb) has doubled since 2015 and is set to expand by roughly another third by 2030 under current policy settings [1].

**Supply is concentrated.** China dominates global rare earth magnet production, and published estimates of its share range from roughly 75% to over 90% depending on source and definition [2, 3]. In April 2025 it imposed export controls on seven heavy rare earths, including Dy and Tb, and on magnets containing them [1]. The controls were suspended for one year in November 2025 [4] and are due to return around 10 November 2026 unless extended [5].

**High-temperature grades are most exposed.** Industry reporting indicates that restricted Dy/Tb access puts disproportionate pressure on high-temperature magnet grades even when standard Nd magnets remain available [6]. Prices for Dy and Tb outside China have risen sharply as buyers compete for limited non-Chinese supply [7].

**Policy is tightening.** US defense sourcing restrictions on China-linked magnets are expected from January 2027 [7]. The EU plans for recycling to cover at least 25% of its annual permanent magnet consumption by 2030 [8]. China has also placed key magnet manufacturing technologies, including sintering and grain boundary diffusion, under technology export controls [9].

## 3. Technical background (established)

**Why Dy and Tb matter.** The magnetic phase of an NdFeB magnet is Nd2Fe14B. Coercivity, the resistance to demagnetization, falls as temperature rises. Dy and Tb have higher magnetic anisotropy than Nd, so concentrating them in the outer region of each grain makes it harder for reverse magnetic domains to form [11, 12].

**Grain boundary diffusion (GBD).** Instead of alloying Dy/Tb through the whole magnet, a Dy/Tb source is applied to the surface of a finished sintered magnet and heated, typically at about 700 to 1000 degrees C. The Nd-rich boundary phase liquefies and Dy/Tb travel along it, forming a hardened shell on each grain. This raises coercivity with only a small loss of remanence and uses substantially less heavy rare earth [12, 13]. Known limits include finite penetration depth in thick magnets and the extra process step after machining [11]. GBD is already used industrially and is covered by many patents [13].

**Hydrogen processing of magnet scrap (HPMS).** Exposed to hydrogen, sintered NdFeB breaks into a brittle, demagnetized hydride powder that can be re-processed into new magnets [8, 14]. Reviews report recovery of magnetic properties of about 90% under low hydrogenation temperature and pressure with rare earth hydride additions before sintering. Recasting loses an estimated 20 to 30% of the magnet and consumes a lot of power, and hydrometallurgical routes generate large volumes of liquid waste [10]. Oxygen control, powder particle size and starting composition are the dominant process variables [10]. As of the review cited, there was no working commercial process for rare earth recycling at scale [10], although HPMS facilities are now being built [15].

## 4. Colour's approach (hypothesis)

**Hypothesis.** A sintered NdFeB magnet made from hydrogen-processed recycled powder, blended with fresh alloy and finished with a GBD treatment, can reach a defined high-temperature coercivity target with materially less Dy/Tb per kilogram than a conventional equivalent, and can do so repeatably.

**Target specification.** These are *Proposed* targets, to be confirmed in customer calls and by our technical advisor:
- Operating temperature: 150 to 180 degrees C. This is where standard grades weaken, and it matches typical robotics and industrial motor conditions.
- Minimum coercivity at that temperature: match a commercial UH-class grade at 150 degrees C. The exact kA/m value comes from the target customer's spec sheet, and grade definitions should be checked with our advisor.
- Maximum Dy/Tb content per kg: at least 30% less Dy plus Tb by mass than a conventional magnet of the same coercivity class. The baseline will be measured from a commercial reference magnet.
- Remanence and energy product floor: within 3% of a conventional magnet of the same grade class.
- Batch-to-batch variation limit: coercivity within plus or minus 5% across batches. Final limits follow the customer's qualification requirements.

**Why the combination could matter.** Recycling reduces dependence on fresh heavy rare earths already embedded in scrap. GBD reduces how much new heavy rare earth is needed. Together they address supply risk from two sides. We have not found a published demonstration of the full combination at commercial quality, which is both the opportunity and the reason to be cautious. Absence of evidence in our search is not proof it has not been done.

**Where computation helps.** We plan to use public materials databases and screening to prioritize diffusion-source compositions and process windows, so that expensive lab runs are spent on the most promising candidates.

## 5. Intellectual property and freedom to operate

The hydrogen processing route for magnet scrap is patented: the University of Birmingham holds the patent and HyProMag is its exclusive licensee, according to UK regulatory filings for a commercial facility [15]. GBD is covered by a large body of patents from established magnet makers [13].

Colour's response:
1. Commission a freedom-to-operate review from a patent attorney before building process equipment.
2. Evaluate three paths: license, design around, or focus on parts of the chain not covered, such as feedstock sourcing, powder qualification, or novel diffusion sources.
3. File provisional patents only on what is genuinely new, as identified with our technical advisor.

Until that review is complete, this paper makes no claim that Colour can commercialize any specific route.

## 6. Validation plan

| Stage | Window | Deliverable | Pass / fail test |
|---|---|---|---|
| Customer spec | Months 0-3 | 30 logged customer calls, spec sheet from 2-3 buyers | At least 2 buyers confirm a target spec and will evaluate samples |
| Advisor review | Months 0-3 | Named magnetics advisor signs off on target spec | Spec judged technically credible |
| Feedstock | Months 1-6 | 3 scrap sources identified, composition characterized | Composition varies little enough that blended powder can hit the target spec, with the limit set by our advisor |
| Sample runs | Months 3-9 | 5-10 contract-lab batches with independent test report | Meets the target spec within the plus or minus 5% batch tolerance above |
| IP | Months 3-9 | Freedom-to-operate review, provisional filing | Clear path identified |
| Customer pilots | Months 9-18 | Paid evaluations with 2-3 customers | At least 1 customer qualifies samples |

**Kill criteria.** We stop or change material if no buyer will provide a spec, if samples cannot meet the target after the contract-lab stage, if scrap feedstock is too inconsistent to repeat results, or if freedom to operate cannot be established at acceptable cost.

## 7. Customers and applications

First targets are makers of robotics, drone, actuator and industrial motors, where qualification cycles are shorter than in automotive. Defense suppliers are a second early segment given the sourcing rules. Automotive is a later target because qualification takes years.

Customer evidence: none yet. Customer discovery is the first workstream, and this line will be updated with calls completed, named companies and any written interest. We will not describe demand beyond what customers tell us.

## 8. Commercial path

Revenue in expected order: paid sample evaluations and custom R&D; small supply contracts for magnets or recycled-feed alloy powder; licensing of qualified process know-how; pilot and then industrial-scale production. Long-term options include integrated recovery and refining, and a broader materials platform applying the same screening and process engine to other supply-constrained materials, including materials for space applications.

Market sizing: an industry consultant report cited in a 2026 Hong Kong Exchange filing puts global NdFeB magnet sales at about 251,600 tonnes in 2025, growing to about 400,300 tonnes by 2030 [16]. Dollar estimates from commercial research firms vary too widely to rely on (published 2024 to 2025 figures for the NdFeB market range from roughly US$3 billion to US$19.5 billion depending on definition), so we do not quote one. The addressable segment, high-temperature and heavy-rare-earth-lean magnets bought outside China, is not published in anything we found. We will size it bottom-up from customer calls: number of target motor makers, magnet mass per motor, and price per kg.

## 9. Risks

- **Technical:** recycled powder quality and oxygen control may limit repeatability [10].
- **IP:** key processes are patented; routes may be blocked or require licenses [15].
- **Market:** heavy-rare-earth-free magnet development could reduce demand for Dy/Tb-lean designs, and unit consumption of Dy/Tb per magnet has been falling [7].
- **Policy:** export controls may be extended, relaxed or reshaped, changing the urgency of the supply argument.
- **Competition:** incumbents and new Western suppliers are building capacity and may outpace a small company.
- **Execution:** a small team depends on contract labs and external advisors until a lab is justified.

## 10. What Colour will publish

To build trust, we will release as we go: a literature review (see [literature-review.md](literature-review.md)), the screening methods and results, customer-call findings in aggregate, and independent test reports when we have them, including negative results.

## 11. Conclusion

The supply pressure on high-temperature magnets is real and sourced. The technologies are individually established, but their combination into a repeatable, patent-clear product is unproven. Colour's plan is to find out quickly and cheaply, with independent data and named customer specs, before committing capital to equipment.

## References

1. IEA, "Rare earth elements" report, executive summary. https://www.iea.org/reports/rare-earth-elements/executive-summary
2. Future Markets Inc., "The Global Rare Earth Magnets Market 2027-2037." https://www.futuremarketsinc.com/rare-earth-magnets-market-2027-2037/ (reports China controlling over 90% of magnet production).
3. Live in the Future, "Rare earth supply cliff" (April 2026). https://liveinthefuture.org/stories/rare-earth-supply-cliff-april-2026.html (secondary source citing IEA data for a roughly 75% share of NdFeB magnet production; verify against the IEA original).
4. Futura-Sciences, article summarizing IEA analysis of China's 2025 rare earth export controls, including the November 2025 one-year suspension. https://www.futura-sciences.com/en/?p=900888
5. Fastmarkets, "China's looming November export controls test rare earth refining, recycling ambitions." https://www.fastmarkets.com/insights/chinas-looming-november-export-controls-test-rare-earth-refining-recycling-ambitions/
6. Radial Magnet, "Rare-Earth Magnet Supply Bottlenecks: What Buyers Should Expect Through the Rest of 2026." https://radialmagnet.com/?p=19881
7. Fastmarkets, "US demand drives sharp increases in CIP global terbium, dysprosium prices." https://www.fastmarkets.com/insights/us-demand-drives-sharp-increases-in-cip-global-terbium-dysprosium-prices/
8. Burkhardt C., "Hydrogen Assisted (Direct) Recycling of Nd-Fe-B Permanent Magnets: A Critical Review, Part 1." Sustainable Industrial Processing Summit 2024, Vol. 12, pp. 159-160.
9. "China Rare Earth Magnet 2026" report summary describing technology export controls on strip casting, sintering and grain boundary diffusion. https://faxiangongchang.com/en/reports/china-rare-earth-magnet-2026 (secondary source; verify against the original Chinese government notices).
10. Habibzadeh A., Kucuker M.A., Gokelma M. "Review on the Parameters of Recycling NdFeB Magnets via a Hydrogenation Process." ACS Omega 2023, 8, 17431-17445. https://doi.org/10.1021/acsomega.3c00299
11. Tian G. et al. "Developments and Applications of Preparing High Coercive Nd-Fe-B Magnets via Heavy Rare Earth Grain Boundary Diffusion Process." Materials Reports, 2025. https://www.mater-rep.com/EN/Y2025/V39/I6/24040174
12. He J. et al. "Grain Boundary Diffusion Sources and Their Coating Methods for Nd-Fe-B Permanent Magnets." Metals 2021, 11, 1434.
13. Patent literature on grain boundary diffusion, for example US 8,420,160, US 8,562,756 and US 10,854,380.
14. Burkhardt C. et al. "An overview of Hydrogen assisted (Direct) recycling of Rare earth permanent magnets." SUSMAGPRO consortium, 2023.
15. HyProMag Ltd, Non-Technical Summary, UK Environment Agency permit application, April 2024. https://consult.environment-agency.gov.uk/psc/b25-8dw-hypromag-ltd-epr-zp3125sn-a001/
16. Industry consultant report cited in a Hong Kong Exchange filing (2026). https://www1.hkexnews.hk/app/sehk/2026/108644/a134083/sehk26061502001.pdf

*Verify each reference against its original source before relying on it. Not legal, patent or investment advice.*
