# [Modulation Identification] Adversarial Deep Modulation Classification Based on Data-Driven Subsampling [with MATLAB Code]

Introduction to Automatic Modulation Classification (AMC): A key feature of this technology allows receiving devices to identify the modulation type of the received signal without manual engineering or prior agreement with the transmitter. This could be one of the core functionalities of next-generation intelligent spectrum-efficient networks, allowing communication devices to freely adapt to various wireless systems without compromising spectral efficiency. To promote AMC, recent studies have explored gradient-based machine learning (ML) techniques in computer vision [1] and natural language processing [2] that have shown promising performance [3], [4]. ML methods demonstrate superior performance over traditional modulation classification algorithms, which are based on statistical classification and operate in a scalable manner with respect to the number of modulation types and samples. To address the viability of this promising technology, we consider two main aspects in this work: robustness against malicious obstruction and computational efficiency.
A. Gradient-Based Adversarial Machine Learning
ML models relying on deep neural networks optimized using stochastic gradient descent show lack of robustness against malicious adversarial examples [5], [6], which introduce small perturbations specifically designed to cause the ML model to fail when added to legitimate inputs. These perturbations are obtained by solving an optimization problem that minimizes the perturbation norm while maximizing classification error. In wireless environments, small perturbation norms correspond to the small amount of additional noise required for the interferer to introduce into the signal at the receiver, which is difficult to detect and leads to significant degradation in ML performance. Recent studies have confirmed the vulnerability of ML models for modulation classification to such adversarial examples. Usama et al. [7], [8] have demonstrated that the well-known CW attack [9] is applicable to this scenario. Moreover, Kim et al. [10], Hameed et al. [11] and Baier et al. [12] have proposed effective algorithms to generate adversarial examples, taking into account the noise encountered during actual air transmission of the perturbed signals.
B. Data-Driven Subsampling
ML models also challenge the computational capabilities of wireless devices, particularly during training phases. The long training times of deep neural networks lead to significant bottlenecks in their application in wireless communications, where frequent retraining is required to adapt in real-time to changing environments. Therefore, Ramjee et al. [13] introduced a data-driven subsampling strategy that simulates input sampling into ML models using deep learning models (called Subsampler Nets) and effectively reduces the size of deep neural network architectures and their training time. Their algorithm leverages transferability in deep learning, which exploits common features relevant to various architectures suitable for the same task. Using multiple pre-trained modulation classifiers, the algorithm ranks each input sample based on its contribution to classification results.
C. Considered Issues
To address the motivations outlined above, we investigated an effective ML-based AMC model with different data-driven subsampling strategies for robustness against adversarial attacks. As demonstrated in the sequel, understanding the subsampling network used can significantly influence both attackers' choice of optimal strategy and its effectiveness. Similarly, the knowledge of the assumed subsampling network by the attacker significantly impacts the defender's strategy. Finally, we identified a computationally efficient training strategy that minimizes the performance cost to the system when exposed to the attacker's system design.
Conclusion
We studied the effectiveness of gradient-based adversarial attacks on deep learning models that utilize data-driven subsampling for wireless modulation classification. We emphasized the use of subsampling schemes for both the victim model and the attacker to generate selective training. We believe this work lays the groundwork for further research on data-driven secondary sampling strategies for deep learning in wireless communication systems in adversarial settings. Our particular interest lies in studying the impact of SNR knowledge in such environments.

## Images

![[Modulation Identification] Adversarial Deep Modulation Classification Based on Data-Driven Subsampling [with MATLAB Code]](01.jpg)
![[Modulation Identification] Adversarial Deep Modulation Classification Based on Data-Driven Subsampling [with MATLAB Code]](02.jpg)
![[Modulation Identification] Adversarial Deep Modulation Classification Based on Data-Driven Subsampling [with MATLAB Code]](03.jpg)
![[Modulation Identification] Adversarial Deep Modulation Classification Based on Data-Driven Subsampling [with MATLAB Code]](04.jpg)
![[Modulation Identification] Adversarial Deep Modulation Classification Based on Data-Driven Subsampling [with MATLAB Code]](05.jpg)
![[Modulation Identification] Adversarial Deep Modulation Classification Based on Data-Driven Subsampling [with MATLAB Code]](06.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
