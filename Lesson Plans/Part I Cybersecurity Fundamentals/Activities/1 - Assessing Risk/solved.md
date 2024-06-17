Activity
========

>Impact Levels: "Low," "Medium," "High," "Critical"

>Likelihoods: "Very Unlikely," "Unlikely," "Possible," "Likely," "Very Likely"


| Risk Matrix   | Low Impact | Medium | High     | Critical |
| ------------- | ---------- | ------ | -------- | -------- |
| Very Likely   | Medium     | High   | Critical | Critical |
| Likely        | Medium     | High   | High     | Critical |
| Possible      | Medium     | Medium | High     | High     |
| Unlikely      | Low        | Medium | Medium   | High     |
| Very Unlikely | Low        | Low    | Low      | Medium   |

---
Scenario 1:

> A vulnerability was discovered on a public-facing web server with an application that stores, processes, and transmits NPI - NonPublic Information. It is your job as a risk analyst to identify the level of risk based on the risk matrix.
  

* **Vulnerability**: A webserver was found to be running TLS v1.0 when the lowest secure version of TLS at the time was TLS 2.0.

Questions:

* What is the impact? High because NPI is a sensitive data classification.
* What is the likelihood if the threat is a (MITM) Man-in-the-Middle attack? Explain your reasoning. Very Likely because we can't control MITM attacks on the Internet.
* Using the formula Risk = Likelihood x Impact (use the matrix), what is the risk level? Critical

---
Scenario 2:

> A vulnerability was discovered on an internal web server with an application that stores, processes, and transmits NPI - NonPublic Information. It is your job as a risk analyst to identify the level of risk based on the risk matrix.
  

* **Vulnerability**: A webserver was found to be running TLS v1.0 when the lowest secure version of TLS at the time was TLS 2.0.

Questions:

* What is the impact? High because NPI is a sensitive data classification.
* What is the likelihood if the threat is a (MITM) Man-in-the-Middle attack? Explain your reasoning. Unlikely because we control the internal network with monitoring tools and other mitigating controls.
* Using the formula Risk = Likelihood x Impact (use the matrix), what is the risk level? Medium

>>If you disagree with the ratings in either scenario doesn't mean that you are wrong. Everyone has differing opinions of impact and more especially likelihood. If it's your job to assess risk, don't let anyone tell you that your assessment is wrong. Don't second guess yourself.
