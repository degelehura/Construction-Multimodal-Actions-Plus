# CMAP Dataset: Split Files, Annotations, and Training Configurations 
﻿ 
This repository contains the data partition lists, annotations, and exact training/inference configurations for the **Construction Multimodal Actions Plus (CMAP)** dataset, as presented in the paper: *"Multimodal Large Language Model-Driven Method for Construction Worker Behavior Recognition"*. 
﻿ 
## 📂 Repository Contents 
﻿ 
To ensure full reproducibility of our evaluation protocol, we publicly release the following core resources: 
﻿ 
1. **`train.txt` & `test.txt` (Split Files & Annotations)**:  
 - It will be published in the document after being accepted. You can refer to the example format of related documents.
 - **Annotation Format**:
 - It will be published in the document after being accepted. You can refer to the example format of related documents. 
 ﻿ 
2. **`train_config.txt`**:  
 - It will be published in the document after being accepted. You can refer to the example format of related documents.
   
3. **`test_config.txt`**:  
 - It will be published in the document after being accepted. You can refer to the example format of related documents. 
--- 
﻿ 
## ⚙️ Training & Inference Hyperparameters 
﻿ 
### Training Configuration (from `train_config.txt`) 
- **Base Model**: InternVL3.5-4B-hf 
- **Finetuning Type**: LoRA 
... 

### Inference Configuration (from `test_config.txt`) 
- **Temperature**: 1.00 
... 
﻿ 
## ⚠️ Data Availability & Access to Video Dataset 
﻿ 
In accordance with academic ethics, worker privacy protection, and third-party licensing agreements, **the raw or processed video clips of the CMAP dataset are NOT publicly hosted in this repository.** 
﻿ 
**Licensing & Authorization**:  
The CMAP dataset incorporates source videos collected from public online platforms and the foundational dataset developed by Yang et al.. We have obtained explicit permission from the original authors to use their foundational video data and expand upon it for this academic research. 
﻿ 
**Restricted Access Mechanism**: 
 - It will be published in the document after being accepted. You can refer to the example format of related documents. 

**Contact for Dataset Access**:  
- It will be published in the document after being accepted. You can refer to the example format of related documents. 
﻿ 
## 🛠️ Framework Versions 
The configurations in this repository were tested with the following environment: 
- PEFT: 0.15.2 
- Transformers: 4.52.4 
- PyTorch: 2.5.1+cu124 
- Datasets: 3.1.0 
- Tokenizers: 0.21.4  

﻿ 
## 📚 Citation 
If you use the CMAP dataset splits, annotations, or configurations in your research, please cite our paper: 
```bibtex 
 - It will be published in the document after being accepted. You can refer to the example format of related documents. 
