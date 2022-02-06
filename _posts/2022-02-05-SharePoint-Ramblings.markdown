---
layout: post
title:  "SharePoint Permissions Ramblings"
date:   2022-02-05 21:40:00 -0800
categories: SharePoint IT
---
When you make a new SharePoint site, it generates 'Member' and 'Guest' permission groups. It then attaches these permission groups to their identically named O365 group. This results in the 'Member' group having the 'Member' permissions group. Which is all good and dandy if you don't disassociate the permission group from the O365 group.... But once you remove the permission group it may end up looking identical, while not operating at all as expected.

One useful feature of this behavior is the ability to assign SharePoint permission groups to ANY O365 group. So, if all of one department should have access to a Sharepoint site but you do not want to manage inviting people on a case by case basis, attach the permissions group to the departments O365 group instead. Then when they are onboarded to their respective group they will automatically inherit access to the Sharepoint site.[^1]





[^1]:This information may or may not be correct, as I am learning new things every day and am usually quite confused. Take this as a starting point for investigating your own conclusions/solutions.