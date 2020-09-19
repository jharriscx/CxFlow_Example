# CxFlow_Example

Download the applicationscan.yml file to your C:\CxFlow directory and change the username and password parameters that say, <CHANGE ME> to be your cxscanner user name and password.

Then run CxFlow from the command line as such:

    java -jar cx-flow-1.6.8.jar --spring.config.location="./application-scan.yml" --scan --f=C:\Users\Administrator\...\JavaVulnerableLab --cx-project=JavaVulnerableLab --app=JavaVulnerableLab --forcescan
