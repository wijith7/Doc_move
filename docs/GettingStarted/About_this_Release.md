# About this Release

### What is new in this release

WSO2 Identity Server (WSO2 IS) version **5.7.0** is the successor of
version **5.6.0,** and contains the following new features and
enhancements:

-   [Adaptive
    authentication](https://docs.wso2.com/display/IS570/Adaptive+Authentication)
    support that allows:
    -   [Role based
        authentication](https://docs.wso2.com/display/IS570/Configuring+Role-Based+Adaptive+Authentication)

    -   [User-age-based
        authentication](https://docs.wso2.com/display/IS570/Configuring+User-Age-Based+Adaptive+Authentication)

    -   [Tenant-based
        authentication](https://docs.wso2.com/display/IS570/Configuring+Tenant-Based+Adaptive+Authentication)

    -   [User store-based
        authentication](https://docs.wso2.com/display/IS570/Configuring+User-Age-Based+Adaptive+Authentication)

    -   [IP-based
        authentication](https://docs.wso2.com/display/IS570/Configuring+IP-Based+Adaptive+Authentication)

    -   [New-device-based
        authentication](https://docs.wso2.com/display/IS570/Configuring+New-Device-Based+Adaptive+Authentication)

    -   [ACR-based
        authentication](https://docs.wso2.com/display/IS570/Configuring+ACR-Based+Adaptive+Authentication)

    -   [Risk-based
        authentication](https://docs.wso2.com/display/IS570/Configuring+Risk-Based+Adaptive+Authentication)

-   [User managed access
    (UMA)](https://docs.wso2.com/display/IS570/User+Managed+Access) that
    allows resource owners to have control over client access to
    protected resources.
-   Support to integrate with Office 365. For detailed information, see
    [Integrating Office365 with WSO2 Identity
    Server](https://docs.wso2.com/display/IS570/Logging+in+to+Office365+Using+WSO2+Identity+Server).
-   [SAML 2.0 artifact
    binding](https://docs.wso2.com/display/IS570/Configuring+SAML+2.0+Artifact+Binding) support
    for SAML service provider.
-   Carbon Health Check API to [monitor server
    health](https://docs.wso2.com/display/ADMIN44x/Monitoring+Server+Health).
-   Support to select [how you want to prompt for credentials when you
    configure JIT provisioning for an Identity
    Provider](https://docs.wso2.com/display/IS570/Configuring+Just-In-Time+Provisioning+for+an+Identity+Provider#ConfiguringJust-In-TimeProvisioningforanIdentityProvider-PromptCreds).
-   Support to [customize Just-In-Time provisioning user
    interfaces](https://docs.wso2.com/display/IS570/Customizing+Just-In-Time+Provisioning+User+Interfaces).

-   Support to [configure consent purposes for JIT
    provisioning](https://docs.wso2.com/display/IS570/Configuring+Just-In-Time+Provisioning+Consent+Purposes).

-   Support to [configure consent purposes for
    self-registration](https://docs.wso2.com/display/IS570/Self-Registration+and+Account+Confirmation#Self-RegistrationandAccountConfirmation-SelfRegConsentConfiguringself-registrationconsentpurposes).

-   Support to [upload multiple certificates for an identity
    provider](https://docs.wso2.com/display/IS570/Adding+and+Configuring+an+Identity+Provider#AddingandConfiguringanIdentityProvider-multipleCert).
-   [Logical operators for SCIM2
    filters](https://docs.wso2.com/display/IS570/SCIM+2.0+REST+APIs). 

### What has changed in this release

The Analytics distribution of previous WSO2 Identity Server releases was
based on WSO2 Data Analytics Server (WSO2 DAS). With WSO2 Identity
Server 5.7.0, the Analytics distribution is based on WSO2 Stream
Processor (WSO2 SP). For information on how to work with WSO2 Identity
Server Analytics, see [WSO2 Identity Server
Analytics](https://docs.wso2.com/display/IS570/Analytics).

### WUM updates

This section lists new features and improvements that are introduced to
WSO2 IS 5.7.0 via WUM updates.

<table>
<colgroup>
<col style="width: 52%" />
<col style="width: 47%" />
</colgroup>
<thead>
<tr class="header">
<th>New feature or improvement</th>
<th>The date of the WUM update</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Support to enable reCaptcha during the following account recovery scenarios:</p>
<ul>
<li>At the time of <a href="https://docs.wso2.com/display/IS570/Username+Recovery#UsernameRecovery-reCaptchaforusernamerecovery">user name recovery</a>.</li>
<li>At the time of <a href="https://docs.wso2.com/display/IS570/Password+Recovery#PasswordRecovery-reCaptchaforpasswordrecoveryusingnotifications">password recovery using notifications</a>.</li>
<li>At the time of <a href="https://docs.wso2.com/display/IS570/Password+Recovery#PasswordRecovery-reCaptchaforpasswordrecoveryusingchallengequestions">password recovery using challenge questions</a>.</li>
</ul></td>
<td>Effective from the 2nd of October 2018</td>
</tr>
</tbody>
</table>

### Compatible versions

For information on the Carbon platform version and Carbon Kernel version
of WSO2 IS 5.7.0, see the [Release
Matrix](https://wso2.com/products/carbon/release-matrix/).

All WSO2 products that are based on a specific Carbon Kernel version are
expected to be compatible with each other. If you come across any
compatibility issue, [contact team WSO2](https://wso2.com/contact/).

### Fixed issues

For a complete list of improvements and bug fixes available with this
release, see [WSO2 IS 5.7.0 - Fixed
Issues](https://github.com/wso2/product-is/milestone/45?closed=1).

### Known issues

-   For a complete list of open issues related to the WSO2 Identity
    Server runtime, see [WSO2 IS Runtime - Open
    Issues](https://github.com/wso2/product-is/issues).
-   For a complete list of open issues related to the WSO2 Identity
    Server analytics, see [WSO2 IS Analytics - Open
    Issues](https://github.com/wso2/analytics-is/issues)
