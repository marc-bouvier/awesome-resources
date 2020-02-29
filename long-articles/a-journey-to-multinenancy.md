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

Our main sponsor and stakeholder is our CEO. Our company
is the first user of our product. This allow us to have useful
and realistic feedback. This additionally adds
a strategic and financial input to the business value
of the features we develop.

Our CEO asked this questions. Can we ensure our customers that their data won't be
mixed with data of other customers? Can we ensure that
a peak of usage on a customer won't affect the performance of other customers?




