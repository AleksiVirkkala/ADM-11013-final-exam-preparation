---
title: Concept Map
---

> Visual overview of the 7 topic clusters and how they connect. Click any cluster to drill in.

```mermaid
graph TB
    EXAM["Final Exam<br/>17 MC + 7 essay = 100 pts"]

    CONS["Consolidation<br/>(21 pts)"]
    FXT["FX Theories<br/>(PPP, IFE, swaps)"]
    FXE["FX Exposure<br/>& Hedging"]
    TAX["Tax Mechanisms<br/>(4 ways)"]
    MNC["MNC Finance<br/>(Lessard-Lorange<br/>+ depositories)"]
    MON["Monetary System<br/>(IMF/WB, currency board,<br/>fixed vs floating)"]
    LEG["Legal Systems<br/>(common/civil, torts, IP)"]

    EXAM --> CONS
    EXAM --> FXT
    EXAM --> FXE
    EXAM --> TAX
    EXAM --> MNC
    EXAM --> MON
    EXAM --> LEG

    FXT -.PPP underlies.-> CONS
    FXT -.IFE underlies.-> FXE
    FXE -.translation = .-> CONS
    MON -.fixed/floating context.-> FXT
    TAX -.4 mechanisms used by.-> MNC
    LEG -.IP enables royalty mechanism.-> TAX

    classDef red fill:#fee2e2,stroke:#991b1b,stroke-width:2px,color:#000
    classDef orange fill:#ffedd5,stroke:#c2410c,stroke-width:1px,color:#000
    class CONS,FXT,TAX red
    class FXE,MNC,MON,LEG orange
```

🟥 = guaranteed / very high probability    🟧 = high probability

## Within Consolidation

```mermaid
graph LR
    FUNC["Functional currency<br/>(teacher gives)"] --> METHOD{Which method?}
    METHOD -->|Home = functional| TEMP[Temporal Method]
    METHOD -->|Local = functional| CURR[Current Rate Method]
    METHOD -->|High inflation| TEMP

    TEMP --> MONO[Monetary vs<br/>non-monetary distinction]
    TEMP --> PLUG1[RE is the PLUG]
    TEMP --> FX1[FX gain/loss on<br/>INCOME STATEMENT]

    CURR --> ALL[All B/S items use<br/>current rate<br/>except capital]
    CURR --> PLUG2[Exchange Adjustment<br/>is the PLUG]
    CURR --> FX2[FX adjustment on<br/>BALANCE SHEET]

    FX1 --> COMPUTE["Compute via ΔRE − Op result<br/>Label gain/loss EXPLICITLY"]
```

See [[topics/consolidation/index|Consolidation cluster]].

## Within FX Theories

```mermaid
graph LR
    LOP[Law of One Price] --> PPP[Purchasing Power Parity]
    PPP --> BMI[Big Mac Index]
    PPP --> IFE[International Fisher Effect]
    DFE[Domestic Fisher Effect<br/>nominal ≈ real + inflation] --> IFE

    PPP -.high inflation →<br/>currency depreciates.-> IFE
    IFE -.same prediction,<br/>via interest rates.-> PPP
```

See [[topics/fx-theories/index|FX Theories cluster]].

## Within Tax Mechanisms

```mermaid
graph LR
    HIGH[High-tax country<br/>e.g., Mexico 30%, UK 50%] -->|profits shift via 4 mechanisms| TAXHAVEN[Tax haven<br/>Bermuda 0%, Ireland 12.5%]

    M1[1. Transfer pricing] --> HIGH
    M2[2. Royalties on IP] --> HIGH
    M3[3. Dividend remittances] --> HIGH
    M4[4. Fronting loans] --> HIGH
```

See [[topics/tax-mechanisms/index|Tax Mechanisms cluster]].

## Within FX Exposure

```mermaid
graph TB
    FXR[FX risk] --> T1["Transaction exposure<br/>(individual deal)"]
    FXR --> T2["Translation exposure<br/>(consolidation effect)"]
    FXR --> T3["Economic exposure<br/>(long-run competitive)"]

    T1 -.financial hedge.-> HEDGE[Hedging<br/>via forwards, swaps, options]
    T2 -.financial hedge.-> HEDGE
    T3 -.strategic hedge.-> DISP[Disperse production globally]
```

See [[topics/fx-exposure/index|FX Exposure cluster]].

## Within Legal Systems

```mermaid
graph TB
    LS[3 Legal systems] --> CL[Common law<br/>UK, US, Canada]
    LS --> CV[Civil law<br/>Germany, France, Mexico]
    LS --> TC[Theocratic law<br/>Islamic countries]

    CL --> CONTRACT1[Detailed contracts<br/>spell out everything]
    CV --> CONTRACT2[Short contracts<br/>code fills gaps]

    CL --> TORTS["Torts (3 types)<br/>Intentional, Negligence,<br/>Strict liability"]

    LS --> IP[Intellectual Property]
    IP --> P[Patent ~20 yr]
    IP --> C[Copyright ~50 yr after death]
    IP --> TM[Trademark indefinite]
```

See [[topics/legal-systems/index|Legal Systems cluster]].
