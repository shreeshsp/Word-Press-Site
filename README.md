# Word-Press-Site
Fault Tolerant Word Press Site
WordPress, an open-source blogging tool and content management system (CMS) based on PHP and MySQL. Users will connect in over the internet to Route53/CloudFront to access WordPress site and requests will hit the Elastic Load Balancer. The EC2 instances and RDS instances are configured in two separate security groups. The two EC2 instances are behind an auto scaling group and RDS instances are Multi-AZ enabled. EC2 instances will use Amazon S3 for storage of all files, all the WordPress code and the media assets are stored in Amazon S3.
