
# Pipeline core96_v0.6 

## Description

<-- put pipeline description here -->

## Components

- **Extractor:** default
- **Isolator:** min
- **AbsPower Trainers:**

  - PolynomialRegressionTrainer
  - GradientBoostingRegressorTrainer
  - SGDRegressorTrainer
  - KNeighborsRegressorTrainer
  - LinearRegressionTrainer
  - SVRRegressorTrainer


- **DynPower Trainers:** 

  (same as AbsPower Trainers)

## Workload information


### stressng

<-- put workload description here -->

<details>

| stress |
| --- |
| none;sleep;none;none;none |
| 3900000;cpu;1;none;none |
| 3900000;cpu;2;none;none |
| 1725000;cpu;4;none;none |
| 1725000;cpu;8;none;none |
| 1725000;cpu;16;none;none |
| 1725000;cpu;32;none;none |
| 1725000;cpu;48;none;none |
| 1725000;cpu;72;none;none |
| 1725000;cpu;96;none;none |
| 2450000;cpu;4;none;none |
| 2450000;cpu;8;none;none |
| 2450000;cpu;16;none;none |
| 2450000;cpu;32;none;none |
| 2450000;cpu;48;none;none |
| 2450000;cpu;72;none;none |
| 2450000;cpu;96;none;none |
| 3175000;cpu;4;none;none |
| 3175000;cpu;8;none;none |
| 3175000;cpu;16;none;none |
| 3175000;cpu;32;none;none |
| 3175000;cpu;48;none;none |
| 3175000;cpu;72;none;none |
| 3175000;cpu;96;none;none |
| 3900000;cpu;4;none;none |
| 3900000;cpu;8;none;none |
| 3900000;cpu;16;none;none |
| 3900000;cpu;32;none;none |
| 3900000;cpu;48;none;none |
| 3900000;cpu;72;none;none |
| 3900000;cpu;96;none;none |
| 1725000;branch;4;none;none |
| 1725000;branch;8;none;none |
| 1725000;branch;16;none;none |
| 1725000;branch;32;none;none |
| 1725000;branch;48;none;none |
| 1725000;branch;72;none;none |
| 1725000;branch;96;none;none |
| 2450000;branch;4;none;none |
| 2450000;branch;8;none;none |
| 2450000;branch;16;none;none |
| 2450000;branch;32;none;none |
| 2450000;branch;48;none;none |
| 2450000;branch;72;none;none |
| 2450000;branch;96;none;none |
| 3175000;branch;4;none;none |
| 3175000;branch;8;none;none |
| 3175000;branch;16;none;none |
| 3175000;branch;32;none;none |
| 3175000;branch;48;none;none |
| 3175000;branch;72;none;none |
| 3175000;branch;96;none;none |
| 3900000;branch;4;none;none |
| 3900000;branch;8;none;none |
| 3900000;branch;16;none;none |
| 3900000;branch;32;none;none |
| 3900000;branch;48;none;none |
| 3900000;branch;72;none;none |
| 3900000;branch;96;none;none |
| 1725000;regs;4;none;none |
| 1725000;regs;8;none;none |
| 1725000;regs;16;none;none |
| 1725000;regs;32;none;none |
| 1725000;regs;48;none;none |
| 1725000;regs;72;none;none |
| 1725000;regs;96;none;none |
| 2450000;regs;4;none;none |
| 2450000;regs;8;none;none |
| 2450000;regs;16;none;none |
| 2450000;regs;32;none;none |
| 2450000;regs;48;none;none |
| 2450000;regs;72;none;none |
| 2450000;regs;96;none;none |
| 3175000;regs;4;none;none |
| 3175000;regs;8;none;none |
| 3175000;regs;16;none;none |
| 3175000;regs;32;none;none |
| 3175000;regs;48;none;none |
| 3175000;regs;72;none;none |
| 3175000;regs;96;none;none |
| 3900000;regs;4;none;none |
| 3900000;regs;8;none;none |
| 3900000;regs;16;none;none |
| 3900000;regs;32;none;none |
| 3900000;regs;48;none;none |
| 3900000;regs;72;none;none |
| 3900000;regs;96;none;none |
| 1725000;l1cache;4;none;none |
| 1725000;l1cache;8;none;none |
| 1725000;l1cache;16;none;none |
| 1725000;l1cache;32;none;none |
| 1725000;l1cache;48;none;none |
| 1725000;l1cache;72;none;none |
| 1725000;l1cache;96;none;none |
| 2450000;l1cache;4;none;none |
| 2450000;l1cache;8;none;none |
| 2450000;l1cache;16;none;none |
| 2450000;l1cache;32;none;none |
| 2450000;l1cache;48;none;none |
| 2450000;l1cache;72;none;none |
| 2450000;l1cache;96;none;none |
| 3175000;l1cache;4;none;none |
| 3175000;l1cache;8;none;none |
| 3175000;l1cache;16;none;none |
| 3175000;l1cache;32;none;none |
| 3175000;l1cache;48;none;none |
| 3175000;l1cache;72;none;none |
| 3175000;l1cache;96;none;none |
| 3900000;l1cache;4;none;none |
| 3900000;l1cache;8;none;none |
| 3900000;l1cache;16;none;none |
| 3900000;l1cache;32;none;none |
| 3900000;l1cache;48;none;none |
| 3900000;l1cache;72;none;none |
| 3900000;l1cache;96;none;none |
| 1725000;cache;4;none;none |
| 1725000;cache;8;none;none |
| 1725000;cache;16;none;none |
| 1725000;cache;32;none;none |
| 1725000;cache;48;none;none |
| 1725000;cache;72;none;none |
| 1725000;cache;96;none;none |
| 2450000;cache;4;none;none |
| 2450000;cache;8;none;none |
| 2450000;cache;16;none;none |
| 2450000;cache;32;none;none |
| 2450000;cache;48;none;none |
| 2450000;cache;72;none;none |
| 2450000;cache;96;none;none |
| 3175000;cache;4;none;none |
| 3175000;cache;8;none;none |
| 3175000;cache;16;none;none |
| 3175000;cache;32;none;none |
| 3175000;cache;48;none;none |
| 3175000;cache;72;none;none |
| 3175000;cache;96;none;none |
| 3900000;cache;4;none;none |
| 3900000;cache;8;none;none |
| 3900000;cache;16;none;none |
| 3900000;cache;32;none;none |
| 3900000;cache;48;none;none |
| 3900000;cache;72;none;none |
| 3900000;cache;96;none;none |
| 1725000;stream;4;none;none |
| 1725000;stream;8;none;none |
| 1725000;stream;16;none;none |
| 1725000;stream;32;none;none |
| 1725000;stream;48;none;none |
| 1725000;stream;72;none;none |
| 1725000;stream;96;none;none |
| 2450000;stream;4;none;none |
| 2450000;stream;8;none;none |
| 2450000;stream;16;none;none |
| 2450000;stream;32;none;none |
| 2450000;stream;48;none;none |
| 2450000;stream;72;none;none |
| 2450000;stream;96;none;none |
| 3175000;stream;4;none;none |
| 3175000;stream;8;none;none |
| 3175000;stream;16;none;none |
| 3175000;stream;32;none;none |
| 3175000;stream;48;none;none |
| 3175000;stream;72;none;none |
| 3175000;stream;96;none;none |
| 3900000;stream;4;none;none |
| 3900000;stream;8;none;none |
| 3900000;stream;16;none;none |
| 3900000;stream;32;none;none |
| 3900000;stream;48;none;none |
| 3900000;stream;72;none;none |
| 3900000;stream;96;none;none |
| 1725000;sctp;4;none;none |
| 1725000;sctp;8;none;none |
| 1725000;sctp;16;none;none |
| 1725000;sctp;32;none;none |
| 1725000;sctp;48;none;none |
| 1725000;sctp;72;none;none |
| 1725000;sctp;96;none;none |
| 2450000;sctp;4;none;none |
| 2450000;sctp;8;none;none |
| 2450000;sctp;16;none;none |
| 2450000;sctp;32;none;none |
| 2450000;sctp;48;none;none |
| 2450000;sctp;72;none;none |
| 2450000;sctp;96;none;none |
| 3175000;sctp;4;none;none |
| 3175000;sctp;8;none;none |
| 3175000;sctp;16;none;none |
| 3175000;sctp;32;none;none |
| 3175000;sctp;48;none;none |
| 3175000;sctp;72;none;none |
| 3175000;sctp;96;none;none |
| 3900000;sctp;4;none;none |
| 3900000;sctp;8;none;none |
| 3900000;sctp;16;none;none |
| 3900000;sctp;32;none;none |
| 3900000;sctp;48;none;none |
| 3900000;sctp;72;none;none |
| 3900000;sctp;96;none;none |

repetition: 1

</details>

        
    