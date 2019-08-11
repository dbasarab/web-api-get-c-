# web-api-get-c-
web api get c#
Hi,

If you set the web api project as the default you can run it on local machine. Here is my url
http://localhost:56365/api/search/getroute?origin=yyz&destination=yvr

port number may be different on your machine. In properties/web it is the port number for IISExpress. Just press F5 and run the project.

In App_Data folder I added Routes.txt - I load asyc the data from the csv file. Code is commented out as it does not yield the same results as test data - but it works fine. Loading is in RepoRoutes.cs

I have not provided unit test as it takes too much time.

Thank you for your time,
Dan Basarab
