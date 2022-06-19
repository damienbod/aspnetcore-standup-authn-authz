
# Overview of different App security topics 

- Application authentication OIDC, OAuth2, logout, flows
- Application authorization arch. claims, roles, groups 
- Self sovereign identity, verifiable credentials, wallets, distributed authentication
- FIDO2, MFA, 2FA, Authenticators, not SMS 
- DevOps security
- OWASP themes, session hardening
- Identity management in applications, Key management, certificates

# Authentication Flows

- OpenID Connect Code flow + PKCE with client secret 
- OpenID Connect Hybrid flow
- OpenID Connect Code flow + PKCE with no secret
- OAuth Device Flow
- On Behalf Of (OBO) Flow
- OAuth2 Resource Owner Credentials Flow
- Azure Managed Identities
- certicate authentication

# Examples:

## OIDC clients

https://github.com/damienbod/AspNetCoreOpeniddict

https://github.com/damienbod/AspNetCoreHybridFlowWithApi

## Azure AD

https://github.com/damienbod/AzureADAuthRazorUiServiceApiCertificate

## Azure AD B2C clients

https://github.com/damienbod/azureb2c-fed-azuread

https://github.com/damienbod/PwaBlazorBffAzureB2C

## Microsoft Graph

https://github.com/damienbod/AspNetCoreBlazorMicrosoftGraph

## Data Encryption, Certificates

https://github.com/damienbod/SendingEncryptedData

https://github.com/damienbod/AspNetCoreCertificates

# Links:

https://docs.microsoft.com/en-us/aspnet/core/security/

https://openid.net/connect/

## FIDO2

https://github.com/passwordless-lib/fido2-net-lib

https://github.com/damienbod/AspNetCoreIdentityFido2Mfa

## Microsoft.Identity.Web

https://github.com/AzureAD/microsoft-identity-web

## OpenIddict

https://github.com/openiddict/openiddict-core

## Keycloak

https://www.keycloak.org/

## Blazor BFF

https://github.com/damienbod/Blazor.BFF.OpenIDConnect.Template

https://github.com/damienbod/Blazor.BFF.AzureAD.Template

https://github.com/damienbod/Blazor.BFF.AzureB2C.Template

https://github.com/DuendeSoftware/BFF

## Session

https://github.com/andrewlock/NetEscapades.AspNetCore.SecurityHeaders

## Azure VC

https://docs.microsoft.com/en-us/azure/active-directory/verifiable-credentials/verifiable-credentials-configure-tenant

https://github.com/Azure-Samples/active-directory-verifiable-credentials-dotnet
