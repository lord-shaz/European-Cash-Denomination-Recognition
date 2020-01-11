# European-Cash-Denomination-Recognition
-----
### Problem Statement:
-----
* To build a system that recognize different cash denomination, people can make a cash deposite in a bank machine or make a purchase using vending machine both the system have to determine the amount  of money you've deposited in them automatically. ATM uses human to verify the amount. To know possible problems with depositing checks through an ATM https://money.howstuffworks.com/personal-finance/online-banking/deposit-checks-through-atm1.htm

### Dataset:
----
* First Source: https://www.ecb.europa.eu/euro/banknotes/images/html/index.en.html

* Second Source: 
1. Training data: https://cocl.us/DL0320EN_TRAIN_TAR_KERAS
2. Validation data: https://cocl.us/DL0320EN_VALID_TAR_KERAS
3. Testing data: https://cocl.us/DL0320EN_TEST_TAR_KERAS

* The Dataset consist of two folders 
1. Banknotes ES1 Specimen 72dpi 
2. Banknotes ES2 Specimen 72dpi.

* We need to use banknotes ES1 Specimen 72dpi for tranining and Banknotes ES2 Specimen 72dpi for testing.
* Another thing to notice is that there are two format been provided one in GIF and other in JPEG hence we can use any one of it.
* Since the dataset is not much hence we can can create sepreate folder for each of the cash demonitaion.


### Data Visualization:
-----
![Cash Denomination](https://github.com/ShehzadaAlam/European-Cash-Denomination-Recognition/blob/master/Cash_Denomination.PNG)

### Model Architecture
-----
![Cash Denomination](https://github.com/ShehzadaAlam/European-Cash-Denomination-Recognition/blob/master/Currency%20Model.png)

### Deep Learning Model:
----

Model | Train Accuracy | Test Accuracy
----- | ----- | -----
VGG16 + Top Dense Layer | 96 % | 93 % 

----
<p>Thank You!	
<p><!-- Place this tag where you want the button to render. -->
<a class="github-button" href="https://github.com/ShehzadaAlam" aria-label="Follow @ShehzadaAlam on GitHub">Follow @ShehzadaAlam</a>
