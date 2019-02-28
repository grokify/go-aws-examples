# Alexa for Business - Create Contact Example

## Credentials

To use this demo, add the following to your `~/.aws/credentials` file:

```
aws_access_key_id = AKID
aws_secret_access_key = SECRET
aws_session_token = TOKEN_OPTIONAL
region = us-east-1
```

The role must have the `AlexaForBusinessFullAccess` permissions.


`aws_session_token` is optional.

More info here: https://docs.aws.amazon.com/sdk-for-go/api/aws/session/

To generate your Access key ID and Secret access key, follow the instructions here for creating programmatic access credentials for your IAM user:

https://aws.amazon.com/blogs/security/wheres-my-secret-access-key/

## List Contacts

To List Contacts, use the Search Contacts API with an empty search string.
