# Measurement and characterisation

> Part of [Colour Research](../README.md). Educational material. Numbers are approximate textbook or literature values unless sourced. See [research integrity](06-research-integrity.md).

How to measure thermal and structural properties properly, and how to design experiments so the results mean something.

## Measuring things properly

| Question | Technique | What it tells you |
|---|---|---|
| How well does it conduct heat? | Laser flash analysis (LFA) | Thermal diffusivity, converted to conductivity |
| What is its specific heat? | Differential scanning calorimetry (DSC) | Needed for the conversion |
| How dense is it? | Archimedes method | Density and porosity |
| How much does it expand? | Dilatometry | CTE over a temperature range |
| What does it look like inside? | SEM with EDS | Particles, pores, interface layers, composition |
| What crystal phases are present? | XRD | Carbides, graphite, copper |
| Is there graphite on the diamond? | Raman spectroscopy | Graphitic and diamond carbon signals |
| How strong is it? | Flexural or tensile test | Breaking strength |
| How flat and smooth is it? | Profilometry | Surface specifications |

**Measurement discipline:** accuracy (closeness to truth), precision (repeatability), uncertainty (width of doubt), calibration (checking against a reference), and a **reference sample** you measure often. If you cannot state your uncertainty, you do not yet have a result.

## Designing experiments

**DoE (design of experiments)** changes several variables in a planned way and separates their effects, which beats changing one thing at a time.

- **Factor:** a variable you set. **Level:** a value of it. **Response:** what you measure.
- **Screening design:** many factors, few runs, find the important ones.
- **Response-surface design:** few factors, find the best settings.
- **Replicate:** repeat a run to estimate noise. **Control:** an unchanged sample to detect drift.
- **Statistical significance:** whether an effect is bigger than noise.
- **Bayesian optimization:** a model suggests the most informative next run, which is how a data-driven lab gets faster.
