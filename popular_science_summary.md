# Popular science summary of the PhD thesis

---

* PhD student: **Jakob Drachmann Havtorn**

* Title of the PhD thesis: **Uncertainty estimation for machine learning system self-assessment on medical conversations**

* PhD school/Department: **Department of Applied Mathematics and Computing, Section for Cognitive Systems**

---

Machine learning is increasingly being used in healthcare where its flexibility allows assisting in a wide range of tasks including diagnostics, electronic health record analysis, medical coding, and documentation. Machine learning has the potential to aid in rapid and accurate diagnosis and treatment of patients, and to assist healthcare professionals in repetitive and administrative workloads, allowing them to focus on more important tasks. 

The development of machine learning systems to provide support in medical encounters such as in the primary care clinic or with emergency services, is challenging due to the high stakes of the resulting decisions the complexity of the data, which is often unstructured text and audio. 
While machine learning systems based on neural networks have been shown to often perform very well, their application in healthcare can be hindered by their lack of interpretability and of their inability to express uncertainty about their predictions, especially for rare cases and in dynamic environments.

In this thesis, we explore the use of machine learning for decision support in medical conversations and encounters examining how to process the medical text and audio data and ensure robustness and reliability of the resulting systems. 
We study how deep neural networks can be used to learn useful representations of audio, comparing probabilistic models and self-supervised approaches. We provide a comprehensive review of self-supervised methods and propose a new probabilistic model for audio data. 
To improve robustness to potentially harmful inputs, we propose new methods using probabilistic models and statistical hypothesis testing and show that they can be used to detect and reject data that differs from the training data. 
In a detailed replicability study of automated medical coding, we show that current work often suffers from suboptimal configuration, crudely sampled train-test splits, and insufficient evaluation, and make a number of contributions to remedy these issues. 

In a collaboration with the Copenhagen Emergency Services, we develop a system to help call-takers at the 1813 medical helpline recognize patients with stroke. The system is based on speech recognition and results on historical data show that it can increase call-taker recall from 52.7% to 63.0% and precision from 17.1% to 24.9% while also decreasing the false positive rate. We discuss the role of uncertainty estimation for this system and provide preliminary results. If implemented in practice, such a system might help call-takers be confident in their decision-making, reduce the time to treatment for patients with stroke, and lower the load on the emergency services and hospitals. 
