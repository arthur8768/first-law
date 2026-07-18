# Quality Gates

Run this checklist before finalizing. Fix failed gates; do not merely disclose
that they failed.

## Scope

- [ ] The object, context, level of analysis, intended use, and exclusions are
      explicit.
- [ ] The answer does not drift between individual, organizational, market, or
      societal levels.

## Epistemic Integrity

- [ ] Important statements are distinguishable as Evidence, Given, Assumption,
      Inference, or Synthesis.
- [ ] A synthesized formula, acronym, or framework is labeled as a heuristic.
- [ ] Empirical, contested, current, or high-stakes claims use appropriate
      research and citations.
- [ ] The conclusion is no stronger than the supporting evidence.

## First-Principles Derivation

- [ ] The definition is non-circular.
- [ ] The irreducible problem is stated independently of the current solution.
- [ ] The counterfactual explains what fails when the object is absent.
- [ ] Constraints are justified and classified by stability.
- [ ] Every causal arrow has a mechanism or is marked as an assumption.

## Minimum System

- [ ] Every core component has a unique function.
- [ ] Every core component passes a deletion test.
- [ ] Redundant, enabling, optional, and outcome variables are not mislabeled as
      necessary components.
- [ ] The complete set receives a sufficiency test.

## Boundaries And Tensions

- [ ] At least two neighboring concepts are distinguished on common dimensions.
- [ ] The answer includes a positive example and a negative example.
- [ ] The strongest counterexample or competing explanation is considered.
- [ ] Failure conditions and second-order trade-offs are explicit.

## Testability

- [ ] The model has at least one direct observable indicator.
- [ ] Proxies are not confused with the construct.
- [ ] The model makes at least one prediction.
- [ ] At least one observable result would materially weaken or falsify it.
- [ ] Process quality is not inferred solely from outcome quality.

## Usefulness

- [ ] Recommendations follow from the derived mechanism.
- [ ] The answer identifies what the user should stop assuming or do
      differently.
- [ ] Uncertainty and transfer limits are calibrated.
- [ ] The explanation can be summarized in one strict sentence and one
      plain-language sentence without contradiction.

## Automatic Rejection Conditions

Do not ship an answer that:

- only defines the term with synonyms;
- begins from a borrowed framework and never justifies it;
- calls a current convention a universal law;
- uses an analogy as causal evidence;
- presents a long component list without necessity and sufficiency tests;
- hides an unsupported claim inside a formula;
- gives generic advice unrelated to the derived mechanism;
- cannot state what evidence would change its conclusion.
