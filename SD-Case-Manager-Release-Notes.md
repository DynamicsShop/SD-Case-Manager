## SD Case Manager Releases

### 6.2.0

#### Enhancements

- AppSource App - When choosing the Open In Browser action from the Email Inbox Archive, the email is opened in the logged in users email box. If the Queue Email Address on the Email Inboxes is different to the logged in users email, the email cannot be found. However, you can open the email by choosing the new Download Email File action, which downloads the email, and when the downloaded email file is opened, the user can reply to the email from their email box. 

- AppSource App - Functionality was added in the SD Case Manager Email Inbox Pending and SD Case Manager Email Inbox Archive to include the email trail when replying to emails using the Email Templates. 

- AppSource App - A change was made to the HTML Editor to auto insert a hyperlink in the outgoing email if the placeholder field on the Email Template has a URL structure.

- AppSource App - The existing Email Inbox interface was replaced with a new interface and add two extra functions were added ReplyTo and GetEmailMimeContent.

- AppSource App - When creating a Case using the New Case action, surfaced on the Customer Card, Vendor Card, Item Card, Posted Sales Invoice, Posted Purchase Credit Memo, Posted Purchase Invoice and Posted Sales Credit Memo, a link to the record from where the Case was created is auto inserted on the Case. The link from the record where the Case is created is also auto inserted if the New Case action was surfaced on a page using the SD Case Manager Extension Wizard.

- AppSource App - When creating a new Case, all fields on the Case Card are now initially non-editable until the Queue Code is selected.

#### Bug Fixes

- AppSource App - An issue was fixed where if a Customer No was not specified on the Case, and a Contact was chosen as the Reporter, the Customer No. was populated with the Customer associated with the Contact but the selected Contact was not placed in the Contacts List. The Customer No is no longer auto populated on the CardPage from the Contact chosen on the ListPart.

### 6.1.0

#### Enhancements

- AppSource App - A new Licence Install and Setup Wizard was created.

- AppSource App - The notification to activate the app, displayed on fresh install of SD Case Manager, was added to the standard Business Central role centres.

- AppSource App - Changes were made to the Manage Subscriptions page.

- AppSource App - The Lead Subscription Link from the Request Subscription action in the Product Activation page was updated.

- AppSource App - A new action was added to the Setup Card called View Our Apps. This action opens a page on AppSource pointing to all our Simply Dynamics Ltd apps.

- AppSource App - A minor change was made to the About page.

- AppSource App - A minor change to the Product Activation page.

### 6.0.0

#### Enhancements

- AppSource App - Project Codes were added to Queues and Cases.

- AppSource App - A change was made to allow for a selection of a customer at case level to filter down the Project Code and the Reporter lookup.

- AppSource App - The Managed By field was surfaced on the Category list part page.

- AppSource App - A new field, External Case Reference, was added to the Case Card.

- AppSource App - Functionality was added to set default case watchers on the customer card and populate the Case Card with these watchers when a Case is logged for the customer. 

- AppSource App - Templates can now be specified at Sub-Category Level.

- AppSource App - A change was made to the colour coding on the action comments. The Action Code and not the Summary is now added as the comment header.

#### Bug Fixes

- AppSource App - Setting the Managed By field on a Category Card raises an error when the Category is chosen in a Case. This was fixed.

### 5.0.2

#### Enhancements

- AppSource App - An Escalation From Email Address field was added to the SD Case Manager Setup card to use for Email Escalations when the Email Service is Email API.

- AppSource App - A change was made to display the contents of the HTML control when the Case Action is in view mode.

### 5.0.1

#### Enhancements

- AppSource App - A change was made to the licence expiry notification. The logic for checking for expiry dates was reworked.

- AppSource App - AppSource App - An Error Message is raised for users using Graph API to monitor email inboxes or to send emails to let users know when the Graph API token has expired.

- AppSource App - Enhancements were made to the App Request Subscription page.

- AppSource App - Additional phrases were added as search phrases for the SD Case Manager pages.

- AppSource App - ToolTips were updated in the About, Product Activation, and Tenant Subscription pages.

### 5.0.0

#### Enhancements

- AppSource App - New functionality was added to allow users to log a Case from an email. A mail box can be monitored at Queue level. When creating a Case, the Contact on the Case is determined by looking at the email. A new Contact can easily be created when logging the new Case. 

- AppSource App - New functionality was added to read a mail box to update Cases. Emails related to existing cases are matched and automatically moved to the Email Archive table. The search phrase in the subject line parsing used to find cases in the monitored Email Inboxes is a case sensitive search phrase. Punctuation characters such as commas and full stops are ignored in the Subject Line Parsing phrase.  

