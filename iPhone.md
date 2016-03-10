# Appstore Release `2.3.1`
## [b244](https://gitlab.com/Tappr/tappr-ios/tree/b244) (10 Mar 2016)
### Feature
- View the user who created the order in order details

### Fixed Bugs
- Crash during background sync
- Crash when adding certain items to cart

## [b243](https://gitlab.com/Tappr/tappr-ios/tree/b243) (9 Feb 2016)
- Fixed issue with card reader connectivity

## [b242](https://gitlab.com/Tappr/tappr-ios/tree/b242) (29 Jan 2016)
- Added Deeplink debug functionality

# Appstore Release `2.2.0`
## [b241](https://gitlab.com/Tappr/tappr-ios/tree/b241) (27 Jan 2016)
### Improvement
- Redesigned the entire product library

### Fixed Bugs
- Fixed issues around categories

## [b240](https://gitlab.com/Tappr/tappr-ios/tree/b240) (27 Jan 2016)
- Generic fixes

## [b239](https://gitlab.com/Tappr/tappr-ios/tree/b239) (25 Jan 2016)
- Generic fixes

## [b238](https://gitlab.com/Tappr/tappr-ios/tree/b238) (25 Jan 2016)
- Generic fixes

## [b237](https://gitlab.com/Tappr/tappr-ios/tree/b237) (22 Jan 2016)
- Generic fixes

## [b235](https://gitlab.com/Tappr/tappr-ios/tree/b234) (21 Jan 2016)
### Fixed Bugs
- Selecting a item in order summary was not selecting the correct item
- Unknown card schemes were showing up as invalid

## [b234](https://gitlab.com/Tappr/tappr-ios/tree/b234) (23 Dec 2015)
### Fixed Bugs
- Fixed the greyed navigation bars
- Fixed the change cash label not being displayed
- Fixed issue with order not being cleared properly

## [b233](https://gitlab.com/Tappr/tappr-ios/tree/b233) (22 Dec 2015)
### Fixed Bugs
- Discounts could be applied while disabled
- Back button was missing from category screen
- Refund by card reader navigation issues

## [b232](https://gitlab.com/Tappr/tappr-ios/tree/b232) (16 Dec 2015)
### Fixed Bugs
- Edit button was missing from products screen

# Appstore Release `2.1.0`
## [b230](https://gitlab.com/Tappr/tappr-ios/tree/b230) (15 Dec 2015)
### Improvements
- Updated the PIN reset screen layout

## [b229](https://gitlab.com/Tappr/tappr-ios/tree/b228) (15 Dec 2015)
### Improvements
- Updated the look of the Business Details screen
- Updated the look of the order summary page

### New Features
- Added option to set a _default_ home screen.

## [b228](https://gitlab.com/Tappr/tappr-ios/tree/b228) (9 Dec 2015)
### Fixed Bugs
- Fixed a crash when resetting passwords

## [b227](https://gitlab.com/Tappr/tappr-ios/tree/b227) (8 Dec 2015)
### Fixed Bugs
- Prevents issues with long descriptions
- Fixed a bug where the app could get _stuck_ in offline mode

## [b226](https://gitlab.com/Tappr/tappr-ios/tree/b226) (8 Dec 2015)
### Improvements
- Updated the look of the receipt screen
- Updated the syncing functionality

## [b223](https://gitlab.com/Tappr/tappr-ios/tree/b223) (4 Dec 2015)
### Fixed Bugs
- Crash was occuring whenever a user attempted to register a new user.

## [b222](https://gitlab.com/Tappr/tappr-ios/tree/b222) (4 Dec 2015)
### Fixed Bugs
- Consecutive whitespace in descriptions caused a crash.
- Images are now correctly synced to the server.
- Fixed issues with business names going missing.

### Added functionality
- Made it clear when an order has arrived on our servers.
- Added the ability to record some more payment types:
  * Direct Deposit
  * Coupon
  * Cheque
  * Gift Card
  * Other

### Improvements
- Reduced number of network requests made by device.
- Reduced number of past orders stored on device.
- Completely updated registration process.
- Remove _Card_ payment type for users with a _Card Reader._
- Added Crashlytics so that we can understand issues users may have easier.
- Improvements to performance when syncing data with the server.
- Continuing UI refinement.

### Changes
- Only the last 7 days of orders will be synced to a device now.
