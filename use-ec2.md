How to Connect via SSH to Pecos EC2 Instance

```
eval `ssh-agent -s`

ssh-add document-upload.pem

ssh -i "document-upload.pem" ec2-user@ec2-13-58-226-223.us-east-2.compute.amazonaws.com
```