- AppSource App - Functionality was added to allow users manually link an email from the monitored Inbox to an existing Case. 

- AppSource App - New fields to allow for creating a Case from incoming mails were added to the Setup Card. A field was added to the Setup Card to allow users specify when to delete records from the Email Archive. Functionality was added to delete the Archive records when the Delete Archive action in the Setup Card is selected. Various other UI changes were made to FastTabs, field placement and tooltips in the SD Case Manager Setup Card. 

- AppSource App - Functionality was added to the SD Case Manager Job Queue Card to add a Job for email inbox scanning. The SD Case Manager Job Queue Card was also modified to allow for easier setup of creating jobs for executing escalation rules and email inbox scanning. 

- AppSource App - New tables, pages and codeunits were added to create custom Email Templates which can contain variable placeholder data in the Email Subject and Body. Placeholder data is taken from the Case, the Queue Card and from the Case Actions. The Email Templates are used to send customised emails from the Case Card. An option was added to the Email Templates to attach the Case Report when the mail is sent.  Emails can be sent from Cases by opening a dialog box where you can select a Template Email to send an email. A lookup to the Status field was added to the Email Templates so the list of Email Templates can be filtered according to the current Case Status.

- AppSource App - Functionality was added to easily copy Email Templates for ease of setup. 

- AppSource App - A new TimeLine FactBox for a Case was created. Ticket created, status changes, assigning actions, changing the priority on a case, and emails sent or received are recorded to the TimeLine FactBox. The events in the Case Timeline are ordered in descending order.  

- AppSource App - A new improved and optimised HTML editor used in the Comments section of a Case Action was added to SD Case Manager. 

- AppSource App - An SD Case Manager Linked Cases FactBox that shows a count of Open Cases, Hold Cases and Closed Cases for the linked record was created and surfaced on the Customer Card, Item Card, Vendor Card, Posted Sales Invoice, Posted Purchase Credit Memo, Posted Purchase Invoice, and the Posted Sales Credit Memo. 

- AppSource App - Functionality was created to allow users surface the Create Case action and the SD Case Manager Linked Cases FactBox to cards and lists by creating and publishing an extension app directly from SD Case Manager. This functionality is accessed via the SD Case Manager Extension Setup Card or by choosing the SD Case Manager Extension Setup wizard from the SD Case Manager Setup Card.

- AppSource App - A change was made to allow a case link to be created for an end of life document even if the Case has been marked as closed. 

- AppSource App - The UI and Setup in SD Case Manager was reviewed and streamlined. All pages were reviewed for UI improvements.

- AppSource App - Various changes were made to the Case Card. Changes were made to FastTabs, field placement and tooltips in the Case Card. A View Comments action was added. Also, users can now send emails from the Case Card using Email Templates.

- AppSource App - A number of changes were made to the Case List. The order of the columns was changed and a freeze frame was added. The Type on the Contacts flowfield was removed and all Case Contacts are now showing here and in the Case Contacts FactBox.  

- AppSource App - Some UI changes were made to the Case Details FactBox. A count of the Open Cases for the case contact was added to the FactBox. 

- AppSource App - A freeze frame was added to the Case Actions list. 

- AppSource App - UI changes were made to the Action Types list. New fields to set comment colours for the different action type comments were added. These colours are displayed when the user chooses the View Comments action in the Case Card. 

- AppSource App - Changes were made to the Case Details FactBox. The Watchers field filters to a Contact Role Type of Watcher and some field captions were updated.

- AppSource App - The UI in the Role Centre was streamlined and new cues were created. Duplicate actions were removed and a new action to the Case Templates was surfaced.

- AppSource App - The SD Case Manager Notifications list was added to the Case Manager User Role Centre.

- AppSource App - The Assisted Setup demo data was reviewed and simplified.

- AppSource App - A change was made to the import of Assisted Data Setup to cater for enum type fields.  
   
- AppSource App - The logo in App was updated to the new logo. 

- AppSource App - The links in the About Page were updated.

### 4.0.1

#### Enhancements

- AppSource App - A change was made to limit the SD ISV Tenant Subscriptions page to display just our SD ISV AppSource Apps and not other SD PTE Apps.

#### Bug Fixes

- AppSource App - A change was made to the ISV Licence Notification procedure in SD Case Manager to fix an issue that would raise an error when the language is changed from English to another language.

- AppSource App - An error will raise in the Assisted Setup import if non sequential enum values exist in the imported data. This was fixed.

- AppSource App - When selecting SD Case Manager activity pages in the Tell Me/Search in a BCv22 environment, the activity pages were hanging.

### 4.0.0

#### Enhancements

