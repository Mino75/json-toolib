# json-toolib
Json-toolib is a personal simple tools library stored in a single json file 
Notice : the json format can be converted into Bson for MongoDB Database

## Testing some requests
The data can be requested as a mongoDB bson data
Requests with the online tool here : https://mongoplayground.net

## Request Example

Query

```javascript

db.tools.find({
  "type": "browser",
  
})
```

Result

```javascript

[
  {
    "_id": ObjectId("5a934e000102030405000010"),
    "name": "Opera",
    "type": [
      "browser"
    ]
  },
  {
    "_id": ObjectId("5a934e00010203040500003e"),
    "name": "Firefox",
    "type": [
      "browser"
    ]
  },
  {
    "_id": ObjectId("5a934e000102030405000043"),
    "name": "Safari",
    "type": [
      "browser"
    ]
  },
  {
    "_id": ObjectId("5a934e000102030405000044"),
    "name": "Chromium",
    "type": [
      "browser"
    ]
  },
  {
    "_id": ObjectId("5a934e000102030405000045"),
    "name": "Tor",
    "type": [
      "browser"
    ]
  },

  {
    "_id": ObjectId("5a934e000102030405000046"),
    "name": "Chrome",
    "type": [
      "browser"
    ]
  }
]

  ```
  
  That's all :-)
  
