# AWS-Cloud-Security
AWS Config takes care of audit, evaluation and assessment of the resources in your AWS Account.
## AWS Config:
- Retrives current and historical configurations of the account
- Evaluated the configurations of your AWS resources for the desired setting and send notifications when a resource is created,modified and deleted.
- Shows the relationships betweer your AWS account.
## Architecture 
![AWS Config (1)](https://user-images.githubusercontent.com/57444486/202353920-9ce86c63-bdeb-4233-aa63-f53fe378238b.png)
## Config Rules
AWS Config checks the configuration of your resources against the rules you define.
For each rule ,there is a compliant status indicating if the resource is compliant or non-compliant.
## Advanced Query
It is AWS Config feature enables one to dynamically query the resources that are being monitored in the account.
A Lambda Function can run advanced queries that are more complex and push the results to a dashboard 
## AWS Config Aggregators
For the entrprises having multiple accounts,
When there is need to apply these rules to each organizational Unit, at a centralized point to ensure consistency accross all accounts.
This is done at the organizational level,and the rsults potrayed in one dashboard showing which resources are compliant and non-compliant.
## Architecture 
![AWS Aggregator_](https://user-images.githubusercontent.com/57444486/202378916-986bd0b5-9cbe-4eff-a3f1-d37558ae4291.jpeg)