- BCv21 App - To allow for greater ease of use, SD Case Manager contains significant changes to the structure of Case Manager, Case Report and Case Watchers on the Case Card. The Watchers table has been renamed to Case Contacts and the Role of a Case Contact can be Manager, Reporter or Watcher. The Case Contact details can come from User Setup, Contact List or Manual Entry. 

- BCv21 App - Upgrade code was created for upgrade of prior versions of SD Case Manager to v4.0.0 and above. 

- BCv21 App - The concept of Analysis Codes was removed from the App to streamline the App and allow for greater ease of use. 

- BCv21 App - Changes were made to the Default Case Watchers on the Queue Card to reflect the changes made to the Case Contacts in the Case Card. 

- BCv21 App - Upgrade code was written for the changes to the structure for the Default Case Watchers on the Queue Card. 

- BCv21 App - Functionality was added to allow the option to track due date changes on Case Actions and to add due dates to be updated based on a rule. 

- BCv21 App - A drilldown to the action due date change log was surfaced on the Action Lines in the Case Card.  

- BCv21 App - The Case Action Due Date was surfaced on the Actions List in the Case Card. 

- BCv21 App - New functionality was added to allow for handling of Case Action record links to end-of-life transactions for Purchase Orders/Credit Memos to Posted Invoices/Posted Credit Memos; Sales Quotes to Orders/Posted Invoices; and Sales Orders/Credit Memos to Posted Invoices/Posted Credit Memos. Users can choose to Modify, Add, Delete or leave the record link as is on the Case Action.  

- BCv21 App - A new Copy Template action was added to the Template List and Template Card.  

- BCv21 App - The Create New Case action was surfaced on the following standard Microsoft Dynamics 365 Business Central pages - Customer, Vendor, Item, Posted Purchase Invoice, Posted Purchase Credit Memo, Posted Sales Invoice and Posted Sales Credit Memo. 

- BCv21 App - A change was made to the notification created for assigned users when escalations were run to add the user to the notification text. 

- BCv221 App - The Case Report now shows the duration of time that it took from creation to completion of the action. 

- BCv21 App - A field was surfaced on the Case Report to show the Case Links. 

- BCv21 App - Added a check to the code that a Manager on a Case can only have a Source of User. 

- BCv21 App - In the SD Case Manager Setup, the Contact No. was updated to Reporter. The message displayed in the Case Card if the Reporter is a required field on a Case was also updated. 

- BCv21 App - Changes were made to the escalations for emailing Watchers and User Watchers. To email a Watcher, the Contact Role on the Case has to be set to Watcher and the Contact Source is Manual or Contact. To email a User Watcher, the Contact Role on the Case has to be set to Watcher and the Contact Source is User. 

- BCv21 App - A minor change was made to the Case Card to reorder some fields in the General FastTab. 

- BCv21 App - Some fields on the Queue Card were promoted to the FastTabs. 

- BCv21 App - Some fields on the Setup Card were promoted to the FastTabs. 

- BCv21 App - The latest ISV licence controller was added to the App. 

- BCv21 App - The licence expiry and licence expired notification was surfaced on the Case List page. 

- BCv21 App - The message displayed when choosing Assisted Setup to import  Demo Data was changed. 

- BCv21 App - A page was created to display all the installed Simply Dynamics Apps and subscription details for the tenant. 

- BCv21 App - The Licence Message displayed on first install of SD Case Manager was changed to prompt the user to activate a free trial and to choose Assisted Setup from the Setup Card to create demo data. 

- BCv21 App - Add an Alert Notification in the SD Case Manager Role Centre and Activity pages to show users that they need to activate the licence. 

- BCv21 App - The SD Case Manager licence expiry message/notification was updated to show the App Name. 

- BCv21 App - The permission set xml file was replaced with permission AL objects. 

- BCv21 App - The links in the About page were updated to point to our new web site.

- BCv21 App - ToolTips were updated to point to our new website. 

- BCv21 App - Captions on Actions were updated so they will be translatable if needed. 

- BCv21 App - The Product Activation page was updated to point to the new CRM URL. 

#### Bug Fixes

- Bcv21 App - Fixed an issue where when deleting a Case the prompt on mandatory Case fields missing was being raised. 

- BCv21 App - A fix was made to the Inactive Open Cases flowfield in the Sub Categories FastTab in the Categories Card. 

- BCv21 App - Fixed the flowfield count for Inactive Open Cases in the Categories FastTab on the Queue Card. 

- BCv21 App - Fixed an issue when drilling into the All Open Cases cue in the SD Case Manager Role Centre raised an error when a notification existed for a Case in another Company. 

- BCv21 App - A fix was made to the Case Card where the Case Contacts record was syncing the Contact back to the Case this happened during restructuring of the new Case Contact table. 

