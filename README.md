# Signin with KYC.Crypto

## Sign Button Partner Flow
1. Any KYC.Crypto verified user who wants to integrate **Signin with KYC.Crypto** button on their website will have to simply create their first app on a signin button partner dashboard.

2. While creating an app, partner will have to provide following details: Application Name, Website URL, Redirect URIs

3. Upon successfull app creation, partner will receive client ID and Client Secret.

4. Partner will also be provided with a url to implement on their website to perform signin with kyc.crypto button


- **Partner can create maximum 5 applications per each kyc verified account**
- **Partner can also update their app details too such as Application Name, Website URL and Redirect URIs**

## User Signin Flow

1. User will be redirected to kyc.crypto signin screen after clicking kyc.crypto signin button on partner's website.

2. User will have to enter their registered email address that is kyc verified on KYC.Crypto platform.

3. After entering email, user will receive an OTP for verification. User will receive an OTP only if that user is kyc verified on KYC.Crypto platform.

4. When user is successfully do signin and grant access to particular partner app, we provide client a JWT token to use to get basic details of a signed in user. Which will be valid for 24 hours

- **Partner will have to use the provided token from their backend side. API call to get user detail will require a client secret to be matched. Client secret is a sensitive credentials that must not be used in browser side.**