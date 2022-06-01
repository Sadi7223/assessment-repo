# Website URl:
https://s3.ap-southeast-2.amazonaws.com/web-demo.com/index.html

# Instructions to set up the site for ourselves:
To setup the site on your end follow the following steps mentioned below:
- create S3 bucket
- select the region
- enable/disable the public access
- Create the bucket object
- create the index.html page in bucket (Name of page must be same as of local page)
- Upload the index.html page from local directory to the object which you created earlier in S3.
- enable the static web hosting of the object (you can find this in the properties)
- Set the bucket policy if you want any. (go to permissions and you will find the policy section there)

# What else you would do with your website, and how you would go about doing it if you had more time?
If i would have some more time i would love to create my resume in blog website, using HTML, CSS and java script for some visual effects.

# Alternative solutions that you could have taken but didn't and explain why?
This was the basic assessment so i was stuck with the tasks as per mentioned. As i have created the static website in S3 bucket, i would have implemented this bucket with route53 as well for readable DNS. Secondly if this was a big project i will enable the bucket versioning aswell for the record purpose.

# What additionally would be required to make this a production grade website that would be developed on by various development teams. The more detail, the better!
To make this website a production grade website, this website should have a production idea which need to be implemented in it forexample business website, e-commerce website. If the website is of ecommerce then it  can be easily monitored and managed by using the aws services and the risk factor will also be very low.
