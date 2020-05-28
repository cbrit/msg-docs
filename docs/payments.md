# Payments

## Take a Payment

To initiate any Payment Function either type Ctrl-M (for Money) or click on the 
![](images/payments/image001.png)
 icon. The Initial Payment Screen will then appear.


![](images/payments/image002.png)
  

While the Initial Payment Screen may default to a given defendant or a given Payment Reason based on the current record, you may take any valid type of payment on any defendant regardless of the record from which you start.

***DEFENDANT***  
The 'Case Number' selected must be a Case of the listed Defendant. The Drop Down Field for Case Number will only display this Defendants cases, unless the 'Payer is not Defendant' box is checked. If the 'Payer is not Defendant' box is checked, any Case Number may be entered. To the right of the case number, the amount owed on this case is displayed. If the case has not yet been worked, the case will be shown to be pending.

![](images/payments/image003.png)  

To the right is displayed the number of open cases for this defendant and the number Worked/Pending. Also displayed is the total amount owed.

***EMPLOYEE***  
The Employee logged in is assumed to be the Employee taking the ` payment. If a different Employee is taking the payment, the 'Change Employee' button should be clicked and the actual Employee taking the payment should log in.

![](images/payments/image005.png)  

***DEFENDANT INFORMATION***  
Clicking on the Defendant Information button will display all the information of the Payer. The information displayed is the same as if 
![](images/payments/image007.png)
 had been pressed.

![](images/payments/image006.png)  
*Defendent information button*

***BONDS AVAILABLE***  
The total number of CASH BONDS (if any) and the total amount is displayed. If you are about to APPLY, RETURN, or FORFEIT a Bond, 'Bond to Use' should display the Bond being acted upon. Press F4 or click the down arrow to see a list of this Defendants Cash Bonds.

![](images/payments/image008.png)  

***REASON***  
The Reason field defines what type of Action is to take place. If you are in the 'Cases Table', the Reason will default to CASE PAYMENT. The Reason field will default depending on the context. Possible choices are:

![](images/payments/image009.png)  

***CASE PAYMENT***  
for payments on cases. If this is the initial payment, Case Disposition Update will be displayed (Adjudication, Court Date, etc) for possible change. If this is the initial payment, but Court Costs have been waived, the Exclude Costs should be checked. If a Bond is being applied, the bond must be listed in the 'Bond to Use' field. If this is a cost prior to Adjudication (like a Warrant Fee) then the PreAdjudication field should be checked. If the Defendant has multiple cases to pay at once, 'Group All Costs' should be checked.

![](images/payments/image010.png)  

***CASE PAYMENT SETUP***  
If a case has been adjudicated, but the defendant is not paying initially, the correct fines and costs should be SETUP. This follows CASE PAYMENT exactly with the exception of the Payment Method defaulting to SETUP (instead of CASH). With SETUP, no receipt number is generated as no actual payment is transacted. This exact function could be accomplished by selecting CASE PAYMENT and changing the Payment Method to SETUP.

***MISCELLANEOUS PAYMENT***  
Payments that do not apply toward a case. Many different uses (Payments for COPIES or FEES).

***PARKING***  
If you have Parking Tickets in the separate Parking Ticket Table and not mixed in the 'Cases' Table, this is how you take a Parking Payment. The next screen will help you to identify which ticket. If the Payer Name is NOT the payer of this ticket, it should be cleared before going on. Otherwise, the ticket being paid will be limited to those of the Payer.

***VOID RECEIPT***  
The next screen will help you chose which receipt to void.

***REPRINT A RECEIPT***  
Prints an already existing Receipt.

***REFUND RECEIPT***  
If a receipt needs to be returned, but it is too late to VOID, a REFUND will subtract amounts from the given accounts.

***DRIVING SCHOOL***  
Payments applied toward records in the 'Driving School' Table.

***BOND RECEIVE CASH***  
***BOND RECEIVE SURETY***  
***BOND RECEIVE PROPERTY***  
Receipts for CASH, PROPERTY or SURETY bonds. Although a Case Number or Warrant Number may be referenced, the BOND is taken on the Defendant. No Case Number is required.

***BOND DISPOSE RETURN***  
***BOND DISPOSE FORFEIT***  
***BOND DISPOSE CIRCUIT***  
***BOND DISPOSE APPLY***  
Actions for the disposition of a previously received Cash Bond The Bond being disposed must be referenced in the 'Bond to Use' field. The 'BOND DISPOSE APPLY' is redundant to a 'CASE PAYMENT' with a bond reference.

***BOND CONVERT SURETY***  
Converts a SURETY to a CASH BOND. Since this is a Surety Bond and 'Bond to Use' is for CASH BONDS, the 'Bond to Use' field should be blank. The Surety Bond being converted will be determined in the next screen.

When your 'Initial Payment Screen' is ready, click on OK. You may also press the F9 key for the same results.

***CASE DISPOSITION UPDATE SCREEN***  
If the Payment Action is the Initial Payment on a case, the 'Case Disposition Update' screen appears to allow you to input the Adjudication and other possible case information that may need to be changed such as Court Date. You may click OK or press F9 when finished. If no changes are to be made to the Case Record, you may click on CANCEL or press ESC.

![](images/payments/image012.png)  

***CASE PAYMENT SCREEN***  
Upon first entering the Case Payment Screen, the focus will normally be on the Pay Method defaulted to CASH. You may also select Pay Methods of CHECK, MONEY ORDER, CREDIT CARD, JAIL or SETUP. SETUP would not involve payment actually taken, but instead setting up what is now owed. For all others an amount should be placed in ![](images/payments/image014.png) which will then be place in ![](images/payments/image015.png).

![](images/payments/image013.png)  
*The Case Payment screen*

The DATA GRID shows the Case Numbers which would vary only if multiple cases are being paid. The next columns are the Fine/Cost Titles, the Original amount owed, the amount Paid prior to this payment, the Current amounts ofthis payment and the Resulting Balance. As you put in the amount Tendered and Applied, the Current column will fill with the appropriate amounts from top to bottom. You may optionally edit and adjust where the current amounts are to be applied. You may also adjust the Original amounts and Costs as needed. However, an Original amount may not be adjusted below the amount paid prior to this payment. Previous payments would need to be first voided. The amount in the Applied field must equal the total amount at the bottom of the Current column. If it does not, a red message will appear below the total Cost reflecting how much to add or subtract: 

![](images/payments/image016.png)


Since FINE is a common item for which to adjust the amount, you may typeCtrl-F to enter the FINE in a Pop-up Window. 

![](images/payments/image017.png)



![](images/payments/image018.png) need only be checked if the case is to be closed prior to full payment being made. Normally, you will not be checking this box.


![](images/payments/image019.png) is used to track payments received in the mail.


![](images/payments/image020.png) is used to enter a check, money order or any other reference number.

***PRINTER***  
Printer is the default receipt printer and may be changed. The receipt number should normally be left blank so that the system will generate the next receipt number in sequence. Instead if needed you may manually enter a receipt number. The Print and Screen check boxes determine if the receipt is to be printed to the Printer, the Screen or both.

![](images/payments/image021.png)

***COMMENT***  
A comment may be added to the Payment record. If the 'Comment on Reciept' box is checked that comment will also be printed on the receipt.

![](images/payments/image022.png)

***POST DATE, COPIES***  
Post Date and number of copies are defaulted and may be changed if needed.

![](images/payments/image023.png)

***CASE INFO***  
Clicking Case Info will display the 'Case Disposition Update' screen previously referenced.

![](images/payments/image024.png)

***RESTITUTION***  
Clicking Restitution will take you to the Restitution Manager for this case.

![](images/payments/image025.png)

***PAYMENT PLAN***   
Payment plan allows you to put in a current or start date. Period payments are to be made (MONTHLY, WEEKLY, BI-WEEKY, VARIABLE). If you then specify the amount, the Next Due and Finish Date will be filled in. If instead you click Fixed Finish, the Finish Date will not change, but the amount will be adjusted so that that Finish Date will be completed. The Amount is rounded up to the nearest $5, so that the last payment could be less than the Amount. You may also click Manual and no calculations will be made. You may then fill in the fields as you wish.

![](images/payments/image026.png)

When ready to actually print or display the receipt(s) click on OK or pressthe F9 key. If you wish to abort this process, click on CANCEL or press ESC.If 'Setup Return' is checked, the focus will go back to the 'Initial Payment Screen' when finished.

![](images/payments/image027.png)

***MISCELLANEOUS PAYMENT***  
Miscellaneous Payment Screen has a similar look as the Case Payment Screen. A case may, but does not have to be referenced. The payment record will havethe Misc Receipt box checked.

![](images/payments/image028.png)

***PARKING PAYMENT***  
Selecting PARKING on the Initial Payment Screen will bring up thePayment Parking Screen designed to help you pick the Parking Ticket thatis being paid. Clicking OK or Pressing F9 brings up this now familiarpayment screen.

![](images/payments/image029.png)

![](images/payments/image030.png)


## Reprint a Receipt

Following the same instructions for taking a Case Payment, change the reason on the Initial Payment Screen to REPRINT RECEIPT.

![](images/payments/image031.png)

Pressing F9 or clicking on OK will take you to the Receipt Reprint Screen.

![](images/payments/image032.png)

The receipt number to reprint must be referenced on this screen. Clicking on OK will reprint that receipt to either the Printer or Screen or Both.

![](images/payments/image033.png)

Notice that the Original Receipt with the Original Date and Time are printed below the REPRINTED: banner. The REPRINTED: banner shows the current Date and Time the reprint took place.

## Void a Payment

Following the same instructions for taking a Case Payment, change thereason on the Initial Payment Screen to VOID RECEIPT.

![](images/payments/image034.png)

Pressing F9 or clicking on OK will take you to the Void Receipt Screen.

![](images/payments/image035.png)

The receipt to be voided must first be entered on this screen along witha Reason for Void.

![](images/payments/image036.png)

Notice that the Original Receipt with the Original Date and Time are printed below the VOIDED: banner. The VOIDED: banner shows the Date and Time the Void took place along with the Voiding Employee.

## Receive a Cash Bond

Following the same instructions for taking a Case Payment, change thereason on the Initial Payment Screen to BOND RECEIVE CASH.

![](images/payments/image037.png)

Pressing F9 or clicking on OK will take you to the Receive Bond Screen.

![](images/payments/image038.png)

Put in the Bond Amount in Tendered and Applied to Receive the CashBond.

## Forfeit, Return, Apply a Bond

Following the same instructions for taking a Case Payment, select the bond in the 'Bond to Use' field on the Initial Payment Screen. Put the BOND DISPOSE FORFEIT, BOND DISPOSE RETURN, BOND DISPOSE CIRCUIT or BOND DISPOSE APPLY in the 'Reason' field.

Note that if this is a BOND APPLY you may also select CASE PAYMENT in the 'Reason' field.

![](images/payments/image039.png)

Pressing F9 or clicking on OK will take you to the Dispose Bond Screen.

![](images/payments/image040.png)

The amount applied will already be filled in from the original bond. You may change the amounts for FORFEIT, CIRCUIT, or RETURN as needed. You do not have to use the entire bond amount. Any amount left over will be available to dispose of in the future. A BOND APPLY will go to a regular Case Payment screen with BOND APPLY as Pay Method.

## Manage Restitution

In order to manage Restitution on a particular case, that case must have Restitution setup in the Payment Manager. Add Restitution as a row inthe Initial Fines and Cost setup. You may do this later by beginning to take a Case Payment, adding Restitution and changing the Pay Method to SETUP.

![](images/payments/image041.png)

Once Restitution in place on this case, you need to go to the Restitution Manager to setup the Receiver or Payee of the Restitution. You may display the Restitution Manager by goingto the particular case in the CaseTable, clicking on the Options Menu, and then clicking on Restitution Manager. 

![](images/payments/image042.png)

![](images/payments/image044.png)

This sametask may be accomplished bytyping Ctrl-R. In the Payment Manager on the Case PaymentScreen there is a 
![](images/payments/image043.png) button that will also display the Restitution Manager.

The Restitution Receivers or Payees need to be entered here. The Amount must be the amount from the Restitution row in the Payment Setup. This amount may be split as needed among various Payees. Each Payee must have a record in the Profile Manager with the name and address. If there is not a record in the Profile Manager for the Payee, one must be created. (See NAME DROP DOWN FIELD in the Field Types Section of this manual.) You may press F4 and start typing the last name or you may type Ctrl-N or right click the field and select 'Create New Profile' from that menu.

![](images/payments/image045.png)

There must be one or more Payees with the Amounts owed to them equal to the Restitution setup for the Defendant to pay.

![](images/payments/image046.png)

Once the Payee Name is in place, no further action is needed in Restitution Manager until the Defendant has made payments toward Restitution. If $60 of the Total $100 of Restitution was paid by the defendant the Restitution Manager would look like this:

![](images/payments/image047.png)

The Amount Column remains at the Original $100. $60 has been received from the Defendant. The Defendant still owes a balance of $40. The court now has $60 that needs to be sent to the Payee. There are Restitution reports that will alert the court that money needs to be sent to the Payee. You acknowledge that the Restitution was actually mailed to the Payee by putting the Date Sent and the optional Check Number in place.

![](images/payments/image048.png)

By clicking OK at the bottom of this screen, you are telling the system that you have sent $60 to the Payee.

If you were to look at the Restitution Manager now, it would show that the Defendant still has to pay $40 and that the court does not currently owe the Payee any outstanding balance.

![](images/payments/image049.png)

The bottom Restitution Payments Sent grid will show a history of when the court sent the Payee the Restitution it previously collected.

## Display Defendent Information

A complete presentation of a Defendants Information may be viewed by clicking on the ![](images/payments/image051.png) Information Button or in the Payment Manager: 

![](images/payments/image050.png)

***CASES***  
The Defendant Information Screen has 6 Tabs or Sections. The first section is Cases. Red Alerts (UTC-6B, UTC-25, WARRANTS, UNDER 18, etc) areacross the top followed by a summation of the number of Open Cases,Amount Owed and Cash Bonds. The Cases Data Grid shows all thedefendants cases, current status, balance, etc. The Payments Grid breaksdown the payments on a case basis. Notice that voided payments have a red line through them and that subsequent multiple payments on the same caseare lighter. You may double click in the margin to the left of any recordand that record will open up in another window for viewing or editing.

![](images/payments/image052.png)

When finished you click on OK or press F9 key. CHANGE DEFENDANT will allow to select another defendant's information. PRINT HISTORY gives you options to print any or all of the information in the 6 tabs.

![](images/payments/image053.png)

***PAYMENTS***  
The Payments tab shows all defendant payments on a time basis starting withthe most recent. Again, you may left click on the margin to go to that record.

![](images/payments/image054.png)

***WARRANTS***  
The Warrants Tab shows all Warrants for the defendant including thestatus of the warrant, date issued, served, recalled, etc.

![](images/payments/image055.png)

***BONDS***  
The Bonds Tab shows all the defendants bonds and their respective balances.

![](images/payments/image056.png)

***PROFILE***  
The Profile Tab displays the 1 Profile for this defendant. The Records Attached grid displays every place in the system that Profile is referenced.

![](images/payments/image057.png)

***STATE***  
If available, a state drivers history will be displayed for this defendant.

![](images/payments/image058.png)

***PRINTING DEFENDANT HISTORY***  
By clicking on the Print History Button on the Cases Tab you may choose from the many options on exactly what information you want printed.

![](images/payments/image059.png)

## Logging In to the Program

From your desktop double click on the MSG Court Manager Icon. The Application should now load. Depending on your System Setup, the following "Employee Validation" screen may appear:

![](images/payments/image060.png)

Your employee name and password may now be entered. You must first put your name in the "Employee Name" field. This may be accomplished several different ways.

You may click on the arrow to the right of the employee name field to display a "Drop down" list of employees from which to select your name.

Alternatively, you may enter your employee ID number in this field and press either the ENTER or the TAB key. Note that you do not have to enter the leading zeros on the 5 digit employee ID number. Employee ID 00015 may simply be entered as 15.

You may also enter the first few letters of your last name and press either the ENTER or TAB key. Note that if you enter the first letter or several letters of your last name it must be enough to distinguish it from other Employee names. If you are the only employee whose last name begins with 'S', you would only need to enter 'S'. Should your Name not appear on this list, an Application Administrator would need to add it to the Employee Data Table.

***FIELD FOCUS***  
In General, a field with the RED color has the FOCUS and is ready to accept input. To change the FOCUS to another field you may press ENTER, TAB, Arrow keys or simply mouse click the field to which you wish to give the FOCUS.

***PASSWORD***  
Once the Employee Name is displayed you should change the FOCUS to the Password field. (with ENTER or TAB) You may type in your password. Your password will remain hidden as asterisks '*' will appear as you type. Should you forget your PASSWORD, an Application Administrator would need to re-enter your PASSWORD in the Employee Data Table.

With both your Name and Password Entered, you may continue by pressing the F9 key. You could also continue by giving the FOCUS to the OK button and pressing ENTER. Alternatively, you could Double Click the OK button.

***WINDOWS LOGIN OPTION***  
By setting the appropriate parameter, your Application may be setup to use the WINDOWS LOGIN for Validation. This option will allow you to skip the above Employee Validation Box. Instead the Application will know who you are based on your initial Windows Login to your computer or Network. While this option may be more convenient, it is less secure. Once you have logged on to your computer, anyone could then click on the icon and go directly to the MAIN SCREEN.

After proper Employee Validation, you are ready to start your adventure on the MAIN SCREEN.

## Search for a Record

The means by which you search for a given record will vary based upon which table you are in. You may begin by clicking on Optionsand then on the menu item'Quick Search'. Using theshortcut 'F1' is much simplier.

![](images/payments/image061.png)

If you are in the 'Cases' Table the resulting window is:

![](images/payments/image062.png)

The white label under the 'Search for' field will inform you the various ways to access this table in 'Quick Search'. If you are searching by name you may enter the last name, comma, space, first name to display that record to select. It's often easier just to enter the first letter or first few letters of the last name to bring up the list of names.

Entering CR will display:

![](images/payments/image063.png)

You may now scroll up and down this list to find the case you want. Notice that the list is in alphabetical order by name. Pressing Enter on the record you want will cause this screen to disappear and place you on that record. You may also search by Case Number. Entering TR07-1328 will yield:

![](images/payments/image064.png)

Now you may scroll through the records in 'Case Number' order pressing 'Enter' on the one to which you wish to go. Likewise in the 'Case' Table you may also search by Court Date and UTC Number.

If you were in the Warrants Table your 'Search' window would look like:

![](images/payments/image065.png)

The only difference in the 'Warrants' Table search and the 'Case' Table search is on what you are searching. For warrants you may search by Defendant Name, Warrant Number, or Date Issued. Each Table has its own unique fields on which you can search.

If a table does not have many records, this 'Search for' window may be by-passed and a display of all the records appear. If you were in the 'Case Type' Table and pressed F1 you would see:

![](images/payments/image066.png)
