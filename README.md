# phd-smartgrid-coap-cla-optimization
repository where I include all the issues and code used during my PhD


##CoAP notes

##CLA notes

##Nupic notes

Swarm automatically determines the best CLA model based on the data.
Input to the swarm: 
- dataset to optimize 
- tasks you are trying to perform (e.g. "predict voltage at node A four steps in advance").
- optionally custom metric to measure efectiveness of the model. 

| Timestamp  | Consumption  | Generation - PV1  | Generation - PV2  |  Voltage at 2 |
|---|---|---|---|---|
|   |   |   |   |   |
|   |   |   |   |   |
|   |   |   |   |   |

Ouput to the swarm:
- An OPF (Online Prediction Framework) format text file which completely describes the bes model found. 

It is possible to customize the parameters of the Swarm process.
