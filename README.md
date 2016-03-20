# Social Harvest

Social Harvest is an open-source social media analytics and monitoring tool. It's goal is to help
provide insight for social media for individuals and small businesses. It is not designed as an 
enterprise tool; however, there is nothing preventing the enterprise from finding value within it.

Therefore, one of the primary focuses of this tool is cost effective hosting. Parts of this application
can be pulled out and executed separately on a variety of hosting providers, but the "microservices" 
are designed to run under Amazon Web Services (AWS). This includes services such as Lambda and 
Elastic Map/Reduce (EMR). By using these services, the user pays for exactly what they use.

Naturally, the requirement here is that the user must be signed up for AWS. Upon launching Social Harvest,
the user will be asked for their credentails for that the apllication can setup all of the necessary
components for them.

This repository includes both the orchestration of services as well as the desktop GUI client. This client
will work on Windows, OS X, and Linux. It is cross platform. However, there is currently no browser based
client that can be hosted on a web server nor a mobile client (for now).

Other repositories include some of the core functionality and utilities that may even be useful outside
of Social Harvest itself. For example, if there was no interest in using AWS services.