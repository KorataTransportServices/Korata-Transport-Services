# Korata Transport Services Process Flow

# Combined Business Process Flow

```mermaid
flowchart TD
    %% General Driver Workflow %%
    A[Driver takes the car from the parked area] --> B[Driver picks up all the kids]
    B --> C[Driver drops off the kids at school]
    C --> D[Driver starts accepting Uber trips]
    D --> E{Passenger enters the vehicle}
    E --> F[Driver introduces himself and provides employment details]
    F --> G[Trip ends]
    G --> H{Rider left item?}
    H -- Yes --> I[Item taken to head office]
    H -- No --> J[Driver continues trips]
    I --> J[Driver continues trips]
    J --> K[Close to school knock-off, drivers go to their respective schools]
    K --> L{Learner has extracurricular activities?}
    L -- NO --> M[ Drivers Picks up and drop the kids at home]
    L -- Yes --> N[Arrange pick-up time with parents]
    L --> M[Drop kids after activities]
    N --> O[Driver resumes Uber trips]
    M --> O[Driver resumes Uber trips]
    O --> P{Made an arrangement to pickup a learner with extracular activities?}
    P -- Yes --> Q[Go pickup the learner in time and drop the learner at home]
    P -- No --> R[Continue accepting trips]
    Q -->  R[Continue accepting trips]
    R --> S{Driver has an arrangement with restaurant workers?}
    S -- No --> T[Continue accepting trips]
    S -- Yes --> U[Go to pickup workers and drop them at their homes]
    U --> T[Continue accepting trips]
    T --> V{Drivers may continue accepting trips until 10 PM. Done for the day ?}
    V -- Yes --> W[Driver returns the car to parking area]
    V -- No --> X[Contact lead driver to make arrangements]
    X --> AB [Continues accepting trips and stops at 11pm]
    AB --> W[Driver returns the car to parking area]
    W --> Y[Lead driver takes worker(s) to their homes]
    Y --> Z[Lead driver returns the car and requests transport to go home]
    Z --> AA[Lead driver submits report on drivers and vehicle condition every 2 weeks]

    %% Cash Payment Process %%
    cash1[Driver accepts a trip with cash payment] --> cash2[Driver receives cash]
    cash2 --> cash3{End of trip within 2 hours?}
    cash3 --> cash4[Driver deposits the cash]
    cash3 --> cash5[If more than 2 hours, notify the lead driver and company]

    %% Petrol Refill Process %%
    petrol1[Lead driver holds petrol bank account with monthly allocation]
    petrol2[Driver needs a refill] --> petrol3[Driver contacts lead driver]
    petrol3 --> petrol4[Driver indicates cost of petrol and sends receipt to lead driver]
    petrol4 --> petrol5[Lead driver sends money using e-wallet and cc's company email]
    petrol5 --> petrol6[Driver pays for the petrol refill]
    petrol6 --> petrol7[Lead driver sends proof of transaction to company email]

