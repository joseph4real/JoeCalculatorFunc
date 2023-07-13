# JoeCalculatorFunc  
- Sign in to the Azure portal with your Azure account.
- In the search bar, enter Function App and Create.
- On the basic page adopt the below project details as specified in the following "Function App name-JoeCalculator.
- On the hosting page,Select Window OS and Consumption Plan (serverless hosting where you only pay when the app runs).
- Choose default settings for Networking, Monitoring, Deployment and Tag, then select review +create. After validation is passed cl create.
- When the deployment is complete, click go-to resource, app overview and Click function to view where your function app will be.

## Creating Function App Calculator  
- Open visual studio, create a new project, select Azure function, and give your project a name.
- Select.NET 6, choose HTTP trigger, to call an Azure-Function-App that sums the value of x and y and inputs a result.
- Edit your code in the visual studio environment by replacing the class "function1" and function attribute with the "Sum'.
  delete lines 22 to 30 and replace them with the one below.
- int x=int.Parse(req.Query("x"]);
- int y =int.Parse(req.Queryl"y"]);
- int result=x ult=x+y;
- return new OkobjectResult(result);
- Make sure Build the code is successfully built.

## Deploying from VS code to Azure  
- Right-dlick. JoecalculatorFunc and click publish,then select Azure,and click next.
- Select Azure function app (windows) and click next.
- Login to your Azure account.
- Expanding the "josephRG" and select your function app (loeCaculator) and click finish.
- A ready-to-be-publish window will come up, click publish on the right side. After that, a publish succeeded window will come up (publishing complete).
- Goto Azure portal to see if you app was successfully published under function button.

## Testing the App by doing some Calculation  
- Click on the Function App "Sum" and click the "Get Function URL" to copy the App URL.
- Paste the URL into browser, give "x" and "y" values as shown in the capture and click enter.
- After the" two equals to sign", add (&=x=2(&=x=230&y=890)y=890) and press enter.

## Pushing Function App Files to GitHub from Visual Studio  
- Click on git changes by the right bottom side of the VS screen.
- Select create git Repository.
- The create a Git repo window will appear, enter your repo name and description, uncheck private, and click create and Push.
- After you have succeeded in pushing, the visual studio right side screen will appear to show a new repository has been created.
- Go to your Github account to confirm if you have successfully created and push your files. 




