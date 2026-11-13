# Analysis Plan

**Status:** Proposed plan only. No data have been collected. Date and freeze this plan before recruitment; document any deviations.

## Design
2 × 2 between-participants pilot: warm vs neutral tone; contextual privacy notice vs no additional notice.

## Outcomes
**Primary:** share/skip selection for each fictional profile card; pre-defined sensitivity-weighted selection score.  
**Secondary exploratory ratings:** perceived warmth, AI awareness, privacy awareness, notice recall, and perceived freedom to skip (5-point items).

## Data minimization
Collect only a random study code, adult eligibility confirmation, assigned condition, fictional item choices, brief ratings, and completion/missingness indicators. Do not collect names, email, exact age/date of birth, IP addresses, location, device identifiers, free-text narratives, audio, or chat transcripts. Review recruitment-platform metadata settings.

## Exclusions
Predefine exclusions: ineligible participant (under 18); duplicate submission only if detectable without identifying data; missing primary outcome; or technical failure preventing exposure to the assigned stimulus. Never exclude responses because they contradict a hypothesis. Report counts and reasons.

## Descriptive reporting
Report recruited, eligible, completed, and analyzed counts; condition sizes; missingness; item-selection proportions by condition; distributions of secondary ratings; and uncertainty intervals where suitable.

## Exploratory comparisons
For binary item choices, logistic regression may include tone, privacy cue, and their interaction. With a small sample, estimates may be unstable: prioritize descriptive tables, effect estimates, and uncertainty intervals. Choose a simple model for any sensitivity score after inspecting its scale and distribution. Avoid overfitting. A p-value is not proof of an effect or no effect; a non-significant result does not establish equivalence.

## Interpretation limits
Choices concern fictional details, not actual disclosure. The convenience sample may be non-representative. Single-item ratings are not validated scales. The study cannot establish long-term effects, real-world leakage, or the safety of commercial AI systems.

## Reproducibility
Archive final stimuli, screenshots, dated protocol/amendments, variable definitions, analysis code, and software versions. Release row-level data only if consent, ethics approval, and re-identification assessment permit it. Any synthetic example dataset must be labelled **synthetic demonstration data—not participant data**.