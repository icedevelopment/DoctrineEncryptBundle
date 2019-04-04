#Configuration Reference

All available configuration options are listed below with their default values.

``` yaml
vmelnik_doctrine_encrypt:  
# Secret key for encrypt algorithm. All secret key checks are encryptor tasks only.
    secret_key:           ~ # Required
#  You must use your own Encryptor. Encryptor must implements EncryptorInterface interface
    encryptor_class:      ~ 
#  You can optionally provide a service as an encryptor instead of specifying a class.  The service 
#  must implement EncryptorInterface.  You do not need to provide encryptor_class if you provide the service.
    encryptor_service:    ~
#  Now it's only one db driver is supported - orm
    db_driver:            orm 
```
