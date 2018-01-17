# Integrate your service with SSO

## Prerequisites
To integrate your service into Up2U you need your service to be able to use SAML2 as authentication protocol. Further protocols like oAuth or OpenID:Connect may be possible in the future.
In SAML 2 you need to run a so called `service provider` for your service. Widly used implementations of service provider is  the apache module mod_shib with the shibboleth SP or SimpleSamlPHP. The first is a generic apporach since the authentication is handled by the apache webserver whereas the latter integrates well with PHP applications. In this document we will describe the basics of running your service provider with Apache and mod_shib.



