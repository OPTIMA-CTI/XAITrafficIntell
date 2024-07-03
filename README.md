# XAITrafficIntell

This work explores the use of Machine Learning (ML) and Explainable Artificial Intelligence (XAI) for darknet traffic classification, enhancing network security.

We analyze datasets (ISCXTor2016 and CIC-Darknet2020) to identify key features for accurate traffic categorization using XAI techniques like SHAP and LIME, Permutation Importance, Counter Factual Explanation.

The project sheds light on critical factors for traffic classification, including Protocol (ISCXTor2016 traffic), Source Port (ISCXTor2016 application identification), and IdleMax (CIC-Darknet2020 traffic classification).

Furthermore, it delves into extracting Cyber Threat Intelligence from IP addresses, uncovering prevalent malware types, targeted countries, and attacker techniques (e.g., T1071 leveraging application layer protocols for evasion).

This project demonstrates the potential of XAI in understanding and classifying darknet traffic, ultimately contributing to improved network security.

1) Classification_With_XAI folder: This folder includes code for performing traffic classification across three datasets using various explainability tools.

2) Intelligence folder: The Intelligence folder contains scripts related to threat intelligence extracted from darknet traffic data.

3) SHAP_Feature_Selection folder: This folder contains code for conducting classification tasks with varying numbers of features selected based on SHAP (SHapley Additive exPlanations) summary plot results.
