# public-keys
Public keys that are used to provide access to VMs


### Generating Public Keys
Example :
```
ssh-keygen -t rsa -C "your_email@gmail.com"
```

## Workflow
* Please add your public keys, one per line

* Once added, please regenerate the sha512 file too using the following command
```
sha512sum authorized_keys > authorized_keys.sha512
```
or
```
shasum -a 512 authorized_keys > authorized_keys.sha512
```

* Create a pull request

It takes a maximum of 30 minutes at the moment once the PR is merged before you get access to the VMs.
