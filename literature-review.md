# Recycling NdFeB Magnets and Using Less Dysprosium/Terbium: A Plain-Language Technical Review

**Author:** Malik, founder, Colour
**Status:** Literature review. This summarizes published work. It contains no original experimental results yet.
**Last updated:** 31 October 2026

## Why this matters

Sintered neodymium-iron-boron (NdFeB) magnets power most high-performance electric motors. Two things keep them working when hot: heavy rare earths (dysprosium, Dy, and terbium, Tb), and good microstructure. Both are supply-constrained, and China dominates their processing. That makes two questions worth studying carefully:

1. Can we get the same heat resistance with much less Dy/Tb?
2. Can we make new magnets from old ones instead of from fresh ore?

This note walks through what the literature says about each, where the hard problems are, and what is still open.

## 1. How an NdFeB magnet works, in two paragraphs

The magnetic phase is Nd2Fe14B. Its grains are surrounded by a thin Nd-rich grain boundary phase that magnetically isolates them, which is a big part of why the magnet resists demagnetization [1].

Coercivity, the resistance to demagnetization, falls as temperature rises. Dy and Tb have a higher magnetic anisotropy than Nd, so putting them in the outer layer of each grain makes it harder for reverse magnetic domains to nucleate there. That is the basis of high-temperature grades [2, 3].

## 2. Using less Dy/Tb: grain boundary diffusion (GBD)

**The old way:** mix Dy or Tb into the alloy before melting. It works, but heavy rare earths end up throughout each grain, where they add little coercivity and reduce remanence (Br) and maximum energy product, (BH)max [4].

**GBD:** apply a Dy- or Tb-containing source to the surface of a finished sintered magnet, then heat it, typically at about 700 to 1000 degrees C. The Nd-rich grain boundary phase becomes liquid, and Dy/Tb travel along it much faster than they penetrate into the grains. The result is a Dy/Tb-rich shell at the outer region of each grain, which boosts coercivity with only a small hit to Br [2, 4].

Industrial variants differ mainly in how the diffusion source is applied: powder layers of Dy/Tb fluorides or oxides, vapor deposition, coatings, electrophoretic deposition, and electroplating, plus newer alloy sources designed to modify the boundary phase [2, 4].

**Known limits to be aware of:**
- Penetration depth is limited, so the benefit shrinks as magnets get thicker and the interior is modified less than the surface [3, 8].
- The process is applied after machining, so it adds a step and needs careful control of temperature, time and source chemistry [2].
- GBD is already used industrially, and many patents cover specific sources and methods [4]. Any new approach must be checked against that landscape.

## 3. Making magnets from old magnets: hydrogen processing

**The core idea.** When a sintered NdFeB magnet is exposed to hydrogen, it breaks apart into a brittle, demagnetized powder. The powder contains Nd2Fe14B-type hydride particles around 10 microns plus much finer material from the grain boundary phase [5]. That powder can be re-processed into new magnets, which is the shortest route from scrap to a magnet [1, 7].

This approach is called Hydrogen Processing of Magnet Scrap (HPMS). Two main variants appear in the literature: hydrogen decrepitation (HD), and hydrogenation-disproportionation-desorption-recombination (HDDR) [6].

**Why it is attractive compared to other routes** [6]:
- Recasting and melt spinning consume a lot of power, and a reported 20 to 30% of the magnet is lost, though oxygen content stays low.
- Hydrometallurgical routes are complex, with a large environmental footprint because of the liquid waste they generate.
- Hydrogen processing is shorter, and reported recovery of magnetic properties reaches about 90% when using low hydrogenation temperature and pressure and adding rare earth hydrides before sintering.

**What actually controls the result** [6]: starting composition, hydrogen pressure and temperature (which interact, and the optimum is sensitive to composition), gas flow, particle size distribution, grain size, and above all oxygen content. Oxygen pickup in fine powder is the central practical problem, which is why industrial descriptions of the process stress evacuating the vessel, back-filling with nitrogen, and working in tightly controlled atmospheres [9].

**Feedstock is a real constraint.** Most recycling activity so far has focused on hard disk drive magnets because they are accessible. The reviews expect most future scrap to come from energy and automotive applications, which are harder to collect and dismantle [6]. European projects such as SUSMAGPRO have worked on the full chain: dismantling, magnet extraction, HPMS recycling, magnet production and demonstrator testing [7].

