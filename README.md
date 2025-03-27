# DarkWrt -  a Dataset of Potentially Unwanted Functions in IoT Devices

## About DarkWrt
To facilitate research on detecting potentially unwanted functions in IoT devices, we created DarkWrt by modifying OpenWrt, an open-source Linux distribution for routers. Unlike datasets that only provide source code or binaries, DarkWrt can be deployed as a fully functional router, enabling both static and dynamic analysis. DarkWrt implements the following potentially unwanted functions:
- Hidden accounts for WebUI and SSH authentication
- Hard-coded credentials
- Privilege escalation capabilities (root group account addition, password-less sudo execution)
- Data breach functions (packet sniffing, time-triggered data transfer, configuration information retrieval)
- Configuration modification features (port-based Telnet backdoor, firewall settings manipulation)
- Kill switch (denial-of-service capabilities)
- Trace removal function

For details, please check the following.

https://www.ndss-symposium.org/wp-content/uploads/2025-poster-35.pdf

## Contact
Please contact the following email address if you would like to use DarkWrt.

ynugr-darkwrt@ynu.ac.jp


## Call for Collaborators
Our efforts alone are limited in identifying different types of potentially unwanted functions and comprehensively covering their implementations.
We are seeking collaborators to help us expand our dataset.

## Our publication
```
@inproceedings{Uezono2025DarkWrt,
  title     = {{Poster: DarkWrt: Towards Building a Dataset of Potentially Unwanted Functions in IoT Devices}},
  author    = {Uezono, Daichi and Kushibiki, Junnosuke and Sasaki, Takayuki and Hara, Satoshi and Zhauniarovich, Yury and Gañán, Carlos H. and van Eeten, Michel and Yoshioka, Katsunari},
  booktitle = {Poster presented at the Network and Distributed System Security Symposium (NDSS) 2025},
  year      = {2025},
  url       = {https://www.ndss-symposium.org/wp-content/uploads/2025-poster-35.pdf}
}
```
