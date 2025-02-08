## Google Analytics Reporting API With Python
----------------------------------------------------------------------------------------
# UA (GA3) version of Google Analytics has been deprecated and removed by Google in 2024
# This code is no longer valid, refer to https://github.com/tanyazyabkina/GA4_API_python
----------------------------------------------------------------------------------------

How to send requests and process responses from Google Analytics Reporting API (including pivot!)

How to set up and use Google Analytics Reporting API:
1. Create a new project in Google Cloud. Helpful reference: https://cloud.google.com/resource-manager/docs/creating-managing-projects
2. Give your project access to Analytics Reporting API. Reference: https://developers.google.com/analytics/devguides/reporting/core/v4
3. Create service account credentials for the project and generate/download keys for it. 
4. Add your service account as a read and analyze user to your GA account.
5. Install Google suit of python packages, i.e. google-api-python-client. 
6. Create the request. Reference Links: https://ga-dev-tools.appspot.com/request-composer/ and also this for variable names: https://ga-dev-tools.appspot.com/dimensions-metrics-explorer/
7. Process the JSON response into a dataframe. See the code. This is what this project is about!

YouTube video with demonstration: https://youtu.be/N2bbJQroGB4