**Policy is pulling this forward.** EU regulation plans for recycling capacity to cover at least 25% of annual permanent magnet consumption by 2030 [5].

## 4. The intellectual property reality

This section matters more than it looks. HPMS is a patented process: the University of Birmingham holds the patent and HyProMag is its exclusive licensee, according to UK regulatory documents for a commercial HPMS facility [9]. Anyone planning to build a hydrogen-based magnet recycling business needs to understand that landscape before investing. Options include licensing, working on a different route, or focusing on parts of the chain, such as feedstock or downstream processing, that the patents do not cover. This needs a proper freedom-to-operate review by a patent attorney.

## 5. Open questions I think are worth working on

- How much do variation in scrap composition and contamination (coatings, adhesives, oxidation) limit repeatability of recycled powder?
- Can GBD be combined with recycled-feed magnets, and does the recycled microstructure diffuse differently?
- Can computational screening identify better diffusion sources, with less Dy/Tb or cheaper elements, before anyone spends on lab work?
- Which application temperature and spec windows can recycled, low-Dy magnets realistically hit?

**What I would test first.** Feedstock consistency. Every downstream result, whether powder quality, diffusion response or final coercivity, depends on how repeatable the starting scrap is, and it is the cheapest question to answer: collect samples from a few recyclers and characterize their composition and contamination before paying for any magnet-making runs. The second priority is the diffusion source, since a better source is where a small team could plausibly contribute something new, and it is where computational screening can narrow candidates before lab time is spent. I am not claiming results on either yet. These are the experiments I think will teach the most per dollar.

## 6. What I am doing next

These are planned steps. None are complete yet, and this section will be updated as they are.

1. Commission a freedom-to-operate review of the hydrogen processing and grain boundary diffusion patent landscape.
2. Contact magnetics researchers and ex-industry engineers for a technical advisor and for critical review of this note.
3. Run 30 customer-discovery calls with motor, drone, robotics and actuator makers to set real specification targets.
4. Contact scrap magnet sources, such as motor recyclers, to characterize feedstock.
5. Plan contract-lab sample runs with independent testing once the target spec and IP path are clear.

## References

1. Habibzadeh A., Kucuker M.A., Gokelma M. "Review on the Parameters of Recycling NdFeB Magnets via a Hydrogenation Process." ACS Omega 2023, 8, 17431-17445. https://doi.org/10.1021/acsomega.3c00299
2. He J. et al. "Grain Boundary Diffusion Sources and Their Coating Methods for Nd-Fe-B Permanent Magnets." Metals 2021, 11, 1434.
3. Tian G. et al. "Developments and Applications of Preparing High Coercive Nd-Fe-B Magnets via Heavy Rare Earth Grain Boundary Diffusion Process." Materials Reports, 2025. https://www.mater-rep.com/EN/Y2025/V39/I6/24040174
4. Patent literature describing grain boundary diffusion, its coercivity benefit and small remanence loss, for example US 8,420,160, US 8,562,756 and US 10,854,380.
5. Burkhardt C. "Hydrogen Assisted (Direct) Recycling of Nd-Fe-B Permanent Magnets: A Critical Review, Part 1." Sustainable Industrial Processing Summit 2024, Vol. 12, pp. 159-160.
6. Habibzadeh A. et al. (reference 1), which also covers the recycling routes, process parameters, recovery rates and feedstock outlook cited above.
7. Burkhardt C. et al. "An overview of Hydrogen assisted (Direct) recycling of Rare earth permanent magnets." SUSMAGPRO consortium, 2023.
8. EV Reporter, "Neodymium sintered magnets and new manufacturing technologies | Grain boundary diffusion." Trade press overview. https://evreporter.com/neodymium-sintered-magnets-grain-boundary-diffusion/
9. HyProMag Ltd, Non-Technical Summary, UK Environment Agency permit application, April 2024. https://consult.environment-agency.gov.uk/psc/b25-8dw-hypromag-ltd-epr-zp3125sn-a001/

*Verify each reference against its original source before relying on it. I am not a lawyer or a patent attorney, and nothing here is legal advice.*