- BCv21 App - Fixed an issue where users could open the Case Card when the SD Case Manager was not activated but were then unable to close the Case Card as the licence check was firing.  

- BCv21 App - A fix was made to the code for licence key checks on the SD Case Manager Role Centres. 

- BCv21 App - Fix to an intermittent error raised when opening the Escalation Card. 

- BCv21 App - The ping pong on the Case Card was removed as Business Central raises a message on the case card when the ping pong is called. 

### 3.0.7

#### Enhancements

- BCv19 App - Added the Latest Version of the product and the AppSource URL to the About Page. 

- BCv19 App - Added the Latest ISV Licence Control with fix to Free Trials in Public Environments. 

### 3.0.6.1

#### Enhancements

- BCv14 App - To allow for greater ease of use the Case Manager, Case Reporter and Case Watchers were merged into a new single table. Case Contacts are defined as Manager, Reporter or Watcher. This change was made to the BCv14 App v3.0.6 code base only and released as v3.0.6.1 

- BCv14 App - Functionality was added to allow the option to track due date changes on Case Actions and to add due dates to be updated based on a rule. This change was made to the BCv14 App v3.0.6 code base only and released as v3.0.6.1 

- BCv14 App - The concept of Analysis Codes was removed from the App to streamline the App and allow for greater ease of use. This change was made to the BCv14 App v3.0.6 code base only and released as v3.0.6.1 

- BCv14 App - A drilldown to the action due date change log was surfaced on the Action Lines in the Case Card. This change was made to the BCv14 App v3.0.6 code base only and released as v3.0.6.1 

- BCv14 App - The Case Action Due Date was surfaced on the Actions List in the Case Card. This change was made to the BCv14 App v3.0.6 code base only and released as v3.0.6.1 

#### Bug Fixes

- BCv14 App - The notifications were not being displayed correctly in the Notes attached to the Case Card. This change was made to the BCv14 App v3.0.6 code base only and released as v3.0.6.1 

- BCv14 App - The notifications were not being created when the escalations were run. This change was made to the BCv14 App v3.0.6 code base only and released as v3.0.6.1 

### 3.0.6

#### Enhancements

- BCv17 App - The code was updated to use the latest standard smtp emailing functionality in D365 which has been moved to a separate App. 

- BCv14 App - Backported the latest BCv17 App to BCv14 and added the latest ISV Licence Controller to the BCv14 Build.

#### Bug Fixes

- BCv17 App - A fix was made to an error "The Email Item table is empty." that was raised on execution of escalation rules.

### 3.0.5

#### Enhancements

- BCv17 App - Made a change to default the Escalations Card to editable when opened.

- BCv17 App - Users are prevented from creating Queues if the Licence is not valid or has expired.

- BCv17 App - The Application Area property was set on the Role Centre Activity pages.

- BCv17 App - To aid user input the Escalation Description field on the Escalation line is marked as mandatory.

- BCv17 App - Made a change to the Assisted Setup Import to recognise the duration datatype used in escalations.

- BCv17 App - Edit, View and New Actions were removed from the Template Card.

- BCv17 App - Edit, View and New Actions were removed from the Escalation List in the Queue Card.

- BCv17 App - In the Queue Card the Report Actions were set to Promoted only.

- BCv17 App - The Sub Categories list page was missing the Manage menu group.

- BCv17 App - In the Case Actions list, the menu groupings were re-ordered.

- BCv17 App - The Activity Panels from the Role Centre can now be searched for using the Tell Me.

- BCv17 App - The captions of the SD Case Manager objects were changed to be more user descriptive in the Tell Me.

- BCv17 App - The New Action in the Case Interactions and the Actions Interactions FactBoxes were removed. 

- BCv17 App - Changes were made to the SD Case Manager Role Display Names.

- BCv17 App - Description length of Statuses and other Case Manager description fields were increased in length as per standard D365BC.

- BCv17 App - Changes were made to the Case Card to replicate how standard D365BC behaves if default no.s are set to yes on a no. series. 

- BCv17 App - A change was made to the caption of the Setup Card.

- BCv17 App - The Action menu groups on the Setup Card were updated.

- BCv17 App - Changes were made to the layout of the Activity Groups in the SD Case Manager Role Centres.

- BCv17 App - Changes were made to the object captions as they appear in the Tell Me. 

- BCv17 App - The caption of the SD Case Manager reports were changed.

- BCv17 App - Changes were made to the Names of the SD Case Manager Permission Sets.

- BCv17 App - A change was made to the prompt on Activating the Free Trial Licence.

- BCv17 App - The SD Case Manager Role Centre Display Names were updated.

- BCv17 App - Visual changes were made to the SD Case Manager Manager Role Centre.

- BCv17 App - Visual changes were made to the SD Case Manager User Role Centre.

