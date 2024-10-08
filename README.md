# CAN-train-test-Evaluation.
Detecting Attacks on the CAN Protocol with Machine Learning

The motivation behind this project is the need to address the security vulnerabilities of the Controller Area Network (CAN) protocol used in modern vehicles. The CAN protocol was not designed with security in mind, making it susceptible to various attacks such as DoS, fuzzy, and impersonation attacks. These attacks can compromise driver safety and vehicle system integrity, posing a significant threat.  This study investigates the detection of attacks on the Controller Area Network (CAN) protocol using machine learning (ML) algorithms within Intrusion Detection Systems (IDSs) for In-Vehicle Networks (IVNs). 

The Control Area Network (CAN) is a widely adopted communication protocol used in vehicles for transmitting messages between devices, or nodes, without specifying source or destination addresses. This lack of identification makes CAN susceptible to attacks, allowing malicious messages to be injected into the system. In this project, the "can-train-and-test" dataset, which includes data from four vehicles produced by two manufacturers. The dataset, which is pre-processed and labeled, contains samples of normal traffic and nine types of attack traffic. The project conducts a benchmark analysis of various machine learning models to detect these attacks. Implemented in Python using Pandas and Scikit-learn, both supervised and unsupervised models, alongside deep learning methods, were evaluated on multiple data subsets. A decision tree was also developed to classify 9 attacks based on performance metrics, prioritizing models with the highest detection accuracy and reliability. 

The Multi-Layer Perceptron (MLP) emerged as the best performer, achieving an accuracy of 0.9927, but required significant computational resources. K-Nearest Neighbors (KNN) and Decision Tree models also showed high accuracy but struggled with lower AUC (Area Under the Curve) scores and efficiency. Logistic Regression was the most efficient in terms of training and testing times, although less accurate. The unsupervised BIRCH (Balanced Iterative Reducing and Clustering using Hierarchies) model performed well in classification but had poor AUC values. The Decision Tree model performed exceptionally well in detecting simpler, more consistent attack types like Standstill, Force Neutral, RPM/Speed Accessories, and Interval Attacks, achieving near-perfect accuracy, precision, and recall. This analysis reveals the compromise between model accuracy, computational cost, and robustness, helping to choose effective intrusion detection systems for CAN networks. 

Keywords: Control area network (CAN), Machine Learning, Attacks, Anomaly Detection. 

 

 
