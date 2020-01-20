# DevOps

The main goal of the following techniques are to accelerate time to market and improve code quality. Then, there will be explaining 3 techniques using in the Agile software development and it's important to take into account.


## Continuous Integration

Is critical in multiple dev teams on a project. Avoid integration hell, the commond "I don't know whats happend, it works on my machine".


Suggests the tested and integration of my code with the others developers'code and with the existing codebase, that process allow an immediate feedback about code and integration erros. 

The process of integrate the code it's preferably to do daily or even several times per day, that's why "continuous" . 


## Continuous Delivery 

Consist in packing the software for deployment in a production-like enviroment, for example staging branch. The goal is to make sure that we are building a product that can be released to production at any time: the software is always ready to go to production. 

This process requiere to building, testing and releasing faster and more frequently and have benefits for the business users because as soon as the code is successfully accepted in the continuous integration, it can be released to users and let to generate feedback and check expectations.

## Continuos Deployment

The process that automatically deploys the result of Continuous Delivery into the final production environment. This practice requiere excellent automated testing coverage and to roll back changes quickly if something goes wrong. 


## So ...
You can think about it as a pyramid, where the Continuous Integration is at the bottom, Continuous Deployment in the middle and Continuous Delivery on the top. You can have only one of them or two of them at a time, and sometimes there is no other way around, but with the full stack the process of development supposed to be effective and efficient and the set of interconnected those practices is a great tool for developers to make customers happy and developers professional


Ref: https://stackify.com/continuous-delivery-vs-continuous-deployment-vs-continuous-integration/




