<span class="wiki-builder">This page was generated with Wiki Builder. Do not change the format!</span>

## Info


* **URI:** [[/User/UpdateUser/|https://www.bungie.net/Platform/User/UpdateUser/]]
* **Basepath:** https://www.bungie.net/Platform
* **Method:** POST
* **Service:** [[User|Endpoints#User]]
* **Permissions:** None
* **Officially Supported:** No

## Parameters
### Path Parameters
None

### Query String Parameters
None

## Example
### Request
POST https://www.bungie.net/Platform/User/UpdateUser/
```javascript
{
    // Type: string
    "about": "",
    // Type: string
    "adultMode": "",
    // Type: string
    "displayName": "",
    // Type: string
    "emailAddress": "",
    // Type: string
    "emailUsage": "",
    // Type: string
    "locale": "",
    // Type: string
    "localeInheritDefault": "",
    // Type: string
    "profilePicture": "",
    // Type: string
    "profileTheme": "",
    // Type: string
    "showActivity": "",
    // Type: string
    "showFacebookPublic": "",
    // Type: string
    "showGamertagPublic": "",
    // Type: string
    "showGroupMessaging": "",
    // Type: string
    "showPsnPublic": "",
    // Type: string
    "uniqueName": "",
    // Type: object
}

```

### Response
PlatformErrorCode: 200
```javascript
{
    // Type: [#/components/schemas/User.UpdateUser]
    "Response": null,
    // Type: [[PlatformErrorCodes|Exceptions-PlatformErrorCodes]]:Enum
    "ErrorCode": 0,
    // Type: integer:int32
    "ThrottleSeconds": 0,
    // Type: string
    "ErrorStatus": "",
    // Type: string
    "Message": "",
    // Type: Dictionary&lt;string,string&gt;
    "MessageData": {
        "{string}": ""
    },
    // Type: object
}

```

## References
