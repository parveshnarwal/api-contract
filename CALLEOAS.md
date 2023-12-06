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

**Response:**
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

### 2. DataSetByCategory
**End Point** : api/datasetdetails/datasetbycategory

**Sample Request**
``` json
{
    "code" : 101,
    "patientId" : 1001,
    "userId" : 12,
    "workEntity" : 320
}

```
