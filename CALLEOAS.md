## CALLEOAS API Contract

### 1. Categories
**End Point** : api/datasetdetails/categories

**Sample Request**
``` json
{
    "patientId" : 1001,
    "userId" : 201
    "workEntity" : 12  
}

```

**Sample Response:**
``` json
   [
    {         
          "category": "IDC10",
          "code": 93231
    },
    {          
         "category" : "INPATIENT",
         "code" : 91566
    }
 ]

```

### 2. Data Set By Category
**End Point** : api/datasetdetails/datasetbycategory

**Sample Request**
``` js
{
    "code" : 101,
    "patientId" : 1001,
    "userId" : 12,
    "workEntity" : 320
}

```

**Sample Response**
``` js
[
   {
          Dataset: "Asthama",
          CheckListType: "LSPSET25",
          KeyType : “E”,
          Active: "Y"
    },
   {                   
          Dataset: "Falls",
          CheckListType: "LSPSET26",
          KeyType : “E”,
          Active: "Y"
    }
]
```
