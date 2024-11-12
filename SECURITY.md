# Security Policy

## Supported Versions

Table below shows all currently supported Demand Console releases by their version and build numbers. For SDK release info, [look here]()
All unlisted DMD Console builds are not supported. *End of life* (EOL) means a software will no longer receive security and feature updates, or any more updates at all.


### Below is an explanation on some of the terms used in the table:

|   Term   | Explanation |
| :------: | :-------------------------------------: |
|`Version` | Uses following format: `sdk.maj.min.patch.hotfix`; like so: `v1.2.3`|
|`Build`   | Uses following format: `sdk.maj-min-patch-hotfix`; like so: `build 1.1234`|
|`Features`| Signifies Feature Updates. Contains feature additions, changes and modifications. Performance changes and bug fixes are also delivered thru this. |
|`Security`| Signifies Critical Updates. Critical Updates includes hotfixes for a broken/unusable feature, a Security Patch that addresses a security concern, or other Patches that help improve DMD's performance and usability. |
|`Beta DMD`| Is a beta DMD version being developed? Shows build number for first beta release of that version |
|`SDK LvL` | DMD Software Data Kit version ([learn more](https://github.com/users/blinkyboi/projects/5)) |
|`DMD Server`| Technologies used to contact DMD Server. APiv1 is basic with no form of security to authenticate requests. APiv2 is equipped with higher level of security, endpoint isolation, SessionGuard, AUthKeY and more. | 


## All Demand Console Releases Table


|  Version  |  Build  |  Features  |  Security  | Beta DMD |  SDK Level  |  DMD Server  |  Last Update On (or End of Life [EOL])  | 
| :-------: | :-----: | :--------: | :--------: | :------: | :---------: | :----------: | :--------------: |
|  v0.1.0   | DMD010  | :x:        | :x:        | :x:      |  ~~0.1.0~~  |   `APiv1`    |  ~~08/01/2024~~ EOL: 08/01/2024  |
|  v1.0.0   | 1.0000  | ✔️        | ✔️         | build 1.0000 | 1.0.0    |   `APiv2`    | 08/13/2024 |


## Reporting a Vulnerability

To report a vulnerability, please join the [discord server](https://discord.gg/nSHPMG8zsH) or send a direct message to `dr.heinzdoofenshmirtz33` on Discord. All info on reporting will be found there.

Updates are released on the 2nd or 3rd week of the Month. Expect 2 major updates, one for the Security Updates, and the other for feature updates. Patches and hotfixes are released coninuously (when events permit) until EOL.
Usually DMDU will inform you of new updates, but it is recommended to manually double-check often.
