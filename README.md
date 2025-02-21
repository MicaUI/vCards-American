vCards US
=====

Imported common contact avatars, optimised iOS call and message interface experience.

![Screenshot](https://user-images.githubusercontent.com/2666735/59692672-0b6bdf00-9218-11e9-881e-5856e263f3aa.png)

### Guidelines for use

### Subscription: CardDAV service/ or refer to [Tutorial Build Your Own](https://github.com/metowolf/vCards/issues/208)
The advantage of importing by subscription is that it will be updated automatically, and it is also more convenient to distinguish and manage personal address book and yellow pages without mixing the two lists.

 - Server: `vcards.metowolf.com`
 - Username: `cn`
 - Password: `cn` or whatever you want

Steps:
1. [iOS](https://support.apple.com/zh-sg/guide/iphone/ipha0d932e96/ios): ‘Settings’ - ‘Contacts’ - ‘Accounts’ - ‘Add Accounts’ - ‘Other’ - ‘Add CardDAV Accounts
2. [Mac](https://support.apple.com/zh-cn/guide/contacts/adrb7e5aaa2a/mac): ‘Contacts’ - ‘Settings’ - ‘Accounts’ - ‘Other Address Book Accounts

### Download and Import

1. Go to https://github.com/metowolf/vCards/releases to download the latest packaged file `archive.zip`;
2. Unzip the file and import the `vcf` file to iCloud according to the guidelines of different platforms, it is recommended to create a separate `yellow pages` group for easy management and hiding.

#### macOS
 - [Create groups of contacts in Contacts on Mac](https://support.apple.com/zh-cn/guide/contacts/adrb3280fe91/12.0/mac/10.14)
 - [Import contacts from other apps in Contacts on Mac](https://support.apple.com/zh-cn/guide/contacts/adrbk1457/mac)

#### iOS/web
 - [Create a Group in iCloud Contacts](https://support.apple.com/kb/PH2667?locale=zh_CN)
 - [Import contacts into iCloud Contacts](https://support.apple.com/kb/ph3605?locale=zh_CN)

----

## Request Inclusion

 1. Open the https://github.com/metowolf/vCards/issues/new/choose page and select ‘vCard New Request’.
 2. Fill in all relevant information
 3. Submit the `issue` and wait for processing.

## Participate in maintenance

 1. Add `yaml` and `png` files to `/data/categories/`. 2.
 2. run `yarn test` in the root directory to check for formatting conventions
 3. Submit `pull requests` and wait for the merge.

## Number Inclusion

Due to the differences in the 106 SMS push numbers of different operators in different regions, the project will not include them. We suggest you use this project as a basic template, and you can add the rest of the numbers after importing the contacts in the following way.

![Screenshot](https://user-images.githubusercontent.com/2666735/59747105-ccd33480-92aa-11e9-90e0-93f295dcb504.png)


## Iconography

 - Encoded in `PNG`.
 - Canvas size `width:200px;height:200px`
 - Logo centred
   - Circle size 140w140h
   - Rectangle size 120w120h
   - Long rectangle size 160w80h
   - No svg Need to use Inkscape to convert
   - Special handling for special cases
 - Image size compressed within `20 kB`.

! [Design](https://user-images.githubusercontent.com/2666735/60966995-224fae00-a34c-11e9-970c-ea5fa15186c6.png)

## Acknowledgements

 - [114 Pepsi](http://www.114best.com/) provides query interface.
 - [Baidu Mobile Guardian](https://haoma.baidu.com/yellowPage) provides the query interface.
 - Query interface provided by [China Trusted Number Data Centre](https://www.kexinhaoma.org/).
