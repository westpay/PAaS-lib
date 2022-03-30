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
We have written up some helpful documents over at our Wiki to help you understand more and perhaps help yuou get started with your own implementation.

### [1. Introduction](https://github.com/westpay/PAaS-lib/wiki/1.-Introduction)
### [2. Getting started](https://github.com/westpay/PAaS-lib/wiki/2.-Getting-started)
### [3. How-To guides](https://github.com/westpay/PAaS-lib/wiki/3.-How-To)
### [Limitations](https://github.com/westpay/PAaS-lib/wiki/Limitations)

## You will find the latest lib documentation here
[Posapplib overview](https://westpay.github.io/PAaS-lib/)
