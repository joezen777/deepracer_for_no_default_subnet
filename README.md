# deepracer_for_no_default_subnet
Use this Python Notebook if you no longer have a default VPC in us-east-1 and us-west-2 but still want to play around with DeepRacer in SageMaker.

# First copy SageMaker Example

Copy over in SageMaker Examples under Reinforcement Learning the rl_deepracer_coach_robomaker.ipynb

Then replace the notebook with the contents of this notebook file.

# Update vpcName and subnetPrefix variables

Update the vpcName variable in the notebook to your matching VPC name. 

Update the subnetPrefix variable to one that matches your public subnets. You must have at least two public subnets in AZ's A,B or C.
