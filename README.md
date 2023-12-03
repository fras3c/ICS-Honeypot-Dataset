# ICS Honeypot Interactions: A Latitudinal Study (dataset and analysis framework)
Welcome to the "ICS-Honeypot-Dataset". Our dataset consists of both IT and ICS interactions gathered over a three-month period from our HoneyICS deployment, actively exposed to the internet.

## Overview

This repository contains the dataset and associated Jupyter notebook for the paper titled "ICS Honeypot Interactions: A Latitudinal Study." The paper investigates the proliferation of sophisticated threats targeting Industrial Control Systems (ICSs) and presents a latitudinal study on a dataset collected from an ICS honeynet. The honeynet emulates ICS devices exposed on the Internet, providing insights into the level of interaction, origin of interactions, and interaction/attack patterns.

## Paper Abstract

The recent proliferation of sophisticated threats targeting the plant of Industrial Control Systems (ICSs) has triggered a growing interest in the development of  dedicated honeypots/honeynets in which the emulation of Operational Technology (OT) components plays a major role. This work presents a latitudinal study on a dataset comprising both IT and ICS interactions collected from an instance of an ICS honeynet emulating ICS devices exposed on the Internet for three months. 
The study focuses on three orthogonal aspects of such interactions: level of interaction, origin of interactions, and interaction/attack patterns. 
Our results shed light on the impact of different choices in the configuration of a honeynet on its attractiveness and on the captured behavior.

## References
- F. Lupia, M. Lucchese, M. Merro, N. Zannone. ICS Honeypot Interactions: A Latitudinal Study. In 6th CyberHunt@IEEE BigData 2023, pp. 1-10.
- M. Lucchese, F. Lupia, M. Merro, F. Paci, N. Zannone, A. Furfaro. HoneyICS: A High-interaction Physics-aware Honeynet for Industrial Control Systems. In 19th ARES, pp. 113:1-113:10, ACM press, 2023, https://doi.org/10.1145/3600160.3604984.


## Repository Contents

-   **Dataset:** The dataset folder contains the raw data used in the study.
-   **Jupyter Notebook:** The notebook, named "ICS_Honeypot_Latitudinal_Study.ipynb," replicates research questions 1 to 7.
-   **Manual Analysis:** Research questions 8 to 10 were addressed manually, and details can be found in the paper.

## How to Use the Jupyter Notebook

1.  **Install Dependencies:** Ensure that you have the necessary dependencies installed. Follow the installation guide for guidance.
2.  **Open the Jupyter Notebook:** Launch the Jupyter notebook by running `jupyter notebook` in your terminal.
3.  **Run Cells Sequentially:** Execute the notebook cells in order to replicate the research questions 1 to 7.
4.  **Manual Analysis:** For research questions 8 to 10, refer to the paper for manual analysis details.

Feel free to explore and contribute to this repository. If you have any questions or encounter issues, please open an issue for discussion.
