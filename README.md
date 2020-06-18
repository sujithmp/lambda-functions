# lambda-functions

Lambda function testing
---------------

With the help of vscode it has been very easy to test  lambda function locally. We can run lambda function as it will in the server.

First of all we need to install docker and sam cli at the least. If your functionality or feature need aws s3 bucket access then it's better to install aws cli. Here in my case s3 put object event is used to trigger the lambda function. 

Once you are ready open the vscode, install the aws sdk package. You can install packages required for your project  by just clicking on the extension button in the left side panel of the vscode IDE. This is how vscode make things easier.

Once you have installed the aws-sdk tool kit, it will be available in the left tool box panel. Open the aws command pallette using the combination of  Ctrl+Shift  P in your keyboard. These keys combination will work in windows systems, here I am using Windows 10, or alternatively you can connect to aws using `connect to aws` option from the drop down menu appearing when you click on the three dots in the left top corner of the aws tool panel. 

The connect to option will guide you to create an aws profile. In this process you will be entering the aws access key id and secret key id. And you will be giving a name for this profile.



