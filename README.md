
# Overview of different App security topics 

- Application authentication OIDC, OAuth2, logout, flows
- Application authorization claims, roles, groups, policies
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
- certificate authentication

# Examples identity provider clients:

## OIDC clients

OpenIddict with Razor Pages, Blazor WASM BFF and Angular OpenID Connect Code Flow with PKCE clients and ASP.NET Core APIs

https://github.com/damienbod/AspNetCoreOpeniddict

Differrent ASP.NET Core applications using OpenID Connect Hybrid flow Code Flow, Code Flow with PKCE, JWT APIs, Device Code flow. Force ASP.NET Core OpenID Connect client to require MFA. Send MFA signin requirement to OpenID Connect server using ASP.NET Core Identity and IdentityServer4. Requiring MFA for Admin Pages in an ASP.NET Core Identity application. Require user password verification with ASP.NET Core Identity to access Razor Page

https://github.com/damienbod/AspNetCoreHybridFlowWithApi

Auth0 with Angular and an ASP.NET Core API

https://github.com/damienbod/Auth0AngularAspNetCoreApi

Securing Blazor Web assembly using Cookies and Auth0, securing multiple Auth0 APIs in ASP.NET Core using OAuth Bearer tokens, securing OAuth Bearer tokens from multiple Identity Providers in an ASP.NET Core API

https://github.com/damienbod/SeparatingApisPerSecurityLevel

Securing an ASP.NET Core API which uses multiple access tokens, securing a Web API using multiple token servers

https://github.com/damienbod/ApiJwtWithTwoSts

## Azure AD, Azure AD B2C clients, Continuous Access

https://github.com/Azure-Samples/active-directory-aspnetcore-webapp-openidconnect-v2/

https://github.com/damienbod/AzureADAuthRazorUiServiceApiCertificate

https://github.com/damienbod/AzureAD-Auth-MyUI-with-MyAPI

https://github.com/damienbod/AspNetCoreAzureADCAE

https://github.com/damienbod/azureb2c-fed-azuread

https://github.com/damienbod/PwaBlazorBffAzureB2C

https://github.com/damienbod/AspNetCoreB2cExtraClaims

# Links:

## Docs

https://docs.microsoft.com/en-us/aspnet/core/security/

https://openid.net/connect/

https://oauth.net/2/

## GRPC

https://docs.microsoft.com/en-us/aspnet/core/grpc/authn-and-authz

## Microsoft Graph

https://github.com/damienbod/AspNetCoreBlazorMicrosoftGraph

https://github.com/damienbod/TeamsAdminUI

## Data Encryption, Certificates, Identity

https://github.com/damienbod/SendingEncryptedData

https://github.com/damienbod/AspNetCoreCertificates

## FIDO2

https://github.com/passwordless-lib/fido2-net-lib

https://github.com/damienbod/AspNetCoreIdentityFido2Mfa

## Microsoft.Identity.Web

https://github.com/AzureAD/microsoft-identity-web

## OpenIddict

https://github.com/openiddict/openiddict-core

## Keycloak

https://www.keycloak.org/

## DuendeSoftware

https://github.com/DuendeSoftware

## Blazor BFF

https://github.com/damienbod/Blazor.BFF.OpenIDConnect.Template

https://github.com/damienbod/Blazor.BFF.AzureAD.Template

https://github.com/damienbod/Blazor.BFF.AzureB2C.Template

https://github.com/DuendeSoftware/BFF

## Session protection

https://github.com/andrewlock/NetEscapades.AspNetCore.SecurityHeaders

## Self soverign identity (SSI), Azure VC

https://docs.microsoft.com/en-us/azure/active-directory/verifiable-credentials/verifiable-credentials-configure-tenant

https://github.com/Azure-Samples/active-directory-verifiable-credentials-dotnet

https://github.com/swiss-ssi-group
