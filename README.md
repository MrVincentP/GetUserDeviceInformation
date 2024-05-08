# Get User Device Information
get user device information by client browser.

# Requirement
Sometimes, we need to use a browser to find out on which platform our web application is running.

In this way, we can complete the business we need based on the obtained device environment information.

# Principle

Obtain basic information of the device through UA.

Or reassign some information through the information in our URL.

# Example
import GetUserDeviceInformation from 'GetUserDeviceInformation';

    const env = GetUserDeviceInformation();

On PC you will get

        appMode:"browser"
        appName:"chrome"
        appType:"web"
        appVersion:"1.1"
        browser:"Chrome"
        browserVersion:"124.0.0.0"
        env:"pc"
        equipment:"Windows"
        equipmentOS:"Windows 10"
        osVersion:"Win10.0"

On Mobile you will get (Android)

        appMode:"browser"
        appName:"chrome"
        appType:"web"
        appVersion:"1.1"
        browser:"Chrome"
        browserVersion:"124.0.0.0"
        env:"mobile"
        equipment:"Android"
        equipmentOS:"Android 13"
        osVersion:""

On Mobile you will get (IOS)

        appMode:"browser"
        appName:"version"
        appType:"web"
        appVersion:"1.1"
        browser:"Safari"
        browserVersion:"16.6"
        env:"mobile"
        equipment:"IOS"
        equipmentOS:"Iphone"
        osVersion:"iphone os 16.6"
