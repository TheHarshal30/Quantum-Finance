<div align="center"> 
  <h1>Quantum Dynamic Pricing</h1>

  </div>
<div align="center"> 

   ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
   ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
   
</div> 
<div align="center"> 
  <img src="res/dynamic.png" height=300>
 </div> 

<br>

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
<img align="right" src="res/Qlayers.png" width="320" height="200">

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
- Optimal Discount Pricing : <br>
   We also made a Optimal Discount Pricing Engine using Dwave's Simulated Annealing Sampler.(Ising Model) <br>
   We have demonstrated the results using sample data for ease of understanding. <br> 
   
<br>
<br>
<br>


##  Conclusion:
<img align="right" src="res/outputQNN.png" width="350" height="200"> 

Even with small number of epochs and short circuit depth the loss is pretty good. <br>
Implementing the code on Quantum Hardware with high number of epoches and large circuit depths would result in great accuracies in very less time.


## TechStack Used:
<ul>
<li>
Cirq
</li>
<li>
Tensorflow Quantum
</li>
<li>
Dwave Systems
</li>
<li>
Pandas
</li>
<li>
Numpy
</li>
</ul>



## Support
⭐ Please Star and share the project. Thanks! ❤️
