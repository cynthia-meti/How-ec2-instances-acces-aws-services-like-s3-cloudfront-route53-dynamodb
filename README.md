# How-ec2-instances-acces-aws-services-like-s3-cloudfront-route53-dynamodb
This project is to demonstrate how an onprem company uses ec2 instance to access s3 bucket, cloud front route53 and dynamodb 
i creat a vpc where the aws services will be placed
![vpc created](https://github.com/cynthia-meti/How-ec2-instances-acces-aws-services-like-s3-cloudfront-route53-dynamodb/assets/132440521/d9e3348f-bc37-40b3-9c52-5415862ed05a)
4 subnet have been created 2 public and 2private
![created subnet](https://github.com/cynthia-meti/How-ec2-instances-acces-aws-services-like-s3-cloudfront-route53-dynamodb/assets/132440521/fd358df7-69c7-4469-b6ec-f7bd92cb4890)
create instance
![we have our instances](https://github.com/cynthia-meti/How-ec2-instances-acces-aws-services-like-s3-cloudfront-route53-dynamodb/assets/132440521/49d4b305-4383-490a-ba3a-cb8aa6a7fe08)
here i have allocated the elastic IP address to the vpc and associated it wih intance . this is done to enable route 53 to have access to the ec2 instances.
![elastic ip address have been allocated to subnet](https://github.com/cynthia-meti/How-ec2-instances-acces-aws-services-like-s3-cloudfront-route53-dynamodb/assets/132440521/b713cea2-f5c9-41c6-9d59-db52f73d7469)
inorder for us to have a route 53 domain name,,a hosted zone and records is required. below i successfully hosted azone and created record.
![hosted zone created](https://github.com/cynthia-meti/How-ec2-instances-acces-aws-services-like-s3-cloudfront-route53-dynamodb/assets/132440521/99518dec-f665-43f7-98b6-9610694fdb67)
![record created](https://github.com/cynthia-meti/How-ec2-instances-acces-aws-services-like-s3-cloudfront-route53-dynamodb/assets/132440521/3234553c-acc0-407c-8dbc-008ee1edfe54)
![record 2 created](https://github.com/cynthia-meti/How-ec2-instances-acces-aws-services-like-s3-cloudfront-route53-dynamodb/assets/132440521/f1bca699-b5e0-4a47-a35e-6cedba4c708b)
domain name created.
![here we have the domain names](https://github.com/cynthia-meti/How-ec2-instances-acces-aws-services-like-s3-cloudfront-route53-dynamodb/assets/132440521/3803b30c-fcc9-4499-b986-4b29eeb4d2e5)
