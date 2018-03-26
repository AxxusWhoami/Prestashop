
## Configuration

### Enable the Module 
Configuration of you module is available in administration interface Modules & Services >> Splash 

![](https://raw.githubusercontent.com/wiki/SplashSync/Prestashop/img/screenshot_1.png)


### Connect to your Splash Account

First, you need to create access keys for you module in our website. To do so, on Splash workspace, go to **Servers** >> **Add a Server** and note your id & encryption keys. 

![](https://raw.githubusercontent.com/wiki/SplashSync/Prestashop/img/screenshot_2.png)

Then, enter the keys on Module's configuration (take care not to forget any character). 

![](https://raw.githubusercontent.com/wiki/SplashSync/Prestashop/img/screenshot_3.png)

### Setup default Parameters

To work correctly, this module need few parameters to be selected. These defaults values will be used upon objects creation/modification.

![](https://raw.githubusercontent.com/wiki/SplashSync/Prestashop/img/screenshot_4.png)

##### Default Language
Select which language package module should use for communication with Splash Server.

##### Default User
Select which user will be used for all actions executed by Splash Module. 
We highly recommend creation of a dedicated user for Splash. 
Be aware Splash Module will take care of Users rights policy, this user must have appropriated right on Prestashop.

### Check results of Self-Tests

Each time you update your configuration, module will verify your parameters and ensure communication with Splash is working fine. 
Ensure all tests are passed... this is critical!

![](https://raw.githubusercontent.com/wiki/SplashSync/Prestashop/img/screenshot_5.png)