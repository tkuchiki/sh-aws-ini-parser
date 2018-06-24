# sh-aws-ini-parser
AWS credentials / config file parser in sh.

# Usage

```console
# parse ~/.aws/credentials and ~/.aws/config
# use default profile
$ ./aws-ini-parser
aws_access_key_id=AKIAIOSFODNN7EXAMPLE1
aws_secret_access_key=wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY1
output=json
region=us-east-1
```

```console
# parse ~/.aws/credentials and ~/.aws/config
# use user2 profile
$ profile=user2 ./aws-ini-parser
aws_access_key_id=AKIAIOSFODNN7EXAMPLE2
aws_secret_access_key=wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY2
output=json
region=us-east-1
```

```console
# parse /tmp/aws_credentials and /tmp/aws_config
# use default profile
$ credentials_file=/tmp/aws_credentials config_file=/tmp/aws_config ./aws-ini-parser
aws_access_key_id=AKIAIOSFODNN7EXAMPLE3
aws_secret_access_key=wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY3
output=json
region=us-east-1
```
