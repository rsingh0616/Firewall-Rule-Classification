## Background

The objective of this project is to develop a machine learning model for classifying firewall rules into different categories such as Allow, Drop, and Deny. 

The dataset contains various features related to firewall rules, and the goal is to predict the classification of new firewall rules based on these features. 

The dataset has 12 columns, and a total of 262128 rows. The following are the rows:

- **Source Port**: The port number on the sender's side
- **Destination Port**: The port number on the receiver's side
- **NAT Source Port**: The Network Address Translation (NAT) translated source port.
- **NAT Destination Port**: The Network Address Translation (NAT) translated destination port.
- **Bytes**: The total number of bytes transferred
- **Bytes Sent**: The number of bytes sent
- **Bytes Received**: The number of bytes received
- **Packets**: The total number of packets transferred
- **Elapsed Time (sec)**: The duration of the communication in seconds
- **pkts_sent**: The number of packets sent
- **pkts_received**: The number of packets received
- **Class**: Label to classify the rule (Allow, Drop, Deny, Reset-both).

The following models have been used:

1.   **Decision Tree**
2.   **Random Forest**
3.   **Gradient Boosting**
4.   **K-Nearest Neighbor**
5.   **Naive Bayes**: Multinomial and Gaussian
