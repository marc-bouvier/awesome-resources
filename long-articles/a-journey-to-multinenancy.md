# Abstract

How we did migrate to a multi-tenant architecture


# Before

The application is a saas product that consists in an api to support integrations and a back office to handle configuration, subscritption, and nlbusiness capabilities.



An angular frontend, a spring boot application which consists in a 
signing module and an api module.

The api module handles authentication (user / group management), subscription management and some business capabilities.

The backend is conected to a database that handled
all the storage (including audit tables with enver and database migrztion tables with liquivase)

All is stored in the same database schema.

# A question from our stakeholder




