# 🖥️  Testing Web Applications

I tested the Webstore ["Demoshopping.ru"](https://demoshopping.ru/) and prepared the documentation written in Russian Language to showcase my ability to work in the second languauge too. Please, take a look at the results of my work:
1. [Test plan](https://docs.google.com/spreadsheets/d/1o3obMZyl4Jc1viXWQFOAxKv5AI2XAGo5AFfvmCuNixU/edit?gid=0#gid=0) - a describtion of what and how to test (functions, types of testing, tools), main work stages, risks.
2. [Check list](https://docs.google.com/spreadsheets/d/1-YO5gSBaxfIakPl1U3Bl-hCXl2MueUJP5IuauvX2_Fo/edit?gid=0#gid=0) for testing the shopping cart and the payment module.
3. [Test cases](https://github.com/LSalakhova/web/blob/main/Test%20cases%20via%20QASE.pdf) via QASE for testing the shopping cart and the payment module.
4. [Test run results](https://github.com/LSalakhova/web/blob/main/Test%20run%20results%20QASE%20.pdf) via QASE.
5. [Bug Report example](https://github.com/LSalakhova/web/blob/main/Bug%20reports%20Web%20via%20Youtrack%20.xlsx) via Youtrack.

# 🫖  Replacing data with Charles Proxy

   I also tested the Webstore [Demoshopping.ru](https://demoshopping.ru/) using Charles Proxy.
   Check out the following videos where I change data using the proxy server for the Webstore on Google Chrome on MacBook Pro:

1. [Changing the number of items in the cart](https://drive.google.com/file/d/1zQObnQsXon5AHmtV-zgSyz4ajpHp7f-m/view?usp=sharing)

   Catching and modification of a request to change the quantity of items in te cart. The request sends 1 item to the cart and the response returns 500.

2. [Changing the response status from 200 to 403](https://drive.google.com/file/d/1MqaoHw6rL_Qqjv1d-pqMZ_y1ciUXLqCZ/view?usp=sharing)

    When accessing the Webstore server returns the status code 403 instead of 200. While, other websites work in normal mode and return the status code 200.
3. [Redirecting the request from Prod to QA](https://drive.google.com/file/d/1JUp1z8F5lKrrEsd7QlZz0RFMFEpx1Ul_/view?usp=sharing)

    Charles Proxy configuration to forward requests from Prod to QA environment.




