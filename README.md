# BLE_device_fingerprinting

This project will evaluate the different techniques in that can be used to perform device fingerprinting through the use of BLE advertisements. This will include investigating how advertisement packets sent by different devices vary in structure and proportions, and the advertising pattern of devices i.e. time between packets.

The project directory is structured as follows:

    .
    ├── data                         # Raw and preprocessed datasets
    ├── figures                      # Saved figures from notebooks
    ├── screenshots                  # Saved screenshots
    ├── analyse_pcaps.ipynb          # Notebook for analysing device pcap files
    ├── packet_classification.ipynb  # Notebook investigating techniques for packet classification
    ├── README.md
    └── requirements.txt