- BCv17 App - SD Case Manager Permission sets were created.

- BCv17 App - The Usage Category was updated for SD Case Manager pages for the Tell Me search. 

- BCv17 App - Visual changes were made to the SD Case Manager About Page. 

- BCv17 App - A number of visual changes were made to the SD Case Manager Setup Card. 

- BCv17 App - Functionality was created for our Assisted Setup process.

- BCv17 App - The Licencing Control Feature was added to SD Case Manager.

- BCv17 App - The HTML Editor was updated.

- BCv17 App - Certain SD Case Manager pages were removed from the extension to the Sales Order Processor Role Centre.

- BCv17 App - Recoded existing code to allow users send emails with attachments from SD Case Manager.

- BCv17 App - Name and Description fields were updated from 50 to 100 characters as per standard D365BC change.

#### Bug Fixes

- BCv17 App - An issue was fixed where, if a Case Manager No. Series was not setup in the Setup Card then, when creating a Case, the page hangs and becomes unresponsive.

- BCv17 App - The sub categories field in the Queue Card did not have a New Line Action. 

- BCv17 App - The case status field in the Queue Card did not have a New Line Action. 

- BCv17 App - Fixed an issue where notifications were not being created when the escalations were run.

- BCv17 App - Fixed an issue where Escalations were not working.

- BCv17 App - Made a fix to remove the Contact E-Mail or the Contact Phone from the Case Card when the Contact No. is removed.

- BCv17 App - The Edit, View and New Actions on Queue Category listpage were removed.

- BCv17 App - The Case Action Card was missing some menu items.

- BCv17 App - An issue was fixed where the New Line Action on the Actions FastTab of the Escalation Card was not behaving correctly.

- BCv17 App - Fixed an issue where a Case was not updated as closed when all Case Actions were closed.

- BCv17 App - An issue was fixed on the Case Card where removing a Contact No from a Case Card raised an error.

- BCv17 App - Issues were fixed that were raised when creating an escalation rule on a Queue Card - users could open a Card for a blank escalation line.

- BCv17 App - The View and Edit Actions were showing twice in the Case Card on the Actions FastTab.

- BCv17 App - Fixed an issue where an error was raised on creation of a Case.

- BCv17 App - Actions on the Case Action Card menu were not displaying. 

- BCv17 App - The Actions Cues in the Role Centre weren't calculating the flowfield counts on the cues correctly. 

- BCv17 App - In the Case Card, the Actions list page was missing a New Line Action on the Actions FastTab.

- BCv17 App -  The Date Format Error that was appearing on opening the Setup Card prior to activating the Free Trial Licence was fixed.

- BCv17 App - The issue with creating attachments on Case Actions was fixed.

### 3.0.4

#### Enhancements

- BCv14 Public App - Made a change to update the WriteMode property to allow emailing of a Case Contact.

- BCv14 Public App - A change was made to the Escalation Card to place the list pages on FastTabs that could be expanded and collapsed.

- BCv14 Public App - A change was made to the Category Card to place the list pages on FastTabs that could be expanded and collapsed.

- BCv14 Public App - A change was made to the Case Card to place the list pages on FastTabs that could be expanded and collapsed.

- BCv14 Public App - A change was made to the Queue Card to place the list pages on FastTabs that could be expanded and collapsed.

- BCv14 Public App - Activity Groups from the SD Case Manger Role Centre were surfaced on the Order Processor Role Centre and the Purchasing Agent Role Centre.

- BCv14 Public App - Updated the usage category on pages so that SD Case Manager pages can be found when searching in the Tell Me.

- BCv14 Public App - Actions with icons were added to the Role Centre.

- BCv14 Public App - The code base was converted from C/AL to AL extensions.

- BCv14 Public App - Licensing control was added to SD Case Manager.

- BCv14 Public App - The HTML Editor was converted to Javascript.

- BCv14 Public App - Code in SD Case Manager that had used Ping Pong was re-written.

- BCv14 Public App - The SD Case Manager chart codeunits were removed from the code base.

#### Bug Fixes

- BCv14 Public App - Fixed an issue where an error was raised when emailing a Case Contact from a Case Card as the code was taking the User ID email address from the SMTP Setup and not the Case Manager Setup Card.

- BCv14 Public App - Our Simply Dynamics charts were removed from SD Case Manager.

- Fixed an issue raised on closing a Case's Action in a filtered list of Actions where a comment was also stamped on another action.

- Fixed an issue where the Edit and View Actions were shown twice on the Actions FastTab in the Case Card.

- Fixed an issue raised on creation of a new Case if only one Queue Code has been set up in SD Case Manager.

- Fixed an issue where the Case Number was re-numbered when the mandatory fields were filled in.

