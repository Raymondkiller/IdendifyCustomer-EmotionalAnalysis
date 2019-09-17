readme file

use API:
1. to recognize face in image:
- publish to MQTT in topic: "APIGetPost"
- data type json: {"source":"MainApp","func":"recognize","data":{"ID":"","base64image":""}}
* ID is name ID you want
* base64image is link to path of image, ex: "/home/pi/maychamcong/MainApp/image/image.jpg"
2. to register user:
- publish to MQTT in topic: "APIGetPost"
- data type json: {"source":"MainApp","func":"register","data":{"username":"","ID":"","base64video":""}}
* "username" is user name you want
* "ID" is name ID you want
* base64video is link to path of image, ex: "/home/pi/maychamcong/MainApp/video/video.webm"
