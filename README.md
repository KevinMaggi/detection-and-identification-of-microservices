# Lightweight static detection and identification of microservices
Lightweight static black-box method for the detection and identification of microservices

## Execution of experiments

Before to execute the experiment is required to create a file in the dataset folder in CSV format, with only one field "URL", where to list the repositories to examine.

- docker-compose choice:
  
        python3 -m A_dc_choice_dataset {name of dataset file without extension}
  
- microservices detection:

        python3 -m A_ms_detection_dataset {name of dataset file without extension}