- Fixed an issue where if a mandatory field was entered and then blanked out on a Case, a user could navigate to the next page or close the page without entering the mandatory field.

- Fixed an issue where an error was raised when a Case was opened from the Open Cases List on the Role Centre.

### 3.0.3

#### Enhancements

- Made a change to update the Case Status on the Case Card when the user is prompted to close a Case.

- Created functionality to allow users to take a photo and embed the photo in the Case Action html comment area when creating Case Actions on a mobile device .

- Created a new mobile device specific page for creating Case Actions and created functionality to direct mobile users to use this page for optimum rendering of the Case Action.

#### Bug Fixes

- Fixed an issue where updating the Status on the Case Card to a closed status was raising an unexpected validation error.

- Fixed an issue where closing a Case was raising an intermittent error.

- Fixed an issue where the Assign to Me Action on the Case Card was disabled when creating a new Case.

### 3.0.2

#### Enhancements

- Made a change that when the Queue Code is changed on a Case Card, that the Category Code and the Sub-Category Codes are re-validated.

- Changed the default answer from yes to no on the message raised when Queue Code/Category is changed on the Case Card.

- Added functionality to prevent the user from navigating to a different Case and by-passing the check for mandatory fields.

- Moved the placement of the Summary field on the Case FactBox and the Case Action FactBox.

- Moved the Simply Dynamics About Action on the Setup Card to the General group on the Ribbon.

- Changed the wording of the message displayed to users on change of the Queue Code on a Case Card.

- Surfaced the KPIs for the Case Sub Category on the SD-CSM Queue Sub Category List.

- Added the Case Summary field to the Case FactBox and the Action Summary field to the Case Action FactBox.

- Added the Case FactBox to the Case Action List and to the Case Action Card.

- Added KPIs for Case Categories and Case Sub Category and surfaced same on the associated pages.

- Added a new mandatory checkbox list to the Case Manager Setup Card to flag the field to be tested before exit on a newly created Case.

- The Simply Dynamics About Action was added to the SD Case Manager Setup Card.

- Created new functionality on the Template Card to allow a Default Assigned User to be assigned to the Template Actions.

- Made a change to prompt/ask the user, on change of the Queue Code in the Case Card, to confirm whether to delete all the existing Actions and Watchers on the Case or to append new Actions and Watchers to the Case.

#### Bug Fixes

- Fixed an issue where users were unable to navigate to the next or previous record in the Case Card with the introduction of the test fields on the Setup Card.

- Fixed an issue where drilling down on the Case No. FlowField on the Case Action FactBox in NAV 2018 launched a lookup page rather than launching the Case Card.

- Fixed an issue in NAV2018 where new Actions couldn't be added to a Template when editing the Template in the Template Card.

- Fixed an issue where on input of a Case Action, changes were reverted if the Attach File action, New Link action or Log Interaction action was selected when inputting text in the HTML Editor.

### 3.0.1

#### Enhancements

- A new communication method table was added to log how a Case was received and to record the preferred communication method for Watchers.

### 3.0.0

#### Enhancements

- In the 2013R2 Build, the Case Report Email attachment pdf name didn't reflect the Case Number.

- In the 2013R2 build, on input of a Template Action, the text in the HTML Editor is reverted if the Completed Action was chosen when inputting text into the HTML Editor.

- In the 2013R2 Build, there was a compile error in the SD-CSM Management Codeunit in ref to File Management Codeunit when tested on non W1 environment.

- In the 2013R2 Build, the Actions List Page contained an extra action called "Home" that duplicated the "New Link" functionality.

- A change was made to the 2013R2 Build. In the Case Card choosing to Email Case Contact will display a message for SMTP or open Outlook as NAV 2013R2 doesn't have the Email dialog functionality of later NAV versions.

- In the NAV 2013R2 build, the New, Edit, and View actions were not displayed in the SD-CSM Queue Escalation LP.

- Created a 2013R2 release (backported from current release).

- Updated the charts from standard NAV charts to the Simply Dynamics Chart control.

- Updated the About Page.

- Fixed an issue where on input of a Template Action, the text in the HTML Editor was reverted if the Attach File Action was chosen when inputting text into the HTML Editor.

- Created new sample setup xml files.

- Added the Simply Dynamics Import/Export module to SD Case Manager.

- Removed the standard NAV OneNote, Notes, and Links from the SD Case Manager Setup Pages.

- Created a new installer for the Simply Dynamics control add-ins used in SD Case Manager.

- The Activity Cues on the Role Centres were split out into individual pages.

- Refactored the objects to Simply Dynamics.

- A W1 release of SD Case Manager was created.

- Renamed the Analysis codes Action on the Setup Page to Analysis Codes.

