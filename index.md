flowchart TB
    A("Foraging") --> B("Cooking")
    C("Fire lighting") --> B
    D("Crafting") --> G("Shelter building") & B
    F("Knots") --> G
    G --> E("Camping")
    H("Navigation") --> I("Tracking")
    I --> J("Trapping") & K("Hunting")
    J --> L("Butchery")
    K --> L
    L --> B

    style A stroke:#000000,fill:#00C853
    style C stroke:#000000,fill:#00C853
    style D stroke:#000000,fill:#00C853
    style H stroke:#000000,fill:#00C853
    style F stroke:#000000,fill:#00C853
    style L stroke:#000000,fill:#D50000
    style B stroke:#000000,fill:#FFD600
    style G stroke:#000000,fill:#FFD600
    style E stroke:#000000,fill:#FF6D00
    style I stroke:#000000,fill:#FFD600
    style J stroke:#000000,fill:#FF6D00
    style K stroke:#000000,fill:#FF6D00
