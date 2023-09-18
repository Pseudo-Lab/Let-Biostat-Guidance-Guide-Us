# DELTA2 guidance on choosing the target difference and undertaking and reporting the sample size calculation for a randomised controlled trial part2

목차

## **Specifying the target difference for a randomised controlled trial**

box1, table1 참고

Two different approaches can be taken to specify the target difference for a randomised controlled trial.

- Important to one or more stakeholder groups
- Realistic (plausible), based on either existing evidence, or expert opinion.

It has been argued that a target difference should always be both important and realistic, which would seem particularly apt when designing a definitive (phase 3) superiority randomised controlled trial.

## Table 1. DELTA recommended reporting items for the sample size calculation of a randomised controlled trial with a superiority question

### Core Items

1. **Primary outcome**
2. **Statistical significance and power**
3. Express the target difference according to outcome type
    - Binary
        
        state the target difference as an absolute or relative effect (or both), along with the intervention and control group proportions
        
        ※ if both an absolute and a relative difference are provided, clarify if either takes primacy in terms of the sample size calculation
        
    - Continuous
        
        state the target mean difference as the natural scale, common standard deviation, and standardised effect size
        
        $$
        effect\ size = {\mu_{difference} \over {\sigma}}
        $$
        
    - Time-to-event
        
        state the target difference as an absolute or relative difference (or both); provide 4 things
        
        - the control group event proportion
        - planned length of follow-up
        - intervention and control group survival distributions
        - accrual time
        
        ※ if both an absolute and a relative difference are provided, clarify if either takes primacy in terms of the sample size calculation
        
4. Allocation ratio
- Sample size based on the assumptions as per above
    - if standard binary, continuous, or survival outcome formulas are not used → the formula/sample size calculation approach
    - a time- to-event outcome → the number of events required should be stated
    - any adjustments that alter the required sample size (allowance for loss to follow-up, multiple testing) → be specified, referenced, and justified along with the final sample size
    - alternative designs → additional input should be stated and justified
    - Provide details of any assessment of the sensitivity of the sample size

### Additional items for grant application and trial protocol

- Underlying basis used for specifying the target difference
- Explain the choice of target difference

### Additional item for trail results paper

- reference the trial protocol

## **Reporting the sample size calculation**

Under the conventional approach with a standard trial designs & unadjusted statistical analysis, the core items:

- primary outcome
- the target difference (appropriately specified according to the outcome type)
- the associated nuisance parameter (uniquely specifies the difference on the original outcome scale)
- the statistical significance and power
- ++) design이 더 복잡하다면 추가적인 input을 포함할 수도 있음 (ex. cluster randomized design을 위한 클러스터 간 상관관계)

## Box2: Methods that inform what is an important difference

### Methods that inform what is an important difference

- Anchor
    - The outcome of interest can be anchored by using either a patient’s or health professional’s judgment to define what an important difference is.
- Distribution
    - A common approach is to use a value that is larger than the inherent imprecision in the measurement and therefore likely to represent a minimal level needed for a noticeable difference.
    - **[A Distribution-based Method for Assessing The Differences between Clinical Trial Target Populations and Patient Populations in Electronic Health Records](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4081748/)**
- Health economic
    - compare cost with health outcomes
    - define a threshold value for the cost of a unit of health effect that a decision maker is willing to pay
    - to estimate the overall incremental net benefit of one treatment versus the comparator
    - a (bayesian) decision-theoretic value of information analysis
- Standardised effect size
    - [Cohen’s D](https://statisticsbyjim.com/basics/cohens-d/)
        - $d = {{\mu_{groupA} - \mu_{groupB}\over{\sigma}}}$
        
        | Cohen’s d | Indicates Mean Difference | Effect Size |
        | --- | --- | --- |
        | 0.2 |  | Small |
        | 0.5 | Half $\sigma$ | Medium |
        | 0.8 |  | Large |
        | 1 | Equal to $\sigma$ |  |
        | 2 | Twice $\sigma$ |  |
        - Cohen’s cutoff points approximate odds ratios of 1.44, 2.48, and 4.27, respectively.

### Methods that inform what is a realistic difference

- [Pilot study](https://blog.naver.com/happymedicalwriter/220480068851)
    - A pilot (or preliminary) study may be carried out if there is little evidence, or even experience, to guide expectations and determine an appropriate target difference for the trial.

### Methods that inform what is an important or a realistic difference

- Opinion seeking
    - based on opinions elicited from health professionals, patients, or others.
- Review of evidence base
    - Ideally, this evidence would be from a systematic review or meta-analysis of randomised controlled trials.
    - In the absence of randomised evidence, evidence from observational studies could be used in a similar manner

## Discussion

“The key message for researchers is the need to be more explicit about the rationale and justification of the target difference when undertaking and reporting a sample size calculation. Increasing focus is being placed on the target difference in the clinical interpretation of the trial result, whether statistically significant or not. Therefore, the specification and reporting of the target difference, and other aspects of the sample size calculation, needs to be improved.”