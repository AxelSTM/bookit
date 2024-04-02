# Changelog (Free Version)

### 2.4.4

_October 25, 2023_

* **Fixed**: Minor bug fixes & security update

### 2.4.3

_August 7, 2023_

* **Fixed**: Minor bug fixes.

### 2.4.2

_August 4, 2023_

* **Fixed**: Resolved vulnerability based on a report from PatchStack

### 2.4.1&#x20;

_August 3, 2023_

* **Update**: The plugin is now compatible with WordPress 6.3

### 2.4.0

_July 5, 2023_

* **Fixed**: Minor bug fixes

### 2.3.9

_July 5, 2023_

* **Update:** Minor improvements

### 2.3.8

_June 13, 2023_

* **Fixed:** The "Authentication vulnerability" reported by Wordfence is fixed.

### 2.3.7

_May 31, 2023_

* **Fixed:** The authentication Bypass vulnerability is fixed.&#x20;
* **Fixed:** The demo import did not complete and returned a 500 error on the console

### 2.3.6

_May 12, 2023_

* **Fixed**: Minor bug fixes.

### 2.3.5&#x20;

_April 27, 2023_&#x20;

**Fixed:** Compatibility with PHP 8 to ensure appointments can be created successfully.

## 2.3.4

_January 12, 2023_

* **Fixed:** Deprecated functions of Elementor are replaced with actual ones.

## 2.3.3

_October 21, 2022_

* **Fix**: Minor bug fixes.



## 2.3.2

_September 9, 2022_

* **Fix**: Deprecated Elementor methods.
* **Fix**: Appointment Statuses PHP Error.

## 2.3.1

_August 25, 2022_

* **New:** Quick premium support button in WP dashboard (for applying the issue tickets) and personal support account creation.

## 2.3.0

_July 1, 2022_

* **Update:** Plugin Dashboard compatibility with **WordPress 6.0**
* **Fix:** Inappropriate load of graphical elements on **"Contact Us"** page

## 2.2.9

_1 Mar, 2022_

* **Update:** Security code optimization

## 2.2.8

_14 Feb, 2022_

* **Update:** Dashboard translations for static strings &#x20;
* **Fix:**  Bug with staff before loading the services for them
* **Fix:** Dashboard style errors are fixed
* **Fix:** AWS Loader Conflict Fix
* **Fix:**  issues with WordPress 5.9 compatibility

## 2.2.7

_9 Dec, 2021_

* **New:** Added new feature roadmap for Bookit
* **Update:** Freemius SDK 2.4.2 (Pro\*)
* **Fix:** Show minimal price in step-by-step Bookit form
* **Fix:** For the same price, remove the word From
* **Fix:** Not show "from' If price is equal for the staff

## 2.2.6

22 Oct, 2021

* **New:** Use WordPress time format for appointment time
* **Update**: Translations for step by step view, updated pot file
* **Fix**: Show client comment from appointment form
* **Fix**: Change appointment status from customer tab
* **Fix**: Send notification to admin email if it was changed from Settings
* **Fix:** Import Bookit data from file fixes

## 2.2.5

_2 Sep, 2021_

* **Fix**: Admin Dashboard notifications lag

## 2.2.4

_23 Aug, 2021_

* **Update**: Admin Dashboard notifications updated

## 2.2.3

_19 Aug, 2021_

* **New**: Close option for date and time blocks after selection (mobile devices)
* **Fix**: Shortcode logic issues ( correct data for fields depends on choosen values in admin ; frontend – set staff services and categories if staff ID in shortcode, etc.)
* **Fix**: Сonnect staff to google calendar button style (\*Google Calendar addon)
* **Fix**: Min height for appointment on dashboard
* **Fix**: Show day off by black color
* **Removed**: Hover/focus on inactive days
* **Removed**: All fonts from frontend

## 2.2.2

_16 Aug, 2021_

* **Update**: The WordPress user with Administrator role can not be connected to BookIt staff
* **Fix**: The ‘show currency symbol’ setting on service step for the step-by-step view

## 2.2.1

_12 Aug, 2021_

* **New**: Services that are not assigned to any Categories will not display in the booking calendar.
* **New**: Add to Calendar button added on the last step of appointment creation for Standard Calendar Template
* **New**: Admin Dashboard notification
* **Fix**: Step by step Calendar Template style fixes

## 2.2.0

_10 Aug, 2021_

* **New**: Step by step calendar template with six stages of making appointments: Category step; Date & Time step; Details step; Payment step; Confirmation step
* **New**: Categories without any Service will not be displayed on the appointment booking process
* **New**: Step by step calendar template is set by default for mobile devices
* **New**: Calendar templates section with Default and Step by step calendar templates
* **New**: Add to calendar button added on the last step of appointment creation
* **New**: ‘Clean all on delete’ option that deletes all database tables and plugin settings on plugin uninstallation
* **New**: Woocommerce custom title and custom icon for step by step calendar template (Pro)
* **Update**: Dashboard General Settings style updated

## 2.1.9

* **fixed**: Bookit Payments add-on deactivation issue

## 2.1.8

* **added**: Links to purchase add-ons on the landing page
* **fixed**: Bookit Payments add-on icon

## 2.1.7