#### Bug Fixes

- Fixed an issue where the default export filename and manifest header were set to the wrong product id when exporting the Setup data from SD Case Manager..

- Fixed a compile error in the Template Action Card.

- Fixed an issue where an error was raised on close of the page when reviewing a completed Action.

### 2.1.0

#### Enhancements

- Created functionality to define a Queue Default Watchers table and assign at Queue Level for Email and User Watchers. Entries in this table are automatically added to a case for the Queue.
- Displayed the Case Number in the My Open Cases List Pages.
- In the SD-CSM Case Card, if there is a contact email specified on the Case Card, when the Email Case Contact Action is chosen, default the Contact Email into the To: field of the Send Email Card.
- SD-CSM Queue Report, on the Case Lines, show the Total Cost (LCY) for each case within the Queue. Added a Report Total for Total Cost (LCY).
- In the Case Card, Reporter FastTab, horizontally aligned the Contact Company Name to the Contact Company No.
- Removed the Setup Action and the Execute Escalation Rules Action from the SD-CSM User Role Centre.
- Refactored XMLPorts Element Names.
- Updated the Readme.txt file.

### 2.0.1

#### Bug Fixes

- Fixed a bug in SD-CSM Queue Category List Page where selecting page from the Role Centre's Navigation Pane allowed users to create a Category not linked to a Queue. 
- Fixed an issue where in the Category Card on creation of a Case the Managed By on the Case was set to the current USERID. 
- Fixed an issue where in the Time charts for the Cases per Queue, Cases per User, Case Open Vs Close, the flowfield was based on the create date and was not taking the closed date into account. 
- Fixed an issue where importing the Demo Setup.xml raised an error. 
- Fixed an issue where importing the Cases Setup.xml raised an error. 
- Fixed a bug in the SD-CSM Action Type table whereby renaming the Code did not update Cases that had the old Action Code. 
- Fixed a bug in the SD Case Card, Reporter Fast Tab. If a Person Contact was selected and then changed to a Company Contact and back to a Person Contact, the Company No. and Company Name were not being set to blank. 
- Added the Case Summary field to the SD-CSM Case Report. 
- Error was raised when opening the Case Manager Role Centre that the User Name is "length of string is 21, but it must be less than or equal to 20".

### 2.0.0

#### Enhancements

- Created Template functionality in Case Manager. Templates can be added to a Queue Code and to a Category Code. 
- Created XMLPorts for Upgrade to export and import setup.
- In the Setup Card, the Calculate Case Times Action was removed from the Ribbon as this functionality is now automatic. 
- Default the shipped Queue Report and Case Report into the report fields when creating a Queue. 
- Created a Que Table to hold flow fields for SD Case Manager. 
- Added flow fields, restructured the Priority table and corresponding code and functionality. 
- Added flow fields, restructured the Category table and corresponding code and functionality. 
- Added flow fields, restructured the Sub Category table and corresponding code and functionality. 
- Added flow fields, restructured the Queue table and corresponding code and functionality. 
- Removed the Default field from the Queue Action Type and updated the corresponding code and functionality. 
- Restructured the Queue Escalation table and corresponding code and functionality. Allowed for Trigger Intervals on Escalation Rules.Created a new Escalation Log table and corresponding functionality. 
- Restructured the Case table and corresponding code and functionality. 
- Made Contact fields on Case Card editable. Added new Contact fields to Case Card. 
- Added a Case Closed field to the Case Watcher table. Updated the corresponding code and functionality. 
- Restructured the Case Action table and updated the corresponding code and functionality. 
- Made changes to the Role Centre. Created a Manager view of all Cases and a User view of the Users Cases. Added a list page listing the Cases by Priority. 
- Moved Category/Sub Category functionality to Queue Level. 
- Moved Queue Action Type functionality to a Global level. 
- Renamed Action Log Type to Action Log on all relevant objects. 
- Created an Analysis table and Code Unit functionality.
- Created Time Charts. 
- Fixed a spelling mistake in the Role Centre.
- Made layout changes and improvements to the Case Report and the Queue Report.

#### Bug Fixes

- Fixed an issue in the Queue Card page where a length of string error is being raised on input of Queue Code. 
- Fixed an issue where an error was raised when drilling into certain Cues in the My Case Activities Activity Group. 
- Fixed displayed values in the Case Report. 
- Fixed an issue in the Case Card whereby printing the Case Report from the Case Card was showing details for all Cases. 
- Fixed an issue in the Case Card whereby choosing to Email the Case Contact was raising a message that the Queue Status did not exist. 
- Fixed an issue in the Escalation Rules whereby the placeholder field on the email was not being passed into the email routine when Emailing an Assigned User or Watcher.
- Fixed an issue whereby when logging a new action in the Case Action Card, the Comment disappears if the user selects the Log Interaction Action and hasn't selected to Save the Comment. 
- Fixed an issue where in the Case Card, the Email Case Contact Action, attaches the Queue Report, and not the Case Report, to the Email. 
- Fixed an issue in the Case Card, where if an Action record is selected, and the Log Interaction Action is chosen, an error is raised. An Interaction can be logged against an Action in the Action Card and no error is raised. 
- Fixed an issue in the Queue List, where if the Case Report Action is chosen, an error is raised.

