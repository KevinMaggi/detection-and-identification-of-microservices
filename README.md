[UPDATE] A version of this tool has been released and its effectivness and efficiency have been evaluated in a conference paper whose replication package is available [here](https://github.com/KevinMaggi/CLAIM_rep-pkg)

# Lightweight static detection and identification of microservices
This repository contains a lightweight static black-box method for the detection and identification of microservices, as part of the master thesis work entitled: "Analysis of the Evolution of Code Techinical Debt in Microservices Architectures" in Computer Engineering at University of Florence, whose replication package is available [here](https://github.com/KevinMaggi/evolution-of-code-td-in-msa_rep-pkg).

## Execution of experiments

- docker-compose choice:
  
        python3 -m A_dc_choice_dataset 64-MSA
  
- microservices detection:

        python3 -m A_ms_detection_dataset 64-MSA
