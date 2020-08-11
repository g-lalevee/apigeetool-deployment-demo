# config.json format

```
{
    "KVM": [
        {
            "mapName": "KVM1",
            "encrypted": true,
            "environment": "Test",
            "api": ""
        }
    ],

    "KVMentry": [
        {
            "mapName": "KVM2",
            "entryName": "testy", 
            "entryValue":"yyy",
            "environment": "Prod",
            "api": "api2"
        }
    ],

    "Cache": [
        {
            "cacheName": "cache1",
            "environment": "test"
        }  
    ],  

    "TargetServer": [
        {
            "environment": "test",
            "targetServerName": "httpbin",
            "targetHost": "httpbin.org",
            "targetPort": 443,
            "targetSSL": true, 
            "targetEnabled": true             
        }  
    ],

    "Product": [
        {
            "productName": "test",
            "productDesc": "description",
            "environments": "test, prod",
            "scopes": "",
            "proxies": "Swagger-Petstore, GetMP",
            "quota": "1", //quota amount
            "quotaInterva": "1", //interval
            "quotaTimeUnit" "minute", //timeunit
        }
    ],

    "Developer": [
        {
            "attributes": "attr1, attr2",
            "callback": "",
            "email": "developer@example.com",
            "name": "AppName"
        }
    ],

    "Application": [
        {
            "apiProducts": "prod1, prod2",
            "callback": "",
            "email": "developer@example.com",
            "name": "AppName"
        }
    ],

    "ApplicationKey": [
        {
            "apiProducts": "prod1, prod2",
            "appName": "monapp",
            "developerId": "developer@example.com",
            "key": "xkey",
            "secret": "xsecret"
        }
    ]

}
```