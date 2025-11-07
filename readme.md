CLOUD_NAME=<CLOUDINARY_NAME>
CLOUD_API_KEY=<YOUR_CLOUDINARY_API_KEY>
CLOUD_SECRET=<YOUR_CLOUDINARY_API_SECRET>
BACKEND_URL=<YOUR_BACKEND_URL>
# Server Configuration
PORT=<YOUR_PORT_NUMBER>

# Authentication
SECRET_KEY=<YOUR_SECRET_KEY>

# MongoDB Connection String - PASTE DI SINI! 👇
MONGODB_URI=<YOUR_MONGODB_CONNECTION_STRING>

# MongoDB Database Sample - web data
```javascript
{
    "_id":{
    "$oid":"690d79ab277bd6100c2fcdbb"
    },
    "pesertaPaket":{
        "siswaPAUD":{"$numberInt":"17"},
        "paketA":{"$numberInt":"38"},
        "paketB":{"$numberInt":"95"},
        "paketC":{"$numberInt":"101"}
        },
    "images":[
        {
            "imageId":"adf82313-8f75-4760-8708-11699e29aabe",
            "imageAlt":"IMAGE01","imageUrl":"https://res.cloudinary.com/dwkpscs0j/image/upload/v1762535067/folder_name/file_azlhhk.gif",
            "createdAt":{
                "$date":{
                    "$numberLong":"1762535067982"
                    }
                },
                "updatedAt":{
                    "$date":{
                        "$numberLong":"1762535067982"
                        }
                    },
                "cloudinaryId":"folder_name/file_azlhhk"
            }
        ]
}

```
# MongoDB Database Sample - user
```javascript
{
    "_id":{
    "$oid":"690d67908729fb77f04fa708"
    },
    "username":"admin",
    "password":"hashed_password"
}

```