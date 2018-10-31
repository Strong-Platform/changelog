# Changelog

## 0.5.5 (October 31, 2018)

* added initial Coupon report

## 0.5.4 (October 22, 2018)

### Seach Improvements
* search by a customer's email address was not working, that is fixed
* search was always doing OR which was leading to too many results, default to AND

## 0.5.3 (October 18, 2018)

### Style Updates
* small changes to navigation, capsules and login
* logout as off-canvas sidebar

## 0.5.2 (October 18, 2018)

### Customer Manager
* [Redesign edit view](https://s3.amazonaws.com/strong-platform-public/customer-manager.gif)
* Enable edit
* Enable update password

## 0.5.1 (October 16, 2018)

### Reports

* Added Marketing Campaigns
* Added Abandoned Orders

## 0.5.0 (October 16, 2018)

### Subscription Manager Updates

* Improved the ability to search
* Added column showing `cancelled_date`
* Allows sorting of columns
* Fix small style regression on sortable table headings
* Don't show `next_shipping_date` or `next_charge_date` when those fields are blank

### Reports

* Updated architecture of reports in general
* Added Subscription Churn Rate

### Search Indexing

* customers, subscriptions and orders now show first and last name
