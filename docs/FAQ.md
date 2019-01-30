---
title: "FAQ"
date: 2018-11-14T11:59:23+05:30
draft: false
weight: 5
---
# FAQ

-   [Can I use updates without a paid
    subscription?](#FAQ-CanIuseupdateswithoutapaidsubscription?)
-   [What benefits do I get from a paid
    subscription?](#FAQ-WhatbenefitsdoIgetfromapaidsubscription?)
-   [Do I need a key to unlock updates for
    production?](#FAQ-DoIneedakeytounlockupdatesforproduction?)
-   [Can I choose which updates to
    install?](#FAQ-CanIchoosewhichupdatestoinstall?)
-   [What license are WSO2 updates
    on?](#FAQ-WhatlicenseareWSO2updateson?)
-   [How frequently is it recommended to get
    updates?](#FAQ-Howfrequentlyisitrecommendedtogetupdates?)
-   [Should I test my updates?](#FAQ-ShouldItestmyupdates?)
-   [How do I know when updates are
    available?](#FAQ-HowdoIknowwhenupdatesareavailable?)
-   [What can I do in case of an
    issue?](#FAQ-WhatcanIdoincaseofanissue?)
-   [How can I know what changes are included in an
    update?](#FAQ-HowcanIknowwhatchangesareincludedinanupdate?)
-   [I get an error as 'You do not have an active subscription or the
    channel does not exist'. What should I
    do?](#FAQ-Igetanerroras'Youdonothaveanactivesubscriptionorthechanneldoesnotexist'.WhatshouldIdo?)
-   [I get the error as 'invalid credentials. Please enter valid WSO2
    credentials'. What should I
    do?](#FAQ-Igettheerroras'invalidcredentials.PleaseentervalidWSO2credentials'.WhatshouldIdo?)

#### Can I use updates without a paid subscription?

You can use the [free trial
subscription](https://wso2.com/free-trial-subscription) for 15 days.
After that, you need a [paid
subscription](https://wso2.com/subscription).

Find out more about the EULA license.

#### What benefits do I get from a paid subscription?

A paid subscription allows you to:

-   Deploy updates into production immediately, without waiting for an
    open source release.
-   Receive 24x7 support from WSO2 to resolve issues quickly. 
-   Help fund our ongoing R&D and operations.

Read more about [WSO2 support and
subscriptions](https://wso2.com/support/).

#### Do I need a key to unlock updates for production?

No. We trust our customers to adhere to the license terms. We make the
terms clear to avoid accidental violations and reserve the right to
remove access to updates or take other means to enforce the license
against intentional violators.

Find out more about the EULA license.

#### Can I choose which updates to install?

Yes, but only via a custom channel. You cannot choose the updates you
want to install via the default channels (i.e., full and security). You
can choose when to push a (coherent) set of updates into production.

WSO2 tests and certifies each update on systems where all previous
updates are installed. It is not practical to test every arbitrary
combination of updates. Therefore, we cannot recommend you to choose
which updates to install unless you have a custom channel.

#### What license are WSO2 updates on?

We are releasing WSO2 updates with a commercial [EULA
license](https://wso2.com/licenses/wso2-update/2.0).

#### How frequently is it recommended to get updates?

WSO2 releases frequent WUM updates with bug fixes and security fixes. It
is recommended to get these updates to
your **development** environments **weekly or bi-weekly**.

When it comes to **production** environments, if there are urgent
security fixes, WSO2 will announce them to customers via support JIRAs.
In addition, WSO2 announces all security updates, if any, to the
customers monthly. It is recommended to update your production
environments **monthly**.

#### Should I test my updates?

WSO2 tests all updates in systems where all previous updates are also
installed. But, it is not recommended to install your updates directly
to a production environment. First, install them to a development,
staging, or testing environment that has the same product distribution
that runs on your production environment and test the updates.

#### How do I know when updates are available?

Available updates, if any, will be shown when you run the in-place
update tool. 

If you are using the WUM tool, run the wum check-update command.

#### What can I do in case of an issue?

If you encounter any issues when using WSO2 updates, log a [support JIRA
ticket](https://support.wso2.com/). If you have a free-trial subscrition
but do not have a support account at WSO2, you can report the issues
by contacting WSO2 via https://wso2.com/contact.

#### How can I know what changes are included in an update?

You receive an email with information on all the changes included in the
new distribution. You also find this information in
`<PRODUCT_HOME>/updates/summary` as a PDF file.

#### I get an error as 'You do not have an active subscription or the channel does not exist'. What should I do?

First, check whether you typed the channel name correctly. If yes, then
you should have got your WSO2 subscription via that given channel name.
If you haven't, please contact WSO2.

#### I get the error as 'invalid credentials. Please enter valid WSO2 credentials'. What should I do?

First, check whether you have given the right credentials. If yes, check
whether your password has the $ sign. If it does, escape it using '\\'.
For example, if your password is 123$abc, you should enter
123\\$abc. This is because the $ sign is used for variables in BASH.
