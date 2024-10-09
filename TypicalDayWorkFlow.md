# Korata Transport Services Process Flow

```mermaid
flowchart TD
    A[Driver takes the car from the parked area] --> B[Driver picks up all the kids]
    B --> C[Driver drops off the kids at school]
    C --> D[Driver starts accepting Uber trips]
    D --> E{Passenger enters the vehicle}
    E --> F[Driver introduces himself and provides employment details]
    E --> G[Rider leaves item]
    G --> H[Item taken to head office]
    D --> I[Drivers go to respective schools]
    I --> J[Drivers drop kids at home]
    J --> K{Learner has extracurricular activities?}
    K --> L[Arrange pick-up time with parents]
    L --> M[Drop kids after activities]
    K --> M
    M --> N[Driver resumes Uber trips]
    N --> O[Driver picks up restaurant workers]
    O --> P[Drivers drop workers at home]
    P --> Q[Drivers may continue accepting trips until 10 PM]
    Q --> R[Driver returns the car to parking area]
    R --> S[Lead driver takes workers to their homes]
    S --> T[Lead driver returns the car and requests transport home]
    T --> U[Lead driver submits report on drivers and vehicle condition]
