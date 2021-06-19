How to run aws cloudformation cli to create a basic webserver.

> Note: Make sure to access the url without https. It will not load on https.

```bash
aws cloudformation create-stack --stack-name <DemoStack> \
    --region <aws-region> \
    --template-body file://<FILE>.json or .yaml \
    --parameters file://<FILE>.json
```