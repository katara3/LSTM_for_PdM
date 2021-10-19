Deep Learning for Predictive Maintenance
Deep learning has proven to show superior performance in certain domains such as object recognition and image classification. It has also gained popularity in domains such as finance where time-series data plays an important role. Predictive Maintenance is also a domain where data is collected over time to monitor the state of an asset with the goal of finding patterns to predict failures which can also benefit from certain deep learning algorithms. Among the deep learning methods, Long Short Term Memory LSTM networks are especially appealing to the predictive maintenance domain due to the fact that they are very good at learning from sequences. This fact lends itself to their applications using time series data by making it possible to look back for longer periods of time to detect failure patterns. In this notebook, we build an LSTM network for the data set and scenario described at Predictive Maintenance Template to predict remaining useful life of aircraft engines using the Turbofan Engine Degradation Simulation Data Set. In summary, the template uses simulated aircraft sensor values to predict when an aircraft engine will fail in the future so that maintenance can be planned in advance.

Requirements
We suggest that you use Data Science Virtual Machine for this tutorial which comes with CNTK pre-installed. You can then configure to enable CNTK as Keras back end.

Acknowledgments
This tutorial is prepared in collaboration with Ilia Karmanov, Mathew Salvaris and Francesca Lazzeri.

Contributing
This project has adopted the Microsoft Open Source Code of Conduct. For more information see the Code of Conduct FAQ or contact opencode@microsoft.com with any additional questions or comments.
