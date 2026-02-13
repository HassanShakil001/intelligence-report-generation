# Generating Synthetic Intelligence Reports with LLMs

Code and data for the paper "Generating Synthetic Intelligence Reports with LLMs via Structured and Recursive Prompting"

## Paper Information

**Authors:** William Armstrong, Hassan Shakil, Zachary H. Pugh, Dylan Tokita, Jugal Kalita

**Status:** Under Review at Expert Systems with Applications

**Note:** Complete code and datasets will be released upon paper acceptance.

## Abstract
Generating operationally-reliable intelligence reports with large language models requires complete metadata schemas and accurate geographic coordinates, yet no prior work has systematically evaluated whether LLMs can meet these requirements. We present a framework integrating recursive prompting with structured symbolic grounding (knowledge graphs) and spatial grounding (geographic metadata) to address this challenge. Evaluating 382 synthetic intelligence reports from GPT-3.5 and GPT-4, we demonstrate that structured grounding is essential for operational reliability: schema compliance increased from 0\% (baseline) to 100\% with structured inputs ($p<0.001$), geographic accuracy reached 82.9\% (GPT-4) and 57.4\% (GPT-3.5) versus unmeasurable for baseline, and metadata completeness was fully achieved. Entity grounding remained modest (15--23\%), reflecting our framework's design encouraging topical exploration. Three expert evaluators rated all configurations as high-quality ($M>4.0/5.0$, 84--94\% inter-rater agreement), revealing a ceiling effect wherein human assessment alone cannot detect technical failures exposed by automated metrics. Our findings establish that structured grounding is necessary for generating technically reliable intelligence reports, and that comprehensive evaluation requires both automated metrics and human assessment to capture orthogonal quality dimensions.

## Repository Contents (Coming Soon)

Upon paper acceptance, this repository will include:

- 382 synthetic intelligence reports (main dataset)
- 90 supplementary reports (ODIN + VAST)
- Complete Zendia scenario with knowledge graph
- All prompt templates and generation scripts
- Automated evaluation code for all metrics
- Human evaluation rubric and materials
- Statistical analysis scripts

## Citation
```
[Will be added upon publication]
```

## License

MIT License - See LICENSE file for details

## Contact

For questions, please contact: hshakil@uccs.edu
