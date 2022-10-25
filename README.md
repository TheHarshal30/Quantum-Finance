<div align="center"> 

   ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
   ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
   
</div>

## Context
Pricing is very strategic and it makes a big difference in how a business operates. Many businesses operate on a fixed pricing model comes with serious drawbacks. It relies on fickle buyers who are price sensitive. This makes you more vulnerable to price wars. If one of your competitors drops their prices, your buyers are at risk of jumping ship. Also fixed-price model throttles long-term relationships. You don’t have time to connect with customers.<br>
This is where <strong>Dynamic Pricing</strong> comes to save the day!
<br>
<br>
<br>


## What is <strong>Dynamic Pricing </strong> ?
Dynamic pricing, a strategy which enables businesses to provide flexible prices for products and services is now catching on across hospitality, retail, travel and entertainment industry segments. Whether the aim is to stay profitable, fill up an airplane or sell as many sports tickets or products online as possible, companies today are using dynamic pricing to achieve their business goals.
<br>
<br>
<br>
## Dataset
Dynamic Pricing can be applied to various buissness, but here we apply it to predict fare prices of OLA CABS.<br>
The dataset contains various parameters on which the price of fare depends.<br>
Click here to download the dataset.
<br>
<br>
<br>

## Methodology:
<img align="right" src="Qlayers.png" width="320" height="200">

- Converting Classical data into Quantum Data : <br>
   We convert all the classical data into a circuit. <br>
   The encoder used here is:<br>
   RX * (pi * i)<br>
   RY * (pi * i)<br>
   where i belongs to [0,1] (i.e normalized data). <br>
- Quantum Layers : <br>
   A layer consists of CNOT gate followed by RY and RZ gates <br>
- Model : <br>
    We create the Quantum model using Google's Cirq. <br>
    We know that, the number of parameters is 2 paramenters per Qubit multiplied by depth of circuit.<br>
<br>
<br>
<br>


##  Conclusion:
<img align="right" src="outputQNN.png" width="350" height="200"> 

Even with small number of epochs and short circuit depth the loss is pretty good. <br>
Implementing the code on Quantum Hardware with high number of epoches and large circuit depths would result in great accuracies in very less time.


## TechStack Used:
<ul>
1. Python <br />
2. Scikitlearn <br />
3. Numpy <br />
4. Pandas <br />
5. Tensorflow Quantum  <br />
6. Dwave Systems<br />
7. Cirq <br>
</ul>



## Support
⭐ Please Star and share the project. Thanks! ❤️
