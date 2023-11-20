# Popular science summary of the PhD thesis

---

* PhD student: **Jakob Drachmann Havtorn**

* Title of the PhD thesis: **Uncertainty estimation for machine learning system self-assessment on medical conversations**

* PhD school/Department: **Department of Applied Mathematics and Computing, Section for Cognitive Systems**

---

The development of machine learning systems to provide support in medical conversations, such as in the primary care clinic or with emergency services, is challenging due to the high stakes of the resulting decisions and the complexity of the associated text and audio data. While neural networks have set new standards for machine learning performance, their application in healthcare can be hindered by their lack of interpretability and of their poor ability to express uncertainty about predictions, especially for rare cases and in dynamic environments.

In this thesis, we explore the use of machine learning for decision support in medical conversations and examine how to ensure robustness and reliability of the resulting systems. We study how deep neural networks can be used to learn useful representations of audio and compare probabilistic models and self-supervised approaches. Specifically, we perform a comprehensive review of modern methods for unsupervised representation learning on massive amounts of audio data, and propose a novel, probabilistic representation learner. We show how superficial commonalities between different data sources can confuse deep neural networks and make them unable to detect data that differs abnormally from the training data. Using probabilistic models and statistical hypothesis testing, we develop methods to robustly detect and reject such out-of-distribution data.

We also study applications of machine learning to the tasks of automated medical coding and early detection of stroke in emergency calls. In a detailed replicability study, we show that current medical coding models often suffer from suboptimal configuration, crudely sampled train-test splits, and insufficient evaluation, and make several contributions to remedy these issues. In a collaboration with the Copenhagen Emergency Medical Services, we develop a system to help call-takers at the 1813 medical helpline recognize patients with stroke. The system is based on speech recognition and results on historical data show that it can improve recall from 52.7% to 63.0% and precision from 17.1% to 24.9% while also decreasing the false positive rate. We discuss the role of uncertainty estimation for this system and provide preliminary results. If implemented in practice, such a system might help call-takers be confident in their decision-making, reduce the time to treatment for patients with stroke, and lower the load on the emergency services and hospitals. 
