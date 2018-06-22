## IPFS文件上传接口文档##


#### 接口说明 **1、**文件上传

- **请求URL**
> [localhost:3000/upload](#)

- **请求方式** 
>**POST**

- **请求头**
>**multipart/form-data; boundary=----WebKitFormBoundary7MA4YWxkTrZu0gW**

- **请求参数**
>
 | 请求参数      |     参数类型 |   参数说明   |
| :-------- | :--------| :------ |
| name|  <mark>String,**固定为：file**</mark>|  |

- **返回参数**
> | 返回参数      |     参数类型 |   参数说明   |
| :-------- | :--------| :------ |
| status|   Integer|  200|
| data|   String|  存储地址|

- **返回示例**
>    
```java 
  {
  "status": 200,
  "data": "http;//localhost:8080/ipfs/QmNoCkYszwjY9bukSQf8pckCFUabKiJ6j3GEHaGLzMrGKi"
  }
