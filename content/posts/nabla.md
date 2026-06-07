+++
title = 'Nabla'
draft = true
+++
# Nabla

```text
Nabla/
│
├── CMakeLists.txt
├── README.md
├── .gitignore
│
├── include/
│   └── nabla/
│       ├── la/
│       │   └── matrix.hpp
│       │
│       ├── dataset/
│       │   └── csv_loader.hpp
│       │   └── dataset.hpp
│       │
│       ├── metrics/
│       │   ├── regression/
│       │   │   ├── mse.hpp
│       │   │   ├── rmse.hpp
│       │   │   ├── mae.hpp
│       │   │   └── r2_score.hpp
│       │   │
│       │   └── classification/
│       │       ├── accuracy.hpp
│       │       ├── precision.hpp
│       │       ├── recall.hpp
│       │       └── f1_score.hpp
│       │
│       └── models/
│           ├── estimator.hpp
│           ├── linear_regression.hpp
│           └── logistic_regression.hpp
│
├── src/
│   ├── la/
│   │   └── matrix.cpp
│   │
│   ├── dataset/
│   │   └── dataset.cpp
│   │
│   ├── metrics/
│   │   ├── regression/
│   │   │   ├── mse.cpp
│   │   │   ├── rmse.cpp
│   │   │   ├── mae.cpp
│   │   │   └── r2_score.cpp
│   │   │
│   │   └── classification/
│   │       ├── accuracy.cpp
│   │       ├── precision.cpp
│   │       ├── recall.cpp
│   │       └── f1_score.cpp
│   │
│   └── models/
│       ├── linear_regression.cpp
│       └── logistic_regression.cpp
│
├── tests/
|   └── test_csv_loader.cpp
│   └── test_matrix.cpp
│
├── examples/
│   └── linear_regression.cpp
│
└── data/
```