* **new**: WordPress user roles for bookit staff and bookit customer
* **new**: Sender Name and Sender Email fields on Settings for changing default WordPress sender details in notification emails
* **added**: Staff assignment as a WordPress Users
* **added**: WPML translations for email templates
* **added**: Google Calendar add-on section on Settings
* **added**: New tab to buy add-ons in the free version of the plugin
* **added**: Confirmation email for appointments for Staff
* **fixed**: Style fixes in Appointments section
* **fixed**: Date/Time issue in Appointments section
* **fixed**: The Staff disappeared if service written in cyrillic

## 2.1.6

* **fixed**: CSRF issue fixed in appointment actions

## 2.1.5

* **added**: Feedback module inside BookIt settings
* **added**: Roadmap voting in BookIt settings
* **added**: New payment type “free” for free services

## 2.1.4

* **fixed**: Book appointment bugfix

## 2.1.3

* **added**: Two or more calendars on one page
* **added**: Notification alert if WooCommerce is not installed
* **added**: Create appointment from dashboard appointment list section
* **added**: Create appointment from dashboard calendar section by clicking on chosen date
* **added**: Create customer while creating an appointment in dashboard
* **added**: Customer autocomplete field while creating appointment in dashboard
* **added**: Notification alert before deleting staff, service, customer or category that shows all related data to the object that will be deleted
* **added**: Time slot duration setting
* **fixed**: Style issues in plugin dashboard
* **fixed**: Style issues on service list and booking form
* **fixed**: Use staff price while creating or editing appointment
* **fixed**: Appointment creation after dynamic authorization
* **fixed**: Edit appointment without staff
* **fixed**: Custom price for each staff
* **fixed**: Show error if service time is not available
* **fixed**: Edit/Create appointment blocked open accordion
* **fixed**: Check is email exist before create customer
* **updated**: Database structure changed – payments tables separated from appointment table

## 2.1.2

* **fixed**: Styles for calendar week view

## 2.1.1

* **added**: Calendar views added ( Day, Week, Month )
* **added**: ‘customer\_phone’ and ‘customer\_email’ in email templates settings
* **fixed**: Demo import data updated
* **fixed**: Ability for editing appointments created for the staff member that was deleted
* **updated**: Currency list
* **updated**: Phone validation , minimum 8 symbols
* **updated**: Appointment creation for a free service
* **updated**: While delete customer save customer info for appointment

## 2.1.0

* **updated**: Default time slot range set to 15 minutes
* **updated**: Correct time slots for staff members
* **added**: Show new phone in appointments If user logged in and input new phone in the booking form
* **added**: New notification when changing service duration – “Changing of the service duration will not affect the existing appointments and will be applied only to new appointments”
* **added**: ‘Delete appointment’ button
* **added**: Notification email settings for deleted appointments
* **added:** Email template for “Delete appointment” notification
* **updated**: ‘Update appointment’ button, update appointment status, payment status and other fields
* **fixed**: Date input for Chrome
* **removed**: Autofill working hours end time and breaks for staff members
* **fixed**: Inability to create free service
* **fixed**: Style issues on category/service slider

## 2.0.9

* **fixed**: Scrollbar for booking details modal window on small screens
* **fixed**: The booking form doesn’t work if no active payment methods set
* **added**: Validation for add category form
* **added**: Validation for staff form
* **added**: Validation for services form
* **added**: Validation for customer form
* **fixed**: Bottom scrollbar appearance
* **fixed**: View full letters inside the input fields
* **fixed**: Border appearance on active field
* **fixed**: Rows height in booking details modal
* **updated**: Demo import data updated
* **added**: Icon for export JSON on Settings page -> import/export tab
* **fixed**: Buttons alignment on Settings page -> import/export tab
* **fixed**: Special symbols for the translation
* **fixed**: ‘Day Off’ value saved incorrectly 00:00:00 instead of Null while adding and updating working hours
* **fixed**: Arrows appearance for service scrolling
* **fixed**: Last service elements appearance from the list
* **added**: Hide services that have no staff assigned to it
* **fixed**: Show correct tab on settings page after page refresh
* **added**: Show selected file on import JSON with styles
* **added**: Error messages from the server if import JSON or import demo returned error
* **fixed**: Select file button pseudo-element style
* **updated**: Currency in main settings now applied for all payment types (autocomplete by name and currency code, can choose by buttons)
* **added**: Bookit form validation for user “book appointment”
  * check the full name ( from 3 – 25 letters)
  * check phone if exist
  * check email (email is required if booking type = registered\_user)
  * check is exist phone or email if booking\_type = guest
  * check password and password confirmation fields if booking\_type = registered user
* **fixed**: Styles for icons on the calendar on hover for small screens
* **fixed**: Text alert style for redirect URL info
* **added**: Security features

## 2.0.8

* **added**: Stripe Strong Customer Authentication (3D Secure)

## 2.0.7

* **fixed**: Copyright text removed

## 2.0.6

* **fixed**: Copyright disabled for Pro Plugin

## 2.0.5

* **added**: Plugin Copyright
* **added**: Import / Export feature
* **fixed**: Print Appointment Confirmation bug

## 2.0.4

* **added**: Stylemix announcements in admin dashboard

## 2.0.2

* **fixed**: Guest Booking bug

## 2.0.1

* **added**: Icon field added to Services
* **fixed**: Trimming titles issue

## 2.0.0

* Plugin Refactoring

## 1.2.2

* Minor bug fixes

## 1.1

* Minor bug fixes

## 1.0.3

* Minor bug fixes

## 1.0.2

* Features improved

## 1.0.1

* Minor bug fixes

## 1.0

* First Version of Plugin
