# Spatial-Temporal Method for Unsupervised Learning

## Neural Systems
&nbsp;&nbsp;&nbsp;&nbsp; A neural system is a network of randomly distributed neurons that send and receive activation signals through connections. A subset receives sensory signals from the environment, and another subset passes motor signals to the environment. Feedback reflects the causal relationship between outputs and inputs and vice-versa. The interconnected neurons make up an adaptive system whose organization is shaped by the feedback loop.

***

## Neurons and Connections
&nbsp;&nbsp;&nbsp;&nbsp; A neuron is defined by two properties: its threshold, which defines the minimum activity needed to produce a signal, and position, which constrains the neurons it forms connections with. A connection is defined by three properties: its input, which is the neuron whose output it receives, its weight, which is the influence its input has on producing activation, and permanence, which is the strength of a connection.

&nbsp;&nbsp;&nbsp;&nbsp; A neuron adjusts its threshold based on the average signal strength, and adjusts the weight and permanence of connections based on the input signals that lead to activation. The permanence, if below a certain threshold, disconnects the input neuron from sending input signals. This is caused by a lack of matching activity between the sender and receiver. In other words, it removes uncorrelated neurons from sending inputs. 

***

## Spatial Learning
&nbsp;&nbsp;&nbsp;&nbsp; A neuron forms connections to other neurons based on the distance and strength of their activations. Neurons have the potential to form a connection if they reside in working memory at the same time and have a high activity-to-distance ratio. This causes local signals to occur more often than spanning activity between neurons.

***

## Temporal Learning
&nbsp;&nbsp;&nbsp;&nbsp; A neuron is stored in working memory when it produces an activation potential. The time it spends in working memory depends on the depolarization delay, which is a timer that prevents a neuron from sending and receiving signals following activation. During this time, connections may form to newly activated neurons that enter working memory. 

&nbsp;&nbsp;&nbsp;&nbsp; Neurons form connections forward in time, meaning that new neurons do not connect to those already in working memory. This is important to maintain correct order of events in a sequence. Temporal connections enable a current event to signal a future event, based on a similar experience in the past.
