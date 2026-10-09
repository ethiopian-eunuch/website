---
title: Suggestions To Increase Office 365 Security
source: Microsoft Office 365 Admin Portal
author: ME
published: 2026-10-09
created: 2026-10-09
description: This is a list of items that Microsoft suggests to implement to increase security at the Office 365 system level.
tags: microsoft, o365
---
1.  Ensure that intelligence for impersonation protection is enabled

2.  Move messages that are detected as impersonated users by mailbox intelligence

3.  Enable impersonated domain protection

4.  Set the phishing email level threshold at 2 or higher

5.  Enable impersonated user protection

6.  Quarantine messages that are detected from impersonated domains

7.  Quarantine messages that are detected from impersonated users

8.  Ensure 'External sharing' of calendars is not available

9.  Ensure additional storage providers are restricted in Outlook on the web

10.  Ensure the Common Attachment Types Filter is enabled

11.  Ensure all forms of mail forwarding are blocked and/or disabled

12.  Ensure DLP policies are enabled

13.  Set action to take on high confidence spam detection

14.  Ensure user consent to apps accessing company data on their behalf is not allowed

15.  Ensure MailTips are enabled for end users

16.  Ensure mailbox auditing for all users is Enabled

17.  Ensure users installing Outlook add-ins is not allowed

18.  Enable the domain impersonation safety tip

19.  Enable the user impersonation safety tip

20.  Enable the user impersonation unusual characters safety tip

21.  Ensure Exchange Online Spam Policies are set to notify administrators

22.  Ensure Safe Links for Office Applications is Enabled

23.  Ensure that an anti-phishing policy has been created

24.  Only invited users should be automatically admitted to Teams meetings

25.  Configure which users are allowed to present in Teams meetings

26.  Publish M365 sensitivity label data classification policies

27.  Ensure the customer lockbox feature is enabled

28.  Restrict anonymous users from joining meetings

29.  Designate more than one global admin

30.  Use least privileged administrative roles

31.  Block users who reached the message limit

32.  Extend M365 sensitivity labeling to assets in Microsoft Purview data map

33.  Ensure that Auto-labeling data classification policies are set up and used

34.  Set the email bulk complaint level (BCL) threshold to be 6 or lower

# Impersonation settings in anti-phishing policies in Microsoft Defender for Office 365
Impersonation is where the sender or the sender's email domain in a message looks similar to a real sender or domain:

An example impersonation of the domain contoso.com is ćóntoso.com.
User impersonation is the combination of the user's display name and email address. For example, Valeria Barrios (vbarrios@contoso.com) might be impersonated as Valeria Barrios, but with a different email address.
> [!NOTE]
>
>Impersonation protection looks for domains that are similar. For example, if your domain is contoso.com, we check for different top-level domains (.com, .biz, etc.), but also domains >that are even slightly similar. For example, contosososo.com or contoabcdef.com might be seen as impersonation attempts of contoso.com.

An impersonated domain might otherwise be considered legitimate (the domain is registered, email authentication DNS records are configured, etc.), except the intent of the domain is to deceive recipients.

The impersonation settings for user impersonation protection, domain impersonation protection, mailbox intelligence, impersonation safety tips, and trusted senders and domains are available only in anti-phishing policies in Defender for Office 365.

> [!TIP]
>
>Details about detected impersonation attempts are available in the impersonation insight. For more information, see Impersonation insight in Defender for Office 365.
>
>For a comparison of impersonation versus spoofing, see Spoofing vs. impersonation.

Ensure multifactor authentication is enabled for all users in administrative roles

Ensure multifactor authentication is enabled for all users

Create Safe Links policies for email messages
