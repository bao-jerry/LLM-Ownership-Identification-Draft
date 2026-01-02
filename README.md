# Yes, That's Mine: Asymptotically Foolproof LLM Ownership Identification Against Hidden Adversarial Decoding Parameter Perturbations

Author: Jerry Bao (contact: bao.jerry.can@gmail.com)

Acknowledgements: This research is supported by the Vector Scholarship in Artificial Intelligence, provided through the Vector Institute.

## Working Abstract (Draft)
Creating and training an LLM can take vast amounts of resources, money, and effort. Because of this, many LLM creators seek to protect their credit and IP from being stolen. 'LLM ownership identification', the study of determining whether an unnamed LLM is a stolen version of a known LLM, is therefore one of the primary commercial motivators for the research of LLM provenance. White-box methods and backdoor-style black-box methods for LLM ownership identification face challenges with constrained practical assumptions and invasiveness, driving the search for effective and non-invasive black-box methods. There is a practice-theory gap in the current research for non-invasive, black-box methods, and we have proposed a community-wide formal program for classifying threat models which admit 'theoretically foolproof' (in the sense of decidable, statistical consistent, etc.) methods of LLM ownership identification. We argued that hidden decoding parameter perturbations are the necessary first model-identity-obfuscation class to investigate for this formal program, then presented statistically consistent tests for identifying a black-box LLM's ownership identity under such identity obfuscations. The methods presented in this paper satisfy key desirable properties such as: 1) being non-invasive and fully black box, 2) being statistically consistent, 3) being viable against an adversary with perfect information, 4) emitting useful intermediate results that may be useful in other research, and 5) being viable for further optimization. Along the way, we implicitly proved a fundamental negative result: standard, token-distribution-modifying decoding parameters are not obfuscating enough to prevent the existence of a non-invasive, theoretically foolproof method for determining a black-box LLM’s ownership identity. In doing so, we established the first evidence of the feasibility of the proposed formal program, which aims to prove similar results under other threat scenarios.

## Current status
This is a rough draft of a paper undergoing active modifications prior to submission and peer review. The core theoretical results of this paper are stable and complete, but the presentation is expected to change significantly.

## Citation
If you would like to cite this work, please use:
- Title: *Yes, That's Mine: Asymptotically Foolproof LLM Ownership Identification Against Hidden Adversarial Decoding Parameter Perturbations*
- Author: Jerry Bao
- DOI: https://doi.org/10.5281/zenodo.18127692
- Year: 2026

## TO-DO
- Fix typos.
- Improve expositional clarity and conciseness.
- Reformat, restructure, reorganize, and refactor.
- Move this document from Mathcha to Latex.
