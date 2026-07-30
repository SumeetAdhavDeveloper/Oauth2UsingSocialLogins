This is Base level Oauth 2.0 framework social login project


What we have used in?

-Spring Oauth2.0 Client
-Spring Oauth2.0 Resource Server
As our spring boot application will behave as client and Resource server as well

@Bean
This annotation tells Spring that the method returns an object that should be managed as a Spring bean
 in the application context. In other words, Spring will call this method and register its return value as a bean.

ClientRegistrationRepository
This is an interface from Spring Security OAuth2. It represents a repository of client registrations
(i.e., configurations for OAuth2/OpenID Connect providers like Google, GitHub, etc.).
Each ClientRegistration contains details such as client ID, client secret, authorization URI, token URI, etc.

InMemoryClientRegistrationRepository()
This is an in-memory implementation of ClientRegistrationRepository.
It stores client registration details in memory rather than in a database or external system.
Typically, you pass one or more ClientRegistration objects into its constructor so that Spring Security knows
which OAuth2 providers are available for login.