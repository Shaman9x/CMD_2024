📊 Dataset Overview
CMD_2024 Dataset for Cloud-based Malware Detection (9 Classes):

The CMD_2024 dataset is a curated collection designed to support research and development in malware detection using Machine Learning (ML) and Deep Learning (DL) approaches. It enables both binary (malicious vs benign) and multi-class classification tasks.

🏷️ Labeling Conventions for Executable File Samples

| No. | Label        | Binary Label | Multi-class Label | Quantity |
|-----|--------------|--------------|--------------------|----------|
| 1   | Benign       | 0            | 0                  | 5,016    |
| 2   | Virus        | 1            | 1                  | 3,955    |
| 3   | Trojan       | 1            | 2                  | 7,484    |
| 4   | Worm         | 1            | 3                  | 2,673    |
| 5   | Ransomware   | 1            | 4                  | 751      |
| 6   | Adware       | 1            | 5                  | 800      |
| 7   | Miner        | 1            | 6                  | 90       |
| 8   | PUA          | 1            | 7                  | 49       |
| 9   | Downloader   | 1            | 8                  | 32       |
|     | **Total**    |              |                    | **20,850** |


📌 Key Features

Supports ML/DL training for both binary and multi-class classification.

Includes both static and dynamic attributes of malware.

Suitable for cloud-based environments and publicly accessible use.

Accompanied by detailed documentation of the dataset creation process.

🧬 Why Static and Dynamic Attributes Matter
Static features include characteristics such as encryption methods, code structures — typically extracted from executable files or metadata. These allow models to learn patterns without running the sample.

🎯 Purpose and Impact
The CMD_2024 dataset was developed to address the growing need for reliable, rich, and diverse data sources in the cybersecurity field. By combining malicious and benign samples with a wide spectrum of behavior and structure, this dataset helps:
- Improve ML/DL model generalization
- Reduce false positives and misclassification
- Enhance real-world malware detection systems

📚 Citation
If you use the CMD_2024 dataset in your research or application, please cite the following paper:
@article{NGUYEN2025104233,
  title     = {Hybrid feature extraction and integrated deep learning for cloud-based malware detection},
  journal   = {Computers & Security},
  volume    = {150},
  pages     = {104233},
  year      = {2025},
  issn      = {0167-4048},
  doi       = {https://doi.org/10.1016/j.cose.2024.104233},
  url       = {https://www.sciencedirect.com/science/article/pii/S016740482400539X},
  author    = {Pham Sy Nguyen and Tran Nhat Huy and Tong Anh Tuan and Pham Duy Trung and Hoang Viet Long},
  keywords  = {Cloud-based malware dataset, Cloud-based malware detection, Integrated deep learning, Static analysis, Dynamic analysis},
  abstract  = {The escalating prevalence of malware necessitates a proactive and vigilant approach to its detection and mitigation. The ramifications of a successful malware attack on cloud services can be severe, underscoring the critical importance of effective malware detection mechanisms in cloud environments. To address this pressing need, we propose a comprehensive methodology for creating a novel cloud-based malware dataset, namely the CMD_2024 dataset. This dataset integrates static and dynamic attributes, providing a robust framework for malware analysis. The CMD_2024 dataset, comprising 20,850 samples meticulously labeled into various malware categories such as Virus, Trojan, Worm, Ransomware, Adware, Miner, PUA, and Downloader, is designed to facilitate the testing and evaluation of diverse analysis tools, machine learning models, deep learning models, and security systems. We enhance the dataset’s utility and effectiveness by focusing on dynamic features, particularly system calls within the cloud, in conjunction with static attributes. To address the challenges of the imbalance towards less common malware categories in the dataset, we employed the Conditional Tabular Generative Adversarial Network to generate synthetic data, significantly improving the detection capability for these rare malware samples. The application of various machine learning and deep learning classifiers, including our proposed integrated deep learning models, yielded remarkable results, achieving 99.42% accuracy in binary classification and 86.97% in multi-class classification. These outcomes demonstrate the CMD_2024 dataset’s substantial efficacy in supporting robust malware detection within cloud environments.}
}

