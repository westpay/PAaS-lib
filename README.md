# What is PAaS-lib?
Payment Application as Service is Westpay's solution for running Android apps on our payment terminals.

## So, how does it work?
The process is fairly simple and straight forward:
* After system boot the terminal performs a few automatic checks and once ready starts the Westpay Payment Application (PA)
* Once ready, the PA launches **your App** and hands over the control of the device to **You** and then goes into idle
* When **your App** starts you supply the PA with a set of instructions that later will be used to perform payments
* Your App is now in control of the terminal and can be used to operate your application without any restrictions
* When ready, your App sends a request to the our PA via the PAaS lib to perform payments

## Interested to find out more?
We have written up some helpful documents over at our Wiki to help you understand more and perhaps get started with your implementation.


