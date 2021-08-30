
# FILES

This folder contains materials from our Aug 2021 all-hands meeting.

You can access this material in:

- [markdown](README.md) (this file)
- [html](20200828_allhands_minutes.html)
- [pdf](20200828_allhands_minutes.pdf)
- [text](20200828_allhands_minutes.txt) (UTF8)
- [org](20200828_allhands_minutes.org) (source)

# Table of Contents

1.  [Overall Status](#orgdf30689)
    1.  [Additional Colo/Deployments](#orgec922cf)
2.  [Call to order (14:15)](#org7da7083)
    1.  [Thanks for joining](#orge3ecd84)
    2.  [Good community feedback (as seen in chat)](#orga2d4941)
    3.  [Cloud Mercado feedback is out](#org2b99aa4)
        1.  [Being compared to paid platforms (while we're on a budget)](#orgaa159a4)
        2.  [Not embarrassing; in-flight improvements we're considered](#org5a92389)
    4.  [New volunteers](#org48a714a)
3.  [TODOs](#orgb349662)
    1.  [Update (or remove) WIKI](#org2045625)
        1.  [Corwin: focus on standalone documents in git](#org25c3567)
        2.  [Alyx: automation/federation](#orgf6685db)
        3.  [Corwin: process gets stale/ignored fast](#orga8d0e7c)
        4.  [Alyx: balance of expectations vs "not too worried about it"](#org3161608)
        5.  [research/suggest approach (Alyx)](#org37fba6a)
    2.  [RL - dedicated infra via equinix metal](#org5d10dd2)
    3.  [Expansion plans](#org80fc288)
        1.  [UT - updating Debian (bullseye)](#org3592c0c)
        2.  [Hive - need UEFI keys?](#org164d900)
        3.  [No work has been done on the London location](#org441d463)
        4.  [12 new proxmox nodes](#org94cdc0b)
4.  [AARCH64](#orgcc11830)
    1.  [aquired some 240gb SATA SSD](#orgb82c299)
    2.  [Commercial Cloud Provider Support](#org2be4fac)
        1.  [Oracle has launched a program to support FOSS](#org9a2145a)
        2.  [AWS has given us USD 5k credit & USD 3K gift card to amazon.com](#org7dd4a27)
    3.  [FOSS Project Conservation Updates](#orgdeb7f4b)
        1.  [part of our original orginal focus](#org2cc1cac)
        2.  [give projects org (as well as tech) infrastructure/support](#org5331b5f)
        3.  [there are similar projects but nothing we think is "quite us"](#org6697ada)
        4.  [working title for the work is now "FOSSBANK"](#orgaf1022c)
        5.  [at the prototype stage](#org69d6731)
        6.  [flavor of flow/products](#orga45e506)
5.  [Chat Channels](#orgc5f4f8c)
    1.  [We have quite a few right now](#org2f9e133)
    2.  [VC text vs VC text private is especially confusing](#orgc183cab)
        1.  [generally use priv when chatting in a volunteers only](#org95798f8)
        2.  [renamed to include "volunteers" in the name](#org79f18ec)
    3.  [some roadmap opportunities with](#org2b90185)
6.  [Meeting ended (16:00)](#org4bad967)

> These are the full and complete minutes recording the Aug 2021
> FOSSHOST team ("All Hands") meeting. The overall status section was
> added after the meeting.  There may be errors or omissions due e.g, to
> digression; however, these notes were not (otherwise)
> redacted/trimmed.  (Corwin)

![img](fh-banner.png)


<a id="orgdf30689"></a>

# Overall Status

-   We've added a number of new volunteers so far in 2021.
    
    This was a first or second team meeting for several; we
    did quick round of self-introductions from new-volunteers.

-   The network is also growing.
    
    The next section lists our pending and in-flight deployments of
    into new/expanded CoLo.

-   Progress is slow on documentation/policy/etc work.
    
    Today we discussed the need to make good use of volunteers time
    creating documentation by having specific "documentation projects"
    prioritized and with questions and in idea of the time commitments
    involved for SMEs to plan to better support that type of work
    without disrupting other important work.

-   FOSSHOST will provide volunteers with headsets
    
    If you need an headset, e.g. to participate in the team call let
    Hope or another lead know. This doesn't cost cash thanks to
    gift-card from Amazon!


<a id="orgec922cf"></a>

## Additional Colo/Deployments

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<tbody>
<tr>
<td class="org-left">Location</td>
<td class="org-left">Status</td>
</tr>


<tr>
<td class="org-left">Utah</td>
<td class="org-left">finish OS updates; deploy AARCH64 (hammy, team)</td>
</tr>


<tr>
<td class="org-left">Boston</td>
<td class="org-left">finish OS updates; deploy AARCH64 (hammy/team)</td>
</tr>


<tr>
<td class="org-left">London</td>
<td class="org-left">reqs FH staff onsite (thomas, deploy switch)</td>
</tr>


<tr>
<td class="org-left">Canada</td>
<td class="org-left">Setup pending, awaiting staff-time/priority</td>
</tr>
</tbody>
</table>


<a id="org7da7083"></a>

# Call to order (14:15)


<a id="orge3ecd84"></a>

## Thanks for joining


<a id="orga2d4941"></a>

## Good community feedback (as seen in chat)


<a id="org2b99aa4"></a>

## Cloud Mercado feedback is out


<a id="orgaa159a4"></a>

### Being compared to paid platforms (while we're on a budget)


<a id="org5a92389"></a>

### Not embarrassing; in-flight improvements we're considered


<a id="org48a714a"></a>

## New volunteers


<a id="orgb349662"></a>

# TODOs


<a id="org2045625"></a>

## Update (or remove) WIKI


<a id="org25c3567"></a>

### Corwin: focus on standalone documents in git


<a id="orgf6685db"></a>

### Alyx: automation/federation


<a id="orga8d0e7c"></a>

### Corwin: process gets stale/ignored fast


<a id="org3161608"></a>

### Alyx: balance of expectations vs "not too worried about it"


<a id="org37fba6a"></a>

### TODO research/suggest approach (Alyx)

-   get alignment from Nate/Hammy&Corwin/Hope or Thomas


<a id="org5d10dd2"></a>

## RL - dedicated infra via equinix metal

-   project needed complex infra neededing dedicated infra
-   due to requirements around protecting signing-certs for gov use
-   not using due to need for an additional "jump-box"
-   this also needs a (second) dedicated host
-   nik a reached out to RL last week,
    -   no response as yet
    -   we note they are also a busy volunteer driven project
    -   somewhat expecting they will release the unused server
    -   we haz a sad
    -   don't think we will be able to purchase the second node
    -   this would be 50% of/would double vs current monthly co-lo costs
-   assigned machine is huge but planned to be used just for signing
-   


<a id="org80fc288"></a>

## Expansion plans


<a id="org3592c0c"></a>

### UT - updating Debian (bullseye)


<a id="org164d900"></a>

### Hive - need UEFI keys?

1.  hammy didn't have email confirming USB receipt

2.  Thomas will forward


<a id="org441d463"></a>

### No work has been done on the London location


<a id="org94cdc0b"></a>

### 12 new proxmox nodes

updates, install proxmox, recommend logging into each node
This to check.  Thomas can show you how to check, review what to check.

1.  Thomas to document list of things to check?

2.  Hope to create a rotation (nodes per week?)

3.  This could be a good "test" for our new approach to documentation

    1.  leaders to take "scoping and planning" offline
    
    2.  let tech teammembers know the specific questions/time commitments


<a id="orgcc11830"></a>

# AARCH64


<a id="orgb82c299"></a>

## aquired some 240gb SATA SSD

-   purchased caddies from amazon (using credit we have)
-   thomas will stage send to hammy
-   targeting BOS for initial install of addl SSD for each node
-   future options
    -   repurpose/add a node to AARCH64 to be a "cloud disk" host
    -   could purchase riser card, perhaps NVMe capable (experimental!)
    -   (jonathon) Backblaze might donate some hardware :thinking:
-   (nik) do we have data center support?
-   (thomas) the are pulled from the floor but we can get support


<a id="org2be4fac"></a>

## Commercial Cloud Provider Support


<a id="org9a2145a"></a>

### Oracle has launched a program to support FOSS

1.  Thomas is reaching out to see if they can donate credits to us


<a id="org7dd4a27"></a>

### AWS has given us USD 5k credit & USD 3K gift card to amazon.com


<a id="orgdeb7f4b"></a>

## FOSS Project Conservation Updates


<a id="org2cc1cac"></a>

### part of our original orginal focus


<a id="org5331b5f"></a>

### give projects org (as well as tech) infrastructure/support


<a id="org6697ada"></a>

### there are similar projects but nothing we think is "quite us"

1.  SPI - Software In the Public Interest

2.  Open Collective

3.  GNU


<a id="orgaf1022c"></a>

### working title for the work is now "FOSSBANK"


<a id="org69d6731"></a>

### at the prototype stage


<a id="orga45e506"></a>

### flavor of flow/products

1.  products apply (completely sep from FH)

2.  similar to credit check

    1.  we apply a formulaic scoring system ("Secret Sauce"?)
    
    2.  provide a history and profile
    
    3.  option to make your records public to meet transparency goals

3.  once approved projects receive requested funds as loans

    1.  "virtual accounts", not actually providing a true "bank" service

4.  access to legal and other professional services

5.  acceptable to use this money to "pay yourself"

    1.  salaries
    
    2.  "outside" professional and other expenses

6.  Very new/WIP still; we'll share further updates as things get "closer"

    \*\*


<a id="orgc5f4f8c"></a>

# Chat Channels


<a id="org2f9e133"></a>

## We have quite a few right now


<a id="orgc183cab"></a>

## VC text vs VC text private is especially confusing


<a id="org95798f8"></a>

### generally use priv when chatting in a volunteers only


<a id="org79f18ec"></a>

### renamed to include "volunteers" in the name


<a id="org2b90185"></a>

## some roadmap opportunities with


<a id="org4bad967"></a>

# Meeting ended (16:00)

