# Class Master
[baseUrl : class_masater]

## To retreive all records of class master.

> Method : GET  
Endpoint : /all



### Incoming Parameters


| Name        | Data Type |
| ------------- |:-------------:|
| id     | ObjectID |
| standard      | String      |
| division | String      |    



::: tip
Example   
`http://<yourdomain>/class_master/all`
:::


## To create a record of class master.

> Method : POST  
Endpoint : /create



### Parameters


| Name        | Data Type |
| ------------- |:-------------:|
| standard      | String      |
| division | String      |    



::: tip
Example   
`http://<yourdomain>/class_master/create`

Request Body
```
{  
    standard:'I',  
    division:'A'
}
:::
