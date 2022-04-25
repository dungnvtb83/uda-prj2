- Git: https://github.com/dungnvtb83/uda-prj2.git
- Elastic Beantalk URL: http://uda-prj2-dev.us-east-1.elasticbeanstalk.com
- Request: http://uda-prj2-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://i1.wp.com/s1.wp.com/wp-content/themes/h4/landing/marketing/pages/hp-2022-free-pro/media/desktop/desktop-website-v2-2x.jpg

{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "PublicReadGetObject",
            "Effect": "Allow",
            "Principal": "*",
            "Action": [
                "s3:GetObject"
            ],
            "Resource": [
                "arn:aws:s3:::Bucket-Name/*"
            ]
        }
    ]
}