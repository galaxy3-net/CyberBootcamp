Activity
========

>Impact Levels: "Low," "Medium," "High," "Critical"

>Likelihoods: "Very Unlikely," "Unlikely," "Possible," "Likely," "Very Likely"

|               | Low    | Medium | High   | Critical |
| ------------- | ------ | ------ | ------ | -------- |
| Very Likely   | Medium | High   | High   | Critical |
| Likely        | Medium | High   | High   | Critical |
| Possible      | Medium | Medium | Medium | High     |
| Unlikely      | Low    | Low    | Medium | High     |
| Very Unlikely | Low    | Low    | Low    | Medium   |

Scenario 1:

> A vulnerability was discovered on a public-facing web server with an application that stores, processes, and transmits NPI - NonPublic Information. It is your job as a risk analyst to identify the level of risk based on the risk matrix.
  

* **Vulnerability**: A webserver was found to be running TLS v1.0 when the lowest secure version of TLS at the time was TLS 2.0.

Questions:

* What is the impact level?
* Among many threats, a (MITM) Man-in-the-Middle attack is one of them. What is the likelihood of the threat exploiting the vulnerability? Explain your reasoning.
* Using the formula Risk = Likelihood x Impact, what is the risk level? 

