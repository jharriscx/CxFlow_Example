# CxFlow_Example

1. Download the [application-scan.yml](https://github.com/jharriscx/CxFlow_Example/blob/master/application-scan.yml) file to your **C:\CxFlow** directory.
2. Edit the .yml file and change the username and password parameters that say, **\<CHANGE ME\>** to be your cxscanner username and password.

Then run CxFlow from the command line as such:

    cd C:\CxFlow
    
    java -jar cx-flow-1.6.8.jar --spring.config.location="./application-scan.yml" --scan --f=C:\Users\Administrator\...\JavaVulnerableLab --cx-project=JavaVulnerableLab --app=JavaVulnerableLab --forcescan
