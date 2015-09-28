# test-awsm-users

```
npm install jaws-framework -g
jaws new project
cd test-awsm-users
jaws module install https://github.com/jaws-framework/jaws-core-js
jaws module install https://github.com/dekz/awsm-users
jaws deploy resources
jaws dash
```

```
./create-user

HTTP/1.1 403 Forbidden
Content-Type: application/json
Content-Length: 42
Connection: keep-alive
Date: Mon, 28 Sep 2015 01:20:07 GMT
x-amzn-ErrorType: MissingAuthenticationTokenException:http://internal.amazon.com/coral/com.amazon.coral.service/
x-amzn-RequestId: 0db69701-657f-11e5-8100-7750da63aac3
X-Cache: Error from cloudfront
Via: 1.1 3ccccbb11cd13ec9757e157d25a18093.cloudfront.net (CloudFront)
X-Amz-Cf-Id: pEdS3aaiZ-PoYmdcr4VwOTAAtFM_8SqNk6B6s-c3VVUxK65hrCOjZg==

{"message":"Missing Authentication Token"}
```
