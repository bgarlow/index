# Index
Index of my repositories, including code projects and notes (with README only).
## General Notes
## How-To's

| Description                           | Repo   |
| :--------- | :-------| 
| __MFA-Only with Okta Verify Push__: Documents the user creation, MFA factor enrollment, and related flows for an MFA-only use case for Okta Verify with Push. All API calls are documented, and a Postman Collection is provided. | [mfaonly_oktqverifypush](https://github.com/bgarlow/mfaonly_oktaverifypush) |
 __Okta Transaction State, Authentication and MFA__: Documents the user creation, MFA factor enrollment, and related flow in the context of the Okta Transaction State model. Useful for starting a small POC. All API calls are documented, and a Postman Collection is provided. | [okta_authentication_mfa_flow](https://github.com/bgarlow/okta_authentication_mfa_flow) |

## Code Projects 

| Description                           | Repo   |
| :--------- | :------- |
| Mock API resource endpoint for debugging/demoing OAuth with AWS API Gateway. Designed to work with [sample_lambda_authorizer](https://github.com/bgarlow/sample_lambda_authorizer) | [mock_api_lambda](https://github.com/bgarlow/mock_api_lambda)| 
| Sample OAuth Lambda Authorizer for demo/debugging that validates the JWT and returns additional debugging info to the backend API via the policy document object. Designed to work with [mock_api_lambda](https://github.com/bgarlow/mock_api_lambda)            | [sample_lambda_authorizer](https://github.com/bgarlow/sample_lambda_authorizer)|
|__OktaCar Demo__: Demo application showcasing Okta API Access Management securing APIs on various API Gatways using OAuth 2.0. Node.JS Express with Angular 5. This is an internal Okta demo only. Contact me for access.| [oktacar](https://github.com/bgarlow/oktacar)|
|__Apigee API Gateway for OktaCar__: Configuration instructions and XML for an Apigee Gateway proxy that can be used with the OktaCar demo. This is an Okta internal demo repo only. It is not required for OktaCar, but is an effective way to demonstrate Okta API Access Management working with the Apigee API Gateway. | [oktacarapigee](https://github.com/bgarlow/oktacarapigee) |
|__OAuth/OIDC Toolkit__: Demo app/toolkit that is useful for demonstrating various OpenID Connect/OAuth 2.0 concepts with Okta. Pulls all of the Authorization Server and OAuth client info from an Okta org, and allows the user to initiate authentication with any app/auth server combo using the Okta Sign-In Widget, Authorization API, or redirect to Okta (including Authorization Code Flow with PKCE). Examine the contents of tokens, view and revoke tokens, introspect, etc. Live-edit Okta Sign-In Widget configuration, edit OAuth clients via API. | [oauthToolkit](https://github.com/bgarlow/oauthToolkit) |