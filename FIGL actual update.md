# FIGL Actual update
Flow Charts and Diagrams
graph LR
    A[(FIGL 450 excel update)]
    ==> |Import to GS| B[('Google Sheets FIGL450 202X')]
    B ==> C(Rename sheet 'FIGL450' => 'BW Data')
    C ==> D(Refresh RD and NRD Queries)
    D ==> E>RD & NRD Synthesis are ready]
    E -.-> |If any bookings| A
    style A fill:#eff,stroke:#333,stroke-width:4px
    style B fill:#bbfe6e6fa,stroke:#333,stroke-width:4px,stroke-dasharray: 5 5
