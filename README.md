# joshuacruz.me

[joshuacruz.me](https://joshuacruz.me) is a slightly more detailed version of my resume hosted on S3.

## Technology Utilized

- Namecheap
- HTML/CSS
- AWS
    - S3
    - CloudFront
    - Route 53
    - ACM

HTML and CSS were used to design and style the layout of the website. Content is distributed through AWS CloudFront over HTTPS using AWS ACM. Because the domain was purchased on Namecheap, AWS Route 53 is configured to point the domain name to the CloudFront Distribution hosting the static website.
