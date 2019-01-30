# Quick Start Guide

[WSO2 Identity Server (WSO2 IS) is a comprehensive identity and access management (IAM) solution. This guide gives you a quick walk-through to WSO2 IS using a sample scenario.   

## __<font color="#455A64">Sample Scenario</font>__
Pickup is a cab company that has many employees who use different credentials to sign in to different internal enterprise applications. Following are two such applications:

* Pickup Dispatch: This application helps manage the overall operations at Pickup.
* Pickup Manager: This application helps allocate vehicles to drivers. 


Please see the [Prerequisites](http://127.0.0.1:8000/QSG/#prerequisites) for further details.

Please see the [Totosque torum](http://127.0.0.1:8000/QSG/#totosque-torum) for further details.


![screenshot](images/sample.png) 

Pickup needs to identify the necessary permission levels to be granted to the employees and any security vulnerabilities.

Cameron is a senior manager at Pickup who is responsible for resolving these issues using WSO2 IS. Alex is a junior manager attending to day-to-day tasks and Rowan is the HR manager. 

## __<font color="#455A64">Prerequisites</font>__
1. Download and install Oracle Java SE Development Kit (JDK) version 1.7.* or 1.8.
2. Install WSO2 IS 5.7.0 by downloading the [installer](https://wso2.com/identity-and-access-management/install/). 
   The WSO2 IS installation location varies according to the OS as given below.

    |OS     |Home Directory                                |
    |:------|:---------------------------------------------|
    |Mac OS | `/Library/WSO2/IdentityServer/5.7.0`         |
    |Windows| `C:\Program Files\WSO2\IdentityServer\5.7.0` |
    |Ubuntu | `/usr/lib/wso2/IdentityServer/5.7.0`         |
    |CentOS | `/usr/lib64/IdentityServer/5.4.70`           |

    !!! note "Note"
        Hereafter, the installation location of WSO2 IS is called `<IS_HOME>`.

3. [Download](https://tomcat.apache.org/download-80.cgi) and [install](https://tomcat.apache.org/download-80.cgi) Apache Tomcat version 8.*.* or above.
4. [Download](https://curl.haxx.se/download.html) and install curl.
5. Create a Twitter application to try out multi-factor or federated authentication. 
    1. Go to [https://twitter.com/](https://twitter.com/) and create an account.
    2. Register a new application on Twitter at [https://apps.twitter.com](https://apps.twitter.com). You can use the following URL as the Callback URL for your Twitter application: [https://localhost:9443/commonauth](https://localhost:9443/commonauth).
    3. Note down the `API key` and `secret` for later use.
6. Open the `/etc/hosts` file and add the following entry.        
    
        127.0.0.1        localhost.com    

    !!! warning "Warning"
        If you are planning to use Single Sign-On (SSO), do not use `localhost` as it will cause the Tomcat naked host issue. Use `localhost.com` instead. If you are using Windows, `localhost.com` is considered as `127.0.0.1`.

    !!! note "Note"
        Make sure that this is the only such entry available for this IP address in the `/etc/hosts` file to avoid any conflicts.
7. [Start](https://docs.wso2.com/display/IS570/Running+the+Product) WSO2 IS. 
    </br>
    Now you are ready to deploy the sample.

## __<font color="#455A64">Deploying the Sample</font>__


## __<font color="#455A64">Trying the Sample</font>__

