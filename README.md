This workshop builds on top of the [Sagemaker Examples](https://github.com/awslabs/amazon-sagemaker-examples) to show you how, using AWS, you can parallelize the training of your reinforcment learning algorithms to get insanely fast turn around times & results for your reinforcement learning experiments.

# Instructions


## Step 0 - Cloud Formation Installation

Click below to deploy your SageMaker RL stack:

&nbsp;

[![Launch Stack into us-east-1 with CloudFormation](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/images/cloudformation-launch-stack-button.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=SageMakerRLLabSummitSydney2019&templateURL=https://s3-ap-southeast-2.amazonaws.com/aws-summit-2019-rl/AWS-summit_RL-CloudFormation.yml)

&nbsp;

## Step 1 - Login to Sagemaker
&nbsp;
![aws console](images/awsconsole2.png)

&nbsp;

1. Login to AWS Console
2. Click "Find Services"
3. Type "SageMaker" and hit enter




## Step 2 - open our Notebook instance

&nbsp;


1. On the left menu under the "Notebook" section, click "Notebook instances"

&nbsp;
&nbsp;

![menu](images/awssagemakerhome.png)
&nbsp;
2. Next to our instance named "amazon-RL-lab" there is a link called "open jupyter", click it.

&nbsp;
&nbsp;

![menu](images/openjupyter.png)

&nbsp;
3. A new tab will launch taking you to a jupyter notebook. Once this has finished loading, click the link titled "Summit-RL"
4. Clicking the link will take you to a new directory. Click the file titled **"Sagemaker_RL_Lab_Summit_2019_One_Click.ipynb"** to get started with the lab!
