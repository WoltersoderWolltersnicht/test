# Metadata

#### Type: object

__Metadta Root Element__

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| [shopping](#shopping) | object |  |  |

*****

## shopping

#### Type: object

__add description to json file__

Required: languages, currencies, price, nationalities, markets, paymentTypes, accomodationTypes, rateRules, operations, implementsCombination, timeZone

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| [languages](#languages) | object |  |  |
| [currencies](#currencies) | object |  |  |
| [price](#price) | object |  |  |
| [nationalities](#nationalities) | object |  |  |
| [markets](#markets) | object |  |  |
| [paymentTypes](#paymenttypes) | object |  |  |
| [accomodationTypes](#accomodationtypes) | object |  |  |
| [rateRules](#raterules) | object |  |  |
| [operations](#operations) | object |  |  |
| [implementsCombination](#implementscombination) | object |  |  |
| [timeZone](#timezone) | object |  |  |

*****

## languages

#### Type: object

__add description to json file__

Required: all, includes, excludes, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| all | boolean |  |  |
| [description](#description) | undefined |  |  |
| includes | array |  |  |
| excludes | array |  |  |
| reviewDate | string |  |  |

*****

## includes:undefined

#### Type: undefined

__add description to json file__

*****

## excludes:undefined

#### Type: undefined

__add description to json file__

*****

## currencies

#### Type: object

__add description to json file__

Required: all, includes, excludes, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| all | boolean |  |  |
| includes | array |  |  |
| excludes | array |  |  |
| reviewDate | string |  |  |

*****

## price

#### Type: object

__add description to json file__

Required: binding, net, reviewDate, specified, reviewDate, specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| [binding](#binding) | object |  |  |
| [net](#net) | object |  |  |
| reviewDate | string |  |  |
| specified | string |  |  |

*****

## binding

#### Type: object

__add description to json file__

Required: specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## net

#### Type: object

__add description to json file__

Required: specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## nationalities

#### Type: object

__add description to json file__

Required: all, includes, excludes, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| all | boolean |  |  |
| includes | array |  |  |
| excludes | array |  |  |
| reviewDate | string |  |  |

*****

## markets

#### Type: object

__add description to json file__

Required: all, includes, excludes, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| all | boolean |  |  |
| includes | array |  |  |
| excludes | array |  |  |
| reviewDate | string |  |  |

*****

## paymentTypes

#### Type: object

__add description to json file__

Required: includes, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| includes | array |  |  |
| reviewDate | string |  |  |

*****

## accomodationTypes

#### Type: object

__add description to json file__

Required: includes, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| includes | array |  |  |
| reviewDate | string |  |  |

*****

## rateRules

#### Type: object

__add description to json file__

Required: includes, specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| includes | array |  |  |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## operations

#### Type: object

__add description to json file__

Required: search, quote, book, checkBookings, cancel

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| [search](#search) | object |  |  |
| [quote](#quote) | object |  |  |
| [book](#book) | object |  |  |
| [checkBookings](#checkbookings) | object |  |  |
| [cancel](#cancel) | object |  |  |

*****

## search

#### Type: object

__add description to json file__

Required: restrictions, optional, status

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| [restrictions](#restrictions) | object |  |  |
| [optional](#optional) | object |  |  |
| [status](#status) | object |  |  |

*****

## restrictions

#### Type: object

__add description to json file__

Required: destinations, stay, roomRestrictions, requiredAllPassengers, dateType, reference, reference

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| [destinations](#destinations) | object |  |  |
| [stay](#stay) | object |  |  |
| [roomRestrictions](#roomrestrictions) | object |  |  |
| [requiredAllPassengers](#requiredallpassengers) | object |  |  |
| [dateType](#datetype) | object |  |  |
| [reference](#reference) | object |  |  |

*****

## destinations

#### Type: object

__add description to json file__

Required: locations, hotels

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| [locations](#locations) | object |  |  |
| [hotels](#hotels) | object |  |  |

*****

## locations

#### Type: object

__add description to json file__

Required: max, recommended, sameCountry, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| max | integer |  |  |
| recommended | integer |  |  |
| sameCountry | boolean |  |  |
| reviewDate | string |  |  |

*****

## hotels

#### Type: object

__add description to json file__

Required: sameLocation, max, recommended, sameCountry, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| sameLocation | boolean |  |  |
| max | integer |  |  |
| recommended | integer |  |  |
| sameCountry | boolean |  |  |
| reviewDate | string |  |  |

*****

## stay

#### Type: object

__add description to json file__

Required: maxStay, minimumStay, release, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| maxStay | integer |  |  |
| minimumStay | integer |  |  |
| release | integer |  |  |
| reviewDate | string |  |  |

*****

## roomRestrictions

#### Type: object

__add description to json file__

Required: maxOccupancies, maxGuestsInAllRooms, requireSameGuestsInAllOccupancies, guestsInOccupancy, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| maxOccupancies | integer |  |  |
| maxGuestsInAllRooms | integer |  |  |
| [requireSameGuestsInAllOccupancies](#requiresameguestsinalloccupancies) | object |  |  |
| [guestsInOccupancy](#guestsinoccupancy) | object |  |  |
| reviewDate | string |  |  |

*****

## requireSameGuestsInAllOccupancies

#### Type: object

__add description to json file__

Required: samePaxNumber, samePaxAge, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| samePaxNumber | boolean |  |  |
| samePaxAge | boolean |  |  |
| reviewDate | string |  |  |

*****

## guestsInOccupancy

#### Type: object

__add description to json file__

Required: maxGuestsInOccupancy, guests, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| maxGuestsInOccupancy | integer |  |  |
| guests | array |  |  |
| reviewDate | string |  |  |

*****

## guests:undefined

#### Type: undefined

__add description to json file__

*****

## optional

#### Type: object

__add description to json file__

Required: hotel, rental, surcharges, remarks, cancelPolicyDescription, paymentInfo, hotelLocator, clientLocator, holder, hotelDetail, remarks, payable, hotelLocator, holder, hotelDetail, price, cancelPolicy, remarks, billingSellerCode, payable, cancelPrice, hotelLocator, holder, hotelDetail, price, cancelPolicy, remarks, billingSellerCode, payable, cancelPrice, cancelLocator, bookPrice, cancelPrice

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| [hotel](#hotel) | object |  |  |
| [rental](#rental) | object |  |  |
| [surcharges](#surcharges) | object |  |  |
| [remarks](#remarks) | object |  |  |
| [cancelPolicyDescription](#cancelpolicydescription) | object |  |  |
| [paymentInfo](#paymentinfo) | object |  |  |
| [hotelLocator](#hotellocator) | object |  |  |
| [clientLocator](#clientlocator) | object |  |  |
| [holder](#holder) | object |  |  |
| [hotelDetail](#hoteldetail) | object |  |  |
| [payable](#payable) | object |  |  |
| [price](#price) | object |  |  |
| [cancelPolicy](#cancelpolicy) | object |  |  |
| [billingSellerCode](#billingsellercode) | object |  |  |
| [cancelPrice](#cancelprice) | object |  |  |
| [cancelLocator](#cancellocator) | object |  |  |
| [bookPrice](#bookprice) | object |  |  |

*****

## hotel

#### Type: object

__add description to json file__

Required: surcharges, promotions, amenities, remarks, cancelPolicy, hotelName, hotelLocation, boardName, rooms

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| [surcharges](#surcharges) | object |  |  |
| [promotions](#promotions) | object |  |  |
| [amenities](#amenities) | object |  |  |
| [remarks](#remarks) | object |  |  |
| [cancelPolicy](#cancelpolicy) | object |  |  |
| [hotelName](#hotelname) | object |  |  |
| [hotelLocation](#hotellocation) | object |  |  |
| [boardName](#boardname) | object |  |  |
| [rooms](#rooms) | object |  |  |

*****

## surcharges

#### Type: object

__add description to json file__

Required: type, specified, reviewDate, specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| type | string |  |  |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## promotions

#### Type: object

__add description to json file__

Required: type, specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| type | string |  |  |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## amenities

#### Type: object

__add description to json file__

Required: type, specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| type | string |  |  |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## remarks

#### Type: object

__add description to json file__

Required: type, specified, reviewDate, specified, reviewDate, specified, reviewDate, specified, reviewDate, specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| type | string |  |  |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## cancelPolicy

#### Type: object

__add description to json file__

Required: type, specified, reviewDate, specified, reviewDate, specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| type | string |  |  |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## hotelName

#### Type: object

__add description to json file__

Required: specified, reviewDate, specified, reviewDate, specified, reviewDate, specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## hotelLocation

#### Type: object

__add description to json file__

Required: specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## boardName

#### Type: object

__add description to json file__

Required: specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## rooms

#### Type: object

__add description to json file__

Required: description, priceBreakdown, ratePlan, refundable, beds, units, specified, reviewDate, specified, reviewDate, specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| [description](#description) | object |  |  |
| [priceBreakdown](#pricebreakdown) | object |  |  |
| [ratePlan](#rateplan) | object |  |  |
| [refundable](#refundable) | object |  |  |
| [beds](#beds) | object |  |  |
| [units](#units) | object |  |  |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## description

#### Type: object

__add description to json file__

Required: specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## priceBreakdown

#### Type: object

__add description to json file__

Required: specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## ratePlan

#### Type: object

__add description to json file__

Required: specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## refundable

#### Type: object

__add description to json file__

Required: specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## beds

#### Type: object

__add description to json file__

Required: specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## units

#### Type: object

__add description to json file__

Required: specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## rental

#### Type: object

__add description to json file__

*****

## status

#### Type: object

__add description to json file__

Required: includes, reviewDate, includes, reviewDate, includes, reviewDate, includes, reviewDate, includes, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| includes | array |  |  |
| reviewDate | string |  |  |

*****

## quote

#### Type: object

__add description to json file__

Required: optional, status

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| [optional](#optional) | object |  |  |
| [status](#status) | object |  |  |

*****

## cancelPolicyDescription

#### Type: object

__add description to json file__

Required: specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## paymentInfo

#### Type: object

__add description to json file__

Required: specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## book

#### Type: object

__add description to json file__

Required: allowDeltaPrice, allowRemarks, restrictions, optional, status

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| [allowDeltaPrice](#allowdeltaprice) | object |  |  |
| [allowRemarks](#allowremarks) | object |  |  |
| [restrictions](#restrictions) | object |  |  |
| [optional](#optional) | object |  |  |
| [status](#status) | object |  |  |

*****

## allowDeltaPrice

#### Type: object

__add description to json file__

Required: value, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| value | boolean |  |  |
| reviewDate | string |  |  |

*****

## allowRemarks

#### Type: object

__add description to json file__

Required: value, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| value | boolean |  |  |
| reviewDate | string |  |  |

*****

## requiredAllPassengers

#### Type: object

__add description to json file__

Required: value, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| value | boolean |  |  |
| reviewDate | string |  |  |

*****

## hotelLocator

#### Type: object

__add description to json file__

Required: specified, reviewDate, specified, reviewDate, specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## clientLocator

#### Type: object

__add description to json file__

Required: specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## holder

#### Type: object

__add description to json file__

Required: specified, reviewDate, specified, reviewDate, specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## hotelDetail

#### Type: object

__add description to json file__

Required: bookingDate, dates, hotelCode, hotelName, boardCode, occupancies, rooms, bookingDate, dates, hotelCode, hotelName, boardCode, occupancies, rooms, bookingDate, dates, hotelCode, hotelName, boardCode, occupancies, rooms

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| [bookingDate](#bookingdate) | object |  |  |
| [dates](#dates) | object |  |  |
| [hotelCode](#hotelcode) | object |  |  |
| [hotelName](#hotelname) | object |  |  |
| [boardCode](#boardcode) | object |  |  |
| [occupancies](#occupancies) | object |  |  |
| [rooms](#rooms) | object |  |  |

*****

## bookingDate

#### Type: object

__add description to json file__

Required: specified, reviewDate, specified, reviewDate, specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## dates

#### Type: object

__add description to json file__

Required: specified, reviewDate, specified, reviewDate, specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## hotelCode

#### Type: object

__add description to json file__

Required: specified, reviewDate, specified, reviewDate, specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## boardCode

#### Type: object

__add description to json file__

Required: specified, reviewDate, specified, reviewDate, specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## occupancies

#### Type: object

__add description to json file__

Required: specified, reviewDate, specified, reviewDate, specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## payable

#### Type: object

__add description to json file__

Required: specified, reviewDate, specified, reviewDate, specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## checkBookings

#### Type: object

__add description to json file__

Required: byDate, byReference, status

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| [byDate](#bydate) | object |  |  |
| [byReference](#byreference) | object |  |  |
| [status](#status) | object |  |  |

*****

## byDate

#### Type: object

__add description to json file__

Required: implemented, restrictions, optional

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| [implemented](#implemented) | object |  |  |
| [restrictions](#restrictions) | object |  |  |
| [optional](#optional) | object |  |  |

*****

## implemented

#### Type: object

__add description to json file__

Required: value, reviewDate, value, reviewDate, value, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| value | boolean |  |  |
| reviewDate | string |  |  |

*****

## dateType

#### Type: object

__add description to json file__

Required: dateRangeType, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| dateRangeType | array |  |  |
| reviewDate | string |  |  |

*****

## dateRangeType:undefined

#### Type: undefined

__add description to json file__

*****

## billingSellerCode

#### Type: object

__add description to json file__

Required: specified, reviewDate, specified, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| specified | string |  |  |
| reviewDate | string |  |  |

*****

## cancelPrice

#### Type: object

__add description to json file__

Required: value, reviewDate, value, reviewDate, value, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| value | boolean |  |  |
| reviewDate | string |  |  |

*****

## byReference

#### Type: object

__add description to json file__

Required: implemented, restrictions, optional

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| [implemented](#implemented) | object |  |  |
| [restrictions](#restrictions) | object |  |  |
| [optional](#optional) | object |  |  |

*****

## reference

#### Type: object

__add description to json file__

Required: includes, reviewDate, includes, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| includes | array |  |  |
| reviewDate | string |  |  |

*****

## cancel

#### Type: object

__add description to json file__

Required: implemented, optional, restrictions, status

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| [implemented](#implemented) | object |  |  |
| [optional](#optional) | object |  |  |
| [restrictions](#restrictions) | object |  |  |
| [status](#status) | object |  |  |

*****

## cancelLocator

#### Type: object

__add description to json file__

Required: value, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| value | boolean |  |  |
| reviewDate | string |  |  |

*****

## bookPrice

#### Type: object

__add description to json file__

Required: value, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| value | boolean |  |  |
| reviewDate | string |  |  |

*****

## implementsCombination

#### Type: object

__add description to json file__

Required: value, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| value | boolean |  |  |
| reviewDate | string |  |  |

*****

## timeZone

#### Type: object

__add description to json file__

Required: timeZone, reviewDate

| Name    | Type    | Description | Example |
| ------- | ------- | ----------- | ------- |
| [timeZone](#timezone) | string |  |  |
| reviewDate | string |  |  |

*****
