# AutomataStudio Android
app/
├── MainActivity.kt
├── navigation/
│   └── AppNavigation.kt
├── core/
│   ├── model/
│   │   ├── Automaton.kt
│   │   ├── State.kt
│   │   └── Transition.kt
│   └── ui/
│       ├── theme/
│       └── components/
├── data/
│   ├── local/
│   │   ├── AutomataDatabase.kt
│   │   ├── ProjectDao.kt
│   │   └── ProjectEntity.kt
│   └── repository/
│       └── ProjectRepository.kt
├── domain/
│   ├── validation/
│   │   └── AutomatonValidator.kt
│   ├── simulation/
│   │   └── AutomatonSimulator.kt
│   └── algorithms/
│       ├── EpsilonClosure.kt
│       ├── EpsilonRemoval.kt
│       ├── NfaToDfa.kt
│       ├── Reachability.kt
│       └── DfaMinimizer.kt
└── feature/
├── home/
├── project/
├── editor/
├── simulation/
├── algorithms/
├── export/
└── settings/

