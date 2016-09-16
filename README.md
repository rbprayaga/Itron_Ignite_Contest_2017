# Itron_Ignite_Contest_2017
All deliverables related to the Itron OpenRiva Ignite Innovation Contest 2017
################################################################################################################################
#                         README FILE FOR EXECUTING THE DEMO APPLICAITON TO PUSH THE DATA TO CLOUD
#
################################################################################################################################


Step 1: Push the files to Edge board. This can be done from Ubuntu system to the EdgeBoard.

Step 2: Login to Itron EdgeBoard from Ubuntu. Navigate to directory where the python script exists.

Step 3: Execute the python script to push the data to the cloud.
	


################################################################################################################################
#                                        Detailed Information
#
################################################################################################################################


Input source file:

This file holding the outage information having 6 colums of information.

colum1:
           information about the ServicePointID.
colum2:
	   information about the SPLatitude.
colum3:

           information about the SPLongitude.
colum4:
	   information about the TransformerID.

colum5: 
	   information about the StartTime.
colum6:
           information about the EndTime.


###################################################################################################
		Mobile App
###################################################################################################

Power outage is cross platform mobile app built on Xamarin Forms and ArcGIS Xamarin forms SDK.

# list of softwares required to build the app


1. Visual Studio 2015 update 3

2. Latest Xamarin forms SDK
   https://www.nuget.org/packages/Xamarin.Forms/

3. Install the below packages along with Xamarin forms.
	Open the Package manager console in visual studio and install the following packages. 
	Install-Package Refractored.MvvmHelpers
	Install-Package Xamarin.Forms.Theme.Base -Pre
	Install-Package Xamarin.Forms.Theme.Light -Pre
	Install-Package Xamarin.Forms.Theme.Dark -Pre

3. ArcGIS Xamarin SDK.
	https://developers.arcgis.com/xamarin/quartz/android/guide/install-the-sdk.htm

4. To build the iOS app, please connect Mac and follow the instructions below url

https://developer.xamarin.com/guides/ios/getting_started/installation/windows/introduction_to_xamarin_ios_for_visual_studio/

https://developer.xamarin.com/guides/ios/getting_started/installation/windows/connecting-to-mac/

    



