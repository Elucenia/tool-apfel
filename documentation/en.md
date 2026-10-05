<!-- ELUCENIA technical documentation · apfel · en · no clinical/professional/rights approval -->

# Apfel score (postoperative nausea and vomiting)

[conditions, sources and permissions](https://elucenia.org/en/tools/apfel)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Female sex

`fem`

### Nonsmoker

`naofuma`

### History of postoperative nausea and vomiting or motion sickness

`historia`

### Planned postoperative opioid use

`opioide`

## Method edition

Simplified Apfel 1999: 4 factors, 0–4; not the Koivuranta model

## Documented formula

1 point per factor: female sex, nonsmoker, PONV or motion-sickness history, postoperative opioid.

## Limits and population

The simplified Apfel from 1999 was studied in adults under inhalational anesthesia, without antiemetic prophylaxis, for nausea or vomiting in the first 24 hours. Probabilities from the original cohort are not automatically recalibrated for children, other anesthetic techniques or people already receiving prophylaxis. Antiemetic strategy depends on its own assessment and guideline.

## References

- [Apfel CC et al. A simplified risk score for predicting postoperative nausea and vomiting: conclusions from cross-validations between two centers. Anesthesiology, 1999.](https://doi.org/10.1097/00000542-199909000-00022)

- [Gan TJ et al. Fourth consensus guidelines for the management of postoperative nausea and vomiting. Anesth Analg, 2020.](https://doi.org/10.1213/ANE.0000000000004833)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
