# An In-Depth Study of Uplink Performance of 5G mmWave Networks
Data from our ACM SIGCOMM 5G-MeMU 2022 workshop paper where we conducted an extensive study of 5G mmWave uplink performance using commercially available mobile devices.

If you use this dataset in your publication, please cite us as follows:
```
@InProceedings{ghoshal:memu2022,
author={Ghoshal, Moinak and Kong, Z. Jonny and Xu, Qiang and Lu, Zixiao and Aggarwal, Shivang and Khan, Imran and Li, Yuanjie and Hu, Y. Charlie and Koutsonikolas, Dimitrios},
title={An In-Depth Study of Uplink Performance of 5G mmWave Networks},
booktitle={ In Proceedings of 2nd ACM SIGCOMM Workshop on 5G and Beyond Network Measurements, Modeling, and Use Cases (5G-MeMU)},
year={2022}
}
```
## Dataset Description

There are 3 measurement scenarios: Static, Walking and Driving. For each scenarios we performed multiple throughput and latency measurements using 5G and LTE networks. The data is kept in the following heriarchy:

```
throughput
          scenario
                  5g
                     *.list files
                  lte
                     *.list files
ping
    scenario
            5g
               *.list files
            lte
               *.list files
        
```
