## SD Case Manager Releases

### 3.0.6
#### Bug Fixes
- <div><span style="display:inline !important;">BCv17 App - A fix was made to an error &quot;The Email Item table is empty.&quot; that was raised on execution of escalation rules.</span><br></div>
- <div>BCv17 App - Fixed an issue where notifications were not being created when the escalations were run.</div>

### 3.0.5
#### Enhancements
- <div>BCv17 App - Made a change to default the Escalations Card to editable when opened.<br></div>
- <div><span>BCv17 App - Users are prevented from creating Queues if the Licence is not valid or has expired.</span><br></div>
- <div>BCv17 App - The Application Area property was set on the Role Centre Activity pages.<br></div>
- <div>BCv17 App - To aid user input the Escalation Description field on the Escalation line is marked as mandatory.<br></div>
- <div>BCv17 App - Made a change to the Assisted Setup Import to recognise the duration datatype used in escalations.<br></div>
- <div>BCv17 App - Edit, View and New Actions were removed from the Template Card.</div>
- <div><span style="display:inline !important;">BCv17 App - Edit, View and New Actions were removed from the Escalation List in the Queue Card.</span><br></div>
- <div>BCv17 App - In the Queue Card the Report Actions were set to Promoted only.<br></div>
- <div>BCv17 App - The Sub Categories list page was missing the Manage menu group.<br></div>
- <div>BCv17 App - In the Case Actions list, the menu groupings were re-ordered.<br></div>
- <div>BCv17 App - The Activity Panels from the Role Centre can now be searched for using the Tell Me.<br></div>
- <div>BCv17 App - The captions of the SD Case Manager objects were changed to be more user descriptive in the Tell Me.<br></div>
- <div>BCv17 App - The New Action in the Case Interactions and the Actions Interactions FactBoxes were removed. <br></div>
- <div>BCv17 App - Changes were made to the SD Case Manager Role Display Names.<br></div>
- <div>BCv17 App - Description length of Statuses and other Case Manager description fields were increased in length as per standard D365BC.<br></div>
- <div>BCv17 App - Changes were made to the Case Card to replicate how standard D365BC behaves if default no.s are set to yes on a no. series. <br></div>
- <div>BCv17 App - A change was made to the caption of the Setup Card.<br></div>
- <div>BCv17 App - The Action menu groups on the Setup Card were updated.<br></div>
- <div>BCv17 App - Changes were made to the layout of the Activity Groups in the SD Case Manager Role Centres.<br></div>
- <div>BCv17 App - Changes were made to the object captions as they appear in the Tell Me. <br></div>
- <div>BCv17 App - The caption of the SD Case Manager reports were changed.<br></div>
- <div>BCv17 App - Changes were made to the Names of the SD Case Manager Permission Sets.<br></div>
- <div>BCv17 App - A change was made to the prompt on Activating the Free Trial Licence.<br></div>
- <div>BCv17 App - The SD Case Manager Role Centre Display Names were updated.<br></div>
- <div>BCv17 App - Visual changes were made to the SD Case Manager Manager Role Centre.<br></div>
- <div><span style="display:inline !important;">BCv17 App - Visual changes were made to the SD Case Manager User Role Centre.</span><br></div>
- <div>BCv17 App - The code was updated to use the latest standard smtp emailing functionality in D365 which has been moved to a separate App.&nbsp;</div>
#### Bug Fixes
- <div>BCv17 App - Fixed an issue where Escalations were not working.<br></div>
- <div>BCv17 App - Made a fix to remove the Contact E-Mail or the Contact Phone from the Case Card when the Contact No. is removed.<br></div>
- <div>BCv17 App - The Edit, View and New Actions on Queue Category listpage were removed.<br></div>
- <div>BCv17 App - The Case Action Card was missing some menu items.<br></div>
- <div>BCv17 App - An issue was fixed where the New Line Action on the Actions FastTab of the Escalation Card was not behaving correctly.<br></div>
- <div>BCv17 App - Fixed an issue where a Case was not updated as closed when all Case Actions were closed.<br></div>
- <div>BCv17 App - An issue was fixed on the Case Card where removing a Contact No from a Case Card raised an error.<br></div>
- <div>BCv17 App - Issues were fixed that were raised when creating an escalation rule on a Queue Card - users could open a Card for a blank escalation line.<br></div>
- <div>BCv17 App - The View and Edit Actions were showing twice in the Case Card on the Actions FastTab.<br></div>
- <div>BCv17 App - Fixed an issue where an error was raised on creation of a Case.<br></div>
- <div>BCv17 App - Actions on the Case Action Card menu were not displaying. <br></div>
- <div>BCv17 App - The Actions Cues in the Role Centre weren't calculating the flowfield counts on the cues correctly. <br></div>
- <div>BCv17 App - In the Case Card, the Actions list page was missing a New Line Action on the Actions FastTab.<br></div>
- <div>BCv17 App - &nbsp;The Date Format Error that was appearing on opening the Setup Card prior to activating the Free Trial Licence was fixed.<br></div>
- <div>BCv17 App - The issue with creating attachments on Case Actions was fixed.<br></div>

