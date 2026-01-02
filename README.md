# Yes, That's Mine: Asymptotically Foolproof LLM Ownership Verification Against Hidden Adversarial Decoding Parameter Perturbations

## Working Abstract (Draft)
Creating and training an LLM can take vast amounts of resources, money, and effort. Because of this, many LLM creators seek to protect their credit and IP from being stolen. 'LLM ownership verification', the study of verifying whether an unnamed LLM can be identified with a known LLM, is therefore one of the primary commercial motivators for the research of LLM provenance. White-box methods and backdoor-style black-box methods for LLM ownership verification face challenges with constrained practical assumptions and invasiveness, driving the search for effective and non-invasive black-box methods. There is a practice-theory gap in the current research for non-invasive, black-box methods, and we have proposed a community-wide formal program for classifying threat models which admit 'theoretically foolproof' (in the sense of decidable, statistical consistent, etc.) methods of LLM ownership verification. We argued that hidden decoding parameter perturbations are the necessary first model-identity-obfuscation class to investigate for this formal program, then presented statistically consistent tests for identifying a black-box LLM's ownership identity under such identity obfuscations. The methods presented in this paper satisfy key desirable properties such as: 1) being non-invasive and fully black box, 2) being statistically consistent, 3) being viable against an adversary with perfect information, 4) emitting useful intermediate results that may be useful in other research, and 5) being viable for further optimization. Along the way, we implicitly proved a fundamental negative result: standard, token-distribution-modifying decoding parameters are not obfuscating enough to prevent the existence of a non-invasive, theoretically foolproof method for verifying a black-box LLM’s ownership identity. In doing so, we established the first evidence of the feasibility of the proposed formal program, which aims to prove similar results under other threat scenarios.

## Current progress:
This is a rough draft of my paper, but the core theoretical results of this paper are stable and complete.

## Citation


## TO-DO:
- Fix typos.
- Improve expositional clarity and conciseness.
- Reformat, restructure, reorganize, and refactor.
- Move this document from Mathcha to Latex.
