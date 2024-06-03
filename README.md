
# Kryptonite App API Documentation

## Base URL

All API requests should be made to the following base URL:

`https://kryptonite-app.onrender.com`

## Authentication

Authentication is required for all API requests. You'll need to include an API key in the headers of your requests.

## Endpoints

### For users endpoints

#### Send OTP for user registration
POST ` /api/user/send-otp `
| key | value | 
| -------- | -------- |
| email    | your email here     |

#### user registration
POST ` /api/user/register-user `
| key | value | 
| -------- | -------- |
| email    | your email here     |
| otp    | the otp generated here    |


#### user Login OTP
POST ` /api/user/send-passcode `
| key | value | 
| -------- | -------- |
| email    | your email here     |


#### user Login 
POST ` api/user/login `

| key | value | 
| -------- | -------- |
| email    | your email here     |
| otp    | the otp generated here    |


### For file 
### To generate API key
 POST ` /api/v1/file/generate-apikey ` 

### for image upload
 POST ` /api/v1/file/upload  ` 

### To get single image 
 POST ` /api/v1/file/:id ` 

### To get all user image file
 GET ` /api/v1/file ` 

### To delete an image 
 DELETE ` /api/v1/file/:id ` 