### 1.1.0

#### Enhancements

- Cleaned up the code and the objects. 
- Added UI changes to the Case Card Page and to the Case Action List Page. Moved fields on the Pages, setting the field importance of certain fields the FastTabs. 
- Created an Action to Create a new Case in the Role Centre, Actions Ribbon. 
- Add a list page for My Managed Cases, a list page for My Watched Cases, and a list page for Queues in the Navigation Pane of the Role Centre. 
- Created an XMLPort for Configuration and Data. Added the XMLPort to the Setup Card.
- The Email Case Action on the Case Card was renamed to Email Case Contact. 
- The Case Card was tidied up - fields were moved for ease of user input and FastTabs were removed. 
- The layout of the Case Card was simplified.
- On the Case Card, the Total Time Taken and the Time Since Last Action fields were formatted to removed the seconds and milliseconds portion of the time. 
- Moved the Queue Code field to be the first field on the Case Card for ease of user input.
- Fixed code on the Activities Cue Group to allow users to setup colour indicators on the Cues. 
- Created a Queue Report and a Case Report.

#### Bug Fixes

- Fixed a bug where the User Watcher field on the Escalation Rule Action table does not point to User Table. 
- Renamed the New Case Action Log Type field on the Queue Action Log Type table to Default. 
- Renamed the New Case Status field on the Queue Status table to Default. 
- Fixed an issue on the Escalation Rule Actions - the Escalation Rule Action to add a User Watcher now adds the User that is specified on the individual Escalation Rule Actions line to the appropriate Case. 
- Fixed an issue on the Escalation Rule Actions regarding Emailing User Watchers. 
- Fixed an issue on the Escalation Rule Actions regarding Notifying User Watchers. 
- Fixed an issue where on creation of a Case, the Case Description was being blanked out/reset to blank. 
- Fixed an issue on the Priority Card and Priority List Page - set the Editable property on the List Page to No. 
- Fixed an issue where the code for the Action File Attachments was recording links to files. The code now uploads the file to the blob field. 
- Fixed a Primary Key Error that was raised when creating a new Escalation Rule. 
- Fixed an issue where the Queue Code for an existing Case could not be changed. 
- Restructured the Case List Pages to allow standard filtering on the Case List Pages to allow filtering on cases logged by another user, or to filter down by Stage, Date Created, etc.
- Fixed the inconsistency in Queue Code field length between the tables.

### 1.0.0

#### Enhancements

- Created tables, pages and associated functionality for Setup, Cases, Action Log, Action Log Attachment, Action Log Link, Queue, Escalation Rule, Queue Status, Queue Action Log Type, Case Watcher, Priority, Category, Action Log Interaction. 
- Created functionality to use Interactions to define and track Email communication. 
- Created a Role Center and associated Cues. 
- Created a WYSIWYG Editor for Comments on Action Log Entries. 
- Created an Action Log FactBox. 
- Created a File Attachment List FactBox on the Action Log List to display a list of attached files that are assigned to the Action Log Item. Allowed the user to save or open the attachment. 
- Created a Job Queue Wrapper. 
- Changed functionality on the Action Log Link list to allow the user to open the linked record. 
- Created manual run options for Escalation Rules and Time Calculations. 
- Exposed Action Log Type on the Action Log FactBox.

#### Bug Fixes

- Fixed bug on Profile List Page. 
- Fixed bug whereby a Queue with Active Cases can be deleted.
- Fixed bug whereby on deletion of a Queue, related tables are not cleaned up. 
- Added a drop down view to Sub Category. 
- Fixed bug whereby the default Log Type is not assigned when creating a Case. 
- Allow users to select the Action Log Type when creating a new Action Log. 
- Fixed bug on Case Card. The Closed field is now set to true on the Case Card if the Queue Status that was set as ‘Closed’ is selected for the Case. 
- Fixed bug on Case Card. The State field on the Case Card is now determined by the State field of the Queue Status that is selected for the Case.
- Made change to remove the Comment field from the Action Log list. 
- Cleaned up Case deletion. 
- Normalised Case tables. 
- Fixed bug which was causing the Status not to update when creating a new Action Item. 
- Fixed UI Flow.


