# Early Christian Lineage Map

> People and churches only; color-coded by role/era.

```mermaid
graph LR
%% legend
LEG_J[Jesus]:::jesus --> LEG_AP[Apostles]:::apostle --> LEG_AF[Apostolic Fathers]:::apostolicF --> LEG_APO[Apologists]:::apologist --> LEG_ANT[Ante Nicene]:::anteNicene --> LEG_NIC[Nicene]:::nicene --> LEG_POST[Post Nicene]:::postNicene --> LEG_CH[Churches]:::church
%% styles
classDef jesus fill:#FFD700,stroke:#7D6608,color:#000,font-weight:bold;
classDef apostle fill:#5DADE2,stroke:#1B4F72,color:#fff;
classDef apostolicF fill:#58D68D,stroke:#145A32,color:#000;
classDef apologist fill:#F9E79F,stroke:#7D6608,color:#000;
classDef anteNicene fill:#F5B041,stroke:#7E5109,color:#000;
classDef nicene fill:#E74C3C,stroke:#641E16,color:#fff;
classDef postNicene fill:#AF7AC5,stroke:#4A235A,color:#fff;
classDef church fill:#F2F4F4,stroke:#424949,color:#000;
```

```
graph TD

%% ---------- Legend ----------
LEG_J[Jesus]:::jesus --> LEG_AP[Apostles]:::apostle --> LEG_AF[Apostolic Fathers]:::apostolicF --> LEG_APO[Apologists]:::apologist --> LEG_ANT[Ante Nicene]:::anteNicene --> LEG_NIC[Nicene]:::nicene --> LEG_POST[Post Nicene]:::postNicene --> LEG_CH[Churches]:::church

%% ---------- Jesus ----------
A[JESUS 30-33]:::jesus

%% Apostles
A --> B[Peter d64-67]:::apostle
A --> C[Paul d67]:::apostle
A --> D[John d100]:::apostle
A --> JERU[Church of Jerusalem]:::church
JERU --> JAMES[James the Just d62]:::apostolicF

%% Rome
B --> ROM[Church of Rome]:::church
ROM --> CLEM[Clement of Rome d99]:::apostolicF
ROM --> RB[Roman bishops 1st 4th c]:::church
RB --> AMB[Ambrose of Milan 340-397]:::postNicene
AMB --> AUG[Augustine of Hippo 354-430]:::postNicene
RB --> LEO[Leo the Great 400-461]:::postNicene
LEO --> GREGG[Gregory the Great 540-604]:::postNicene

%% Alexandria via Mark
B --> MARK[Mark interpreter of Peter d68]:::apostolicF
C --> MARK
MARK --> ALX[Church of Alexandria]:::church
ALX --> ANIAN[Anianus d82]:::apostolicF
ALX --> PANT[Pantaenus 2nd c]:::apostolicF
ALX --> CLEMA[Clement of Alexandria 150-215]:::anteNicene
CLEMA --> ORI[Origen 185-254]:::anteNicene
ORI --> ATH[Athanasius 296-373]:::nicene
ORI --> PAMP[Pamphilus d309]:::anteNicene
PAMP --> EUSEB[Eusebius of Caesarea 260-339]:::nicene

%% Ephesus and Crete
C --> EPH[Church of Ephesus]:::church
EPH --> TIM[Timothy d97]:::apostolicF
C --> CRE[Church of Crete]:::church
CRE --> TIT[Titus d96]:::apostolicF

%% Antioch
C --> ANT[Church of Antioch Acts 11]:::church
ANT --> ANTMB[Paul and Barnabas base 40s-50s]:::church
ANTMB --> IGN[Ignatius d110]:::apostolicF
IGN --> ANTSCH[Antiochene tradition]:::church
ANTSCH --> CHRYS[John Chrysostom 347-407]:::postNicene
ANTSCH --> THEO[Theophilus of Antioch d183]:::apologist

%% Paul links
C --> CLEM

%% Smyrna and Asia Minor
D --> SMY[Church of Smyrna]:::church
SMY --> POLY[Polycarp 69-155]:::apostolicF
POLY --> IREN[Irenaeus 130-202]:::anteNicene
IREN --> HIPP[Hippolytus 170-235]:::anteNicene
D --> PAPI[Papias 60-130]:::apostolicF

%% Carthage
ROM --> CAR[Church of Carthage]:::church
CAR --> TERT[Tertullian 155-220]:::anteNicene
CAR --> CYPR[Cyprian 200-258]:::anteNicene
CYPR --> AUG

%% Apologists from Rome
ROM --> JUST[Justin Martyr 100-165]:::apologist
JUST --> TAT[Tatian 120-180]:::apologist
TAT --> SYR[Syrian Church]:::church
ROM --> ATHEN[Athenagoras 133-190]:::apologist
ROM --> MIN[Minucius Felix c200]:::apologist

%% Ante Nicene additions
ROM --> NOV[Novatian 200-258]:::anteNicene
ROM --> METH[Methodius d311]:::anteNicene

%% Cappadocia
B --> CAP_PEN[Pentecost Cappadocians 30s]:::church
CAP_PEN --> CAP_CH[Churches of Cappadocia 60s]:::church
CAP_CH --> CAP_EB[Early Cappadocian bishops]:::church
CAP_EB --> BAS[Basil 330-379]:::nicene
CAP_EB --> GNY[Gregory of Nyssa 335-395]:::nicene
CAP_EB --> GNAZ[Gregory Nazianzus 329-390]:::nicene
CAP_EB --> HIL[Hilary of Poitiers 310-367]:::nicene

%% Nicene controversy
ROM --> EUNIC[Eusebius of Nicomedia d341]:::nicene

%% Post Nicene West
RB --> JER[Jerome 347-420]:::postNicene

%% ---------- Styles ----------
classDef jesus fill:#FFD700,stroke:#7D6608,color:#000,font-weight:bold;
classDef apostle fill:#5DADE2,stroke:#1B4F72,color:#fff;
classDef apostolicF fill:#58D68D,stroke:#145A32,color:#000;
classDef apologist fill:#F9E79F,stroke:#7D6608,color:#000;
classDef anteNicene fill:#F5B041,stroke:#7E5109,color:#000;
classDef nicene fill:#E74C3C,stroke:#641E16,color:#fff;
classDef postNicene fill:#AF7AC5,stroke:#4A235A,color:#fff;
classDef church fill:#F2F4F4,stroke:#424949,color:#000;

%% keep only people + churches, with dates, and the corrections we made
%% GitHub renders Mermaid in Markdown, so it will show on the repo and Pages

%% styles
classDef jesus fill:#FFD700,stroke:#7D6608,color:#000,font-weight:bold;
classDef apostle fill:#5DADE2,stroke:#1B4F72,color:#fff;
classDef apostolicF fill:#58D68D,stroke:#145A32,color:#000;
classDef apologist fill:#F9E79F,stroke:#7D6608,color:#000;
classDef anteNicene fill:#F5B041,stroke:#7E5109,color:#000;
classDef nicene fill:#E74C3C,stroke:#641E16,color:#fff;
classDef postNicene fill:#AF7AC5,stroke:#4A235A,color:#fff;
classDef church fill:#F2F4F4,stroke:#424949,color:#000;
