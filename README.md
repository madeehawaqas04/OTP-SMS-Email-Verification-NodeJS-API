# OTP-SMSVerification-NodeJSAPI
MongoDB, Nodejs, Expressjs, twilio, otp-generator


1- SendOTP API

API URL= http://localhost:8800/api/auth/sendOTP

Body
{
    "phoneNumber":"+923337102659"
}

2- verifyOTP

API URL=http://localhost:8800/api/auth/verifyOTP

{
    "phoneNumber":"+923337102659",
    "otp":"z1xj20"
}