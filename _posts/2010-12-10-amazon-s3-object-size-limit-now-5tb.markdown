---
layout: post
title: 'Amazon S3 Object Size Limit Now 5TB'
---
<img src="http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg" alt="" width="250" align="right" />Amazon Web Services increased the <a href="http://aws.typepad.com/aws/2010/12/amazon-s3-object-size-limit.html" target="_blank">size limit for objects you can store on Amazon S3 from 1TB to 5TB</a> today.<p></p>
In order to upload larger objects they require you to use the new <a href="http://aws.typepad.com/aws/2010/11/amazon-s3-multipart-upload.html" target="_blank">Multipart Upload API</a>. This uploader allows you to upload the object in parts, increasing the chances it will finisih.<p></p>
I don't personally have any 1 TB files laying around, let alone a 5TB files, but I'm sure this opens up a lot of new possibilities for using Amazon Web Service for scientific data or media content.