### 3.0.6
#### Enhancements
- <div>BCv17 App - SD Case Manager Permission sets were created.<br></div>

### 3.0.5
#### Enhancements
- <div>BCv17 App - The Usage Category was updated for SD Case Manager pages for the Tell Me search. <br></div>
- <div>BCv17 App - Visual changes were made to the SD Case Manager About Page. <br></div>
- <div>BCv17 App - A number of visual changes were made to the SD Case Manager Setup Card. <br></div>
- <div>BCv17 App - Functionality was created for our Assisted Setup process.<br></div>
- <div>BCv17 App - The Licencing Control Feature was added to SD Case Manager.<br></div>
- <div>BCv17 App - The HTML Editor was updated.<br></div>
- <div>BCv17 App - Certain SD Case Manager pages were removed from the extension to the Sales Order Processor Role Centre.<br></div>
- <div>BCv17 App - Recoded existing code to allow users send emails with attachments from SD Case Manager.<br></div>
- <div>BCv17 App - Name and Description fields were updated from 50 to 100 characters as per standard D365BC change.<br></div>
#### Bug Fixes
- <div>BCv17 App - An issue was fixed where, if a Case Manager No. Series was not setup in the Setup Card then, when creating a Case, the page hangs and becomes unresponsive.<br></div>
- <div>BCv17 App - The sub categories field in the Queue Card did not have a New Line Action. <br></div>
- <div>BCv17 App - The case status field in the Queue Card did not have a New Line Action. <br></div>
- <div> <span style="display:inline !important;">•&nbsp;</span>Fixed a bug in SD-CSM Queue Category List Page where selecting page from the Role Centre's Navigation Pane allowed users to
create a Category not linked to a Queue.&nbsp;</div><div>• Fixed an issue where in the Category Card on creation of a Case the Managed By on the Case was set to the current USERID.&nbsp;</div><div>• Fixed an issue where in the Time charts for the Cases per Queue, Cases per User, Case Open Vs Close, the flowfield was based on the
create date and was not taking the closed date into account.&nbsp;</div><div>• Fixed an issue where importing the Demo Setup.xml raised an error.&nbsp;</div><div><span style="display:inline !important;">•</span>&nbsp;Fixed an issue where importing the Cases Setup.xml raised an error.&nbsp;</div><div>• Fixed a bug in the SD-CSM Action Type table whereby renaming the Code did not update Cases that had the old Action Code.&nbsp;</div><div>• Fixed a bug in the SD Case Card, Reporter Fast Tab. If a Person Contact was selected and then changed to a Company Contact and
back to a Person Contact, the Company No. and Company Name were not being set to blank.&nbsp;</div><div>• Added the Case Summary field to the SD-CSM Case Report.&nbsp;</div><div>• Error was raised when opening the Case Manager Role Centre that the User Name is &quot;length of string is 21, but it must be less than
or equal to 20&quot;.<br></div>

### 2.0.1
#### Bug Fixes
- <div><span style="display:inline !important;">•<span>&nbsp;</span></span>Fixed an issue in the Queue Card page where a length of string error is being raised on input of Queue Code.&nbsp;</div><div>• Fixed an issue where an error was raised when drilling into certain Cues in the My Case Activities Activity Group.&nbsp;</div><div>• Fixed displayed values in the Case Report.&nbsp;</div><div>• Fixed an issue in the Case Card whereby printing the Case Report from the Case Card was showing details for all Cases.&nbsp;</div><div>• Fixed an issue in the Case Card whereby choosing to Email the Case Contact was raising a message that the Queue Status did not
exist.&nbsp;</div><div>• Fixed an issue in the Escalation Rules whereby the placeholder field on the email was not being passed into the email routine when
Emailing an Assigned User or Watcher.
• Fixed an issue whereby when logging a new action in the Case Action Card, the Comment disappears if the user selects the Log
Interaction Action and hasn't selected to Save the Comment.&nbsp;</div><div>• Fixed an issue where in the Case Card, the Email Case Contact Action, attaches the Queue Report, and not the Case Report, to the
Email.&nbsp;</div><div>• Fixed an issue in the Case Card, where if an Action record is selected, and the Log Interaction Action is chosen, an error is raised. An
Interaction can be logged against an Action in the Action Card and no error is raised.&nbsp;</div><div>• Fixed an issue in the Queue List, where if the Case Report Action is chosen, an error is raised.<br></div>

### 2.0.0
#### Enhancements
- <div>• Created Template functionality in Case Manager. Templates can be added to a Queue Code and to a Category Code.&nbsp;</div><div>• Created XMLPorts for Upgrade to export and import setup.
• In the Setup Card, the Calculate Case Times Action was removed from the Ribbon as this functionality is now automatic.&nbsp;</div><div>• Default the shipped Queue Report and Case Report into the report fields when creating a Queue.&nbsp;</div><div>• Created a Que Table to hold flow fields for SD Case Manager.&nbsp;</div><div>• Added flow fields, restructured the Priority table and corresponding code and functionality.&nbsp;</div><div>• Added flow fields, restructured the Category table and corresponding code and functionality.&nbsp;</div><div>• Added flow fields, restructured the Sub Category table and corresponding code and functionality.&nbsp;</div><div>• Added flow fields, restructured the Queue table and corresponding code and functionality.&nbsp;</div><div>• Removed the Default field from the Queue Action Type and updated the corresponding code and functionality.&nbsp;</div><div>• Restructured the Queue Escalation table and corresponding code and functionality. Allowed for Trigger Intervals on Escalation Rules.
Created a new Escalation Log table and corresponding functionality.&nbsp;</div><div>• Restructured the Case table and corresponding code and functionality.&nbsp;</div><div>• Made Contact fields on Case Card editable. Added new Contact fields to Case Card.&nbsp;</div><div>• Added a Case Closed field to the Case Watcher table. Updated the corresponding code and functionality.&nbsp;</div><div>• Restructured the Case Action table and updated the corresponding code and functionality.&nbsp;</div><div>• Made changes to the Role Centre. Created a Manager view of all Cases and a User view of the Users Cases. Added a list page listing
the Cases by Priority.&nbsp;</div><div>• Moved Category/Sub Category functionality to Queue Level&nbsp;</div><div>• Moved Queue Action Type functionality to a Global level.&nbsp;</div><div>• Renamed Action Log Type to Action Log on all relevant objects.&nbsp;</div><div>• Created an Analysis table and Code Unit functionality.
• Created Time Charts.&nbsp;</div><div>• Fixed a spelling mistake in the Role Centre.
• Made layout changes and improvements to the Case Report and the Queue Report<br></div>
#### Bug Fixes
- <div><span style="display:inline !important;">•<span>&nbsp;</span></span>Fixed a bug where the User Watcher field on the Escalation Rule Action table does not point to User Table.&nbsp;</div><div>• Renamed the New Case Action Log Type field on the Queue Action Log Type table to Default.&nbsp;</div><div>• Renamed the New Case Status field on the Queue Status table to Default.&nbsp;</div><div>• Fixed an issue on the Escalation Rule Actions - the Escalation Rule Action to add a User Watcher now adds the User that is specified
on the individual Escalation Rule Actions line to the appropriate Case.&nbsp;</div><div>• Fixed an issue on the Escalation Rule Actions regarding Emailing User Watchers.&nbsp;</div><div>• Fixed an issue on the Escalation Rule Actions regarding Notifying User Watchers.&nbsp;</div><div>• Fixed an issue where on creation of a Case, the Case Description was being blanked out/reset to blank.&nbsp;</div><div>• Fixed an issue on the Priority Card and Priority List Page - set the Editable property on the List Page to No.&nbsp;</div><div>• Fixed an issue where the code for the Action File Attachments was recording links to files. The code now uploads the file to the blob
field.&nbsp;</div><div>• Fixed a Primary Key Error that was raised when creating a new Escalation Rule.&nbsp;</div><div>• Fixed an issue where the Queue Code for an existing Case could not be changed.&nbsp;</div><div>• Restructured the Case List Pages to allow standard filtering on the Case List Pages to allow filtering on cases logged by another user,
or to filter down by Stage, Date Created, etc.</div><div>• Fixed the inconsistency in Queue Code field length between the tables.<br></div>

### 1.1.0
#### Enhancements
- <div><span style="display:inline !important;">•<span>&nbsp;</span></span>Cleaned up the code and the objects.&nbsp;</div><div>• Added UI changes to the Case Card Page and to the Case Action List Page. Moved fields on the Pages, setting the field importance of
certain fields the FastTabs.&nbsp;</div><div>• Created an Action to Create a new Case in the Role Centre, Actions Ribbon.&nbsp;</div><div>• Add a list page for My Managed Cases, a list page for My Watched Cases, and a list page for Queues in the Navigation Pane of the
Role Centre.&nbsp;</div><div>• Created an XMLPort for Configuration and Data. Added the XMLPort to the Setup Card.
• The Email Case Action on the Case Card was renamed to Email Case Contact.&nbsp;</div><div>• The Case Card was tidied up - fields were moved for ease of user input and FastTabs were removed.&nbsp;</div><div>• The layout of the Case Card was simplified.
• On the Case Card, the Total Time Taken and the Time Since Last Action fields were formatted to removed the seconds and
milliseconds portion of the time.&nbsp;</div><div>• Moved the Queue Code field to be the first field on the Case Card for ease of user input.
• Fixed code on the Activities Cue Group to allow users to setup colour indicators on the Cues.&nbsp;</div><div>• Created a Queue Report and a Case Report.<br></div>
#### Bug Fixes
- <div><span style="display:inline !important;">•<span>&nbsp;</span></span>Fixed bug on Profile List Page.&nbsp;</div><div>• Fixed bug whereby a Queue with Active Cases can be deleted.
• Fixed bug whereby on deletion of a Queue, related tables are not cleaned up.&nbsp;</div><div>• Added a drop down view to Sub Category.&nbsp;</div><div>• Fixed bug whereby the default Log Type is not assigned when creating a Case.&nbsp;</div><div>• Allow users to select the Action Log Type when creating a new Action Log.&nbsp;</div><div>• Fixed bug on Case Card. The Closed field is now set to true on the Case Card if the Queue Status that was set as ‘Closed’ is selected
for the Case.&nbsp;</div><div>• Fixed bug on Case Card. The State field on the Case Card is now determined by the State field of the Queue Status that is selected for
the Case.
• Made change to remove the Comment field from the Action Log list.&nbsp;</div><div>• Cleaned up Case deletion.&nbsp;</div><div>• Normalised Case tables.&nbsp;</div><div>• Fixed bug which was causing the Status not to update when creating a new Action Item.&nbsp;</div><div>• Fixed UI Flow.<br></div>

### 1.0.0
#### Enhancements
- <div>• Created tables, pages and associated functionality for Setup, Cases, Action Log, Action Log Attachment, Action Log Link, Queue,
Escalation Rule, Queue Status, Queue Action Log Type, Case Watcher, Priority, Category, Action Log Interaction.&nbsp;</div><div>• Created functionality to use Interactions to define and track Email communication.&nbsp;</div><div>• Created a Role Center and associated Cues.&nbsp;</div><div>• Created a WYSIWYG Editor for Comments on Action Log Entries.&nbsp;</div><div>• Created an Action Log FactBox.&nbsp;</div><div>• Created a File Attachment List FactBox on the Action Log List to display a list of attached files that are assigned to the Action Log
Item. Allowed the user to save or open the attachment.&nbsp;</div><div>• Created a Job Queue Wrapper.&nbsp;</div><div>• Changed functionality on the Action Log Link list to allow the user to open the linked record.&nbsp;</div><div>• Created manual run options for Escalation Rules and Time Calculations.&nbsp;</div><div>• Exposed Action Log Type on the Action Log FactBox.
<br></div>
#### Bug Fixes
- <div>BCv14 Public App - Fixed an issue where an error was raised when emailing a Case Contact from a Case Card as the code was taking the User ID email address from the SMTP Setup and not the Case Manager Setup Card.</div>

### 3.0.4
#### Enhancements
- <span style="display:inline !important;">BCv14 Public App -<span>&nbsp;</span></span>Made a change to update the WriteMode property to allow emailing of a Case Contact.
- <span style="display:inline !important;">BCv14 Public App -<span>&nbsp;</span></span>A change was made to the Escalation Card to place the list pages on FastTabs that could be expanded and collapsed.
- <span style="display:inline !important;">BCv14 Public App -<span>&nbsp;</span></span>A change was made to the Category Card to place the list pages on FastTabs that could be expanded and collapsed.
- <span style="display:inline !important;">BCv14 Public App -<span>&nbsp;</span></span>A change was made to the Case Card to place the list pages on FastTabs that could be expanded and collapsed.
- <span style="display:inline !important;">BCv14 Public App -<span>&nbsp;</span></span>A change was made to the Queue Card to place the list pages on FastTabs that could be expanded and collapsed.
- <span style="display:inline !important;">BCv14 Public App -<span>&nbsp;</span></span>Activity Groups from the SD Case Manger Role Centre were surfaced on the Order Processor Role Centre and the Purchasing Agent Role Centre.
- <span style="display:inline !important;">BCv14 Public App -<span>&nbsp;</span></span>Updated the usage category on pages so that SD Case Manager pages can be found when searching in the Tell Me.
- <span style="display:inline !important;">BCv14 Public App -<span>&nbsp;</span></span>Actions with icons were added to the Role Centre.
- <span style="display:inline !important;">BCv14 Public App -<span>&nbsp;</span></span>The code base was converted from C/AL to AL extensions.
- <span style="display:inline !important;">BCv14 Public App -<span>&nbsp;</span></span>Licensing control was added to SD Case Manager.
- <span style="display:inline !important;">BCv14 Public App -<span>&nbsp;</span></span>The HTML Editor was converted to Javascript.
- <span style="display:inline !important;">BCv14 Public App -<span>&nbsp;</span></span>Code in SD Case Manager that had used Ping Pong was re-written.
- <span style="display:inline !important;">BCv14 Public App -<span>&nbsp;</span></span>The SD Case Manager chart codeunits were removed from the code base.
#### Bug Fixes
- <span style="display:inline !important;">BCv14 Public App -<span>&nbsp;</span></span>Our Simply Dynamics charts were removed from SD Case Manager.
- Fixed an issue raised on closing a Case's Action in a filtered list of Actions where a comment was also stamped on another action.
- Fixed an issue where the Edit and View Actions were shown twice on the Actions FastTab in the Case Card.
- Fixed an issue raised on creation of a new Case if only one Queue Code has been set up in SD Case Manager.
- <div>Fixed an issue where the Case Number was re-numbered when the mandatory fields were filled in.</div>
- Fixed an issue where if a mandatory field was entered and then blanked out on a Case, a user could navigate to the next page or close the page without entering the mandatory field.
- Fixed an issue where an error was raised when a Case was opened from the Open Cases List on the Role Centre.
- Fixed an issue where updating the Status on the Case Card to a closed status was raising an unexpected validation error.

### 3.0.3
#### Enhancements
- Made a change to update the Case Status on the Case Card when the user is prompted to close a Case.
#### Bug Fixes
- Fixed an issue where closing a Case was raising an intermittent error.
- Fixed an issue where the Assign to Me Action on the Case Card was disabled when creating a new Case.
- Fixed an issue where users were unable to navigate to the next or previous record in the Case Card with the introduction of the test fields on the Setup Card.

### 3.0.2
#### Enhancements
- Made a change that when the Queue Code is changed on a Case Card, that the Category Code and the Sub-Category Codes are re-validated.
- Changed the default answer from yes to no on the message raised when Queue Code/Category is changed on the Case Card.
- Added functionality to prevent the user from navigating to a different Case and by-passing the check for mandatory fields.
- Moved the placement of the Summary field on the Case FactBox and the Case Action FactBox.
- Moved the Simply Dynamics About Action on the Setup Card to the General group on the Ribbon.
- Changed the wording of the message displayed to users on change of the Queue Code on a Case Card.
- Surfaced the KPIs for the Case Sub Category on the SD-CSM Queue Sub Category List.
- Created functionality to allow users to take a photo and embed the photo in the Case Action html comment area when creating Case Actions on a mobile device .

### 3.0.3
#### Enhancements
- Created a new mobile device specific page for creating Case Actions and created functionality to direct mobile users to use this page for optimum rendering of the Case Action.
#### Bug Fixes
- Fixed an issue where drilling down on the Case No. FlowField on the Case Action FactBox in NAV 2018 launched a lookup page rather than launching the Case Card.

### 3.0.2
#### Enhancements
- Added the Case Summary field to the Case FactBox and the Action Summary field to the Case Action FactBox.
- Added the Case FactBox to the Case Action List and to the Case Action Card.
- Added KPIs for Case Categories and Case Sub Category and surfaced same on the associated pages.
- Added a new mandatory checkbox list to the Case Manager Setup Card to flag the field to be tested before exit on a newly created Case.
- The Simply Dynamics About Action was added to the SD Case Manager Setup Card.
- Created new functionality on the Template Card to allow a Default Assigned User to be assigned to the Template Actions.
- Made a change to prompt/ask the user, on change of the Queue Code in the Case Card, to confirm whether to delete all the existing Actions and Watchers on the Case or to append new Actions and Watchers to the Case.
- A new communication method table was added to log how a Case was received and to record the preferred communication method for Watchers.
#### Bug Fixes
- Fixed an issue in NAV2018 where new Actions couldn't be added to a Template when editing the Template in the Template Card.
- Fixed an issue where on input of a Case Action, changes were reverted if the Attach File action, New Link action or Log Interaction action was selected when inputting text in the HTML Editor.

### 3.0.1
#### Enhancements
- In the 2013R2 Build, the Case Report Email attachment pdf name didn't reflect the Case Number.

### 3.0.0
#### Enhancements
- In the 2013R2 build, on input of a Template Action, the text in the HTML Editor is reverted if the Completed Action was chosen when inputting text into the HTML Editor.
- In the 2013R2 Build, there was a compile error in the SD-CSM Management Codeunit in ref to File Management Codeunit when tested on non W1 environment.
- In the 2013R2 Build, the Actions List Page contained an extra action called &quot;Home&quot; that duplicated the &quot;New Link&quot; functionality.
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
- <div><span><span style="display:inline !important;">•<span>&nbsp;</span></span>Replaced Text Editor with Html Editor.<br></span><div>• Created functionality to define a Queue Default Watchers table and assign at Queue Level for Email and User Watchers. Entries in this<br></div><div>table are automatically added to a case for the Queue.<br></div><div>• Displayed the Case Number in the My Open Cases List Pages.<br></div><div>• In the SD-CSM Case Card, if there is a contact email specified on the Case Card, when the Email Case Contact Action is chosen,<br></div><div>default the Contact Email into the To: field of the Send Email Card.<br></div><div>• SD-CSM Queue Report, on the Case Lines, show the Total Cost (LCY) for each case within the Queue. Added a Report Total for Total<br></div><div>Cost (LCY).<br></div><div>• In the Case Card, Reporter FastTab, horizontally aligned the Contact Company Name to the Contact Company No.<br></div><div>• Removed the Setup Action and the Execute Escalation Rules Action from the SD-CSM User Role Centre.<br></div><div>• Refactored XMLPorts Element Names.<br></div><span>• Updated the Readme.txt file.</span><br></div>
#### Bug Fixes
- Fixed an issue where the default export filename and manifest header were set to the wrong product id when exporting the Setup data from SD Case Manager..
- Fixed a compile error in the Template Action Card.
- Fixed an issue where an error was raised on close of the page when reviewing a completed Action.

