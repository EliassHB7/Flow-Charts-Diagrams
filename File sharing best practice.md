# Flow-Charts-Diagrams
Flow Charts and Diagrams

graph BT
    A[(Update YTD of initial database: SAP, GPS, EPM, STR, PUMA, HANA...)]
    ===> |Upload to Google Sheets| B[(Google Sheet ''Source Database'' + Filtered Queries)]
    B ----> |Importrange of whole sheet or synthesis| D(My Working File)
    B ----> |Queried Importrange|E(Synthesis 2)
    B ----> |Queried Importrange|F(Synthesis 3)
    B ----> |Queried Importrange|G(Synthesis 4)
    B ----> |Queried Importrange|I(Synthesis 5)
    D <---- C(Finance Team)
    E <---- J(Other Departments/Teams)
    F <---- J
    G <---- J
    I <---- J


    style A fill:#eff,stroke:#333,stroke-width:3px,stroke-dasharray: 5 5
    style B fill:#ffb94e,stroke:#333,stroke-width:4px
    style D fill:#eff,stroke:#333,stroke-width:3px
