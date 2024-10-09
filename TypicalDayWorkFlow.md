# Korata Transport Services Process Flow

flowchart TD
    %% General Driver Workflow %%
    A[Driver takes the car from the parked area] --> B[Driver picks up all the kids]
    B --> C[Driver drops off the kids at school]
    C --> D[Driver starts accepting Uber trips]
    D --> E{Passenger enters the vehicle}
    E --> F[Driver introduces himself and provides employment details]
    E --> G[Rider leaves item]
    G --> H[Item taken to head office]
    D --> I[Close to school knock-off, drivers go to their respective schools]
    I --> J[Drivers drop the kids at home]
    J --> K{Learner has extracurricular activities?}
    K --> L[Arrange pick-up time with parents]
    L --> M[Drop kids after activities]
    K --> M
    M --> N[Driver resumes Uber trips]
    N --> O[Driver picks up restaurant workers]
    O --> P[Drivers drop workers at their homes]
    P --> Q[Drivers may continue accepting trips until 10 PM]
    Q --> R[Driver returns the car to parking area]
    R --> S[Lead driver takes workers to their homes]
    S --> T[Lead driver returns the car and requests transport home]
    T --> U[Lead driver submits report on drivers and vehicle condition every 2 weeks]

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
