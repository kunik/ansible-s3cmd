# Ansible Role: s3cmd

Install s3cmd and creates basic configuration.

## Requirements

None

## Role Variables

All variables sit under ```s3cmd``` key:

```
s3cmd:
  key: 'aws-key'
  secret: 'aws-secret'
  user: 'root'
```

    key: 'aws-key'

Your public IAM key.

    secret: 'aws-secret'

Your secret IAM key. Do not leave these in plain text. Use Ansible Vault or another key storage mechanism.

    user: 'root'

User to place the ```.s3cfg``` under. Defaults to the root user.

## Dependencies

None

## License

BSD
