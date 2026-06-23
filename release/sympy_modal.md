* logic
  * Implemented a complete second-order modal predicate logic reasoning engine (`sympy_modal`) fully integrated with the main namespace.
  * Added `Universe`, `BoolType`, `FunctionType`, `PredicateVariable`, and `ModalPredicate` type systems.
  * Added explicit modal operators `Box`, `Diamond`, `ProvabilityBox`, `AlethicBox`, `EpistemicBox`, `DeonticBox`, and `TemporalBox`.
  * Added second-order logic quantifiers `ForAllPredicates` and `ExistsPredicates`.
  * Added `KripkeFrame` runtime semantics to automatically validate structures across possible worlds.
  * Added `TrustedKernel` and `ProofTerm` certificate verification to rigorously enforce intuitionistic natural deduction.
  * Added `ProofContext` that orchestrates hypotheses, lemmas, and manages classical logic warnings.
  * Added `Strategy.Backward`, `Strategy.ForwardChain`, and `Strategy.ModalInduction` automated theorem proving search routines for the proof context.
  * Added `FormalisationInterface` to unambiguously parse code strings into typed modal instances by heuristic logic inference.
