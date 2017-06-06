# FECFile Release Notes

**NEW! Build 8.2
Release date – June 7, 2017**

What's new?

*	FECFile — Revised Form 3Z and 3PZ.
*	FECFile — Faxed confirmation receipts will no longer be sent.
*	FECFile — Form 2, vice presidential name fields have been added for presidential candidates. 
*	FECFile — Schedule H1, Flat Minimum Percentage option has been removed.
*	FECFile — Form 5, contributions received can now be added to 24/48 hour independent expenditure reports.
*	FECPrint — Page by page and schedule view is no longer supported. 
*	FECPrint — All negative value minus signs (-) have been replaced with an en dash (–) plus a space.
*	FECPrint — Form 1, Line 5C now shows Name of Candidate.
*	FECPrint — Form 1S, standardized Form 1S with new template (now accommodating four Joint Fundraising Participants, 1 Affiliated, 1 Designated Agent, and 1 Bank in each Form 1S).
*	FECPrint — Form 2S, standardized Form 2S with new template (now accommodating four Authorized Committees in each Form 2S).
*	FECPrint — Form 3P, Termination Report checkbox bug has been corrected.
*	FECPrint — Form 3X, Schedule E, Subtotal labels (a, b, c) have been corrected.
*	FECCheck — Form 1, changed from Warning to Error for Candidate Office, State, and District, if committee is Principal Campaign Committee or Authorized Committee.
*	FECCheck — Form 1, changed from Warning to Error for Party Code if committee is Principal Campaign Committee; Authorized Committee; or a National, State, or Subordinate Party Committee.
*	FECCheck — Form 2, added Warning, for vice president Last Name and First Name Fields, if Office is P (presidential).


**Build 8.1.0.6  
Release date – October 11, 2016**  
[  
](http://fecload-update.fec.gov/cgi-bin/fecfile)Updates:

*   FECPrint - Forms 3, 3P and 3X: The FEC Identification Number field on Schedule B will now display the committee ID. In the absence of a committee ID, the candidate ID will display.

**Build 8.1.0.5  
Release date – October 3, 2016**

Updates:

*   FECFile - Corrected an aggregate issue for Form 3X, 24 Hour Report, if Disbursement Date is missing.
*   FECPrint - New standardization of name fields: Last Name, First Name, Middle Name, Prefix, Suffix. Missing data elements will now print as an empty field (showing comma). Example: Smith,John,P,,Jr.
*   FECPrint - Form 3, Form 3P, Form 3X, and Form 6 (and accompanying schedules) have been revised with new templates.
*   FECPrint- New "Beneficiary Committee Number" field has been added to Schedule B for Form 3, Form 3P, and Form 3X.
*   FECPrint- New "Personal Funds of the Candidate" check-box field has been added to Schedule C for Form 3, and Form 3P.  

**Build 8.1.0.4  
Release date – February 8, 2016**  
[  
](http://fecload-update.fec.gov/cgi-bin/fecfile)Updates:

*   FECFile - Performance improvement launching *.DCF files containing multiple 24 - Hour Reports.
*   FECPrint - Added new "Memo Item" check-box for Form 3 and 3P Schedules A, B, and C. and for Form 3X Schedules A, L-A, B, L-B, C, E, F, H4, and H6.
*   FECCheck - Canadian ZIP codes now accepted.
*   Form 3P - "Public-Funding" check-box is unselected by default.
*   Form 3P - Disbursements: Election Designation and Year of Election are enabled.

**Build 8.1.0.3  
Release date – January 5, 2016**  
[  
](http://fecload-update.fec.gov/cgi-bin/fecfile)Updates:

*   Form 3X - 24 Hour Report aggregate value calculated based on calendar year.
*   Form 5 - 24 and 48 Hour Report aggregate value calculated based on calendar year.

**Build 8.1.0.2  
Release date – October 5, 2015**  
[  
](http://fecload-update.fec.gov/cgi-bin/fecfile)Updates:

*   FECFile - Minimum system requirements have changed - Java 7 (8 preferred) & Adobe Acrobat Reader DC now required.
*   FECFile - Installation warning message "...minimum requirements were not met" removed for Windows 8 & 10.
*   FECFile - Check Limits function updated.
*   FECFile - Changed text from "24/48 Hour Notice" to "24/48 Hour Report".
*   FECFile - Committee List lookup function downloads to a new more accessible location.
*   Form 3P - New public funding checkbox.<span style="FONT-SIZE: 11pt; FONT-FAMILY: &quot;Calibri&quot;,&quot;sans-serif&quot;; COLOR: #1f497d"></span>  

*   FECPrint - Aligned all amount fields, centered on decimal point.
*   FECPrint - The transaction order for Schedule H3 has been corrected.
*   FECPrint - Print preview for Form 99 now shows committee information.
*   FECPrint - Corrected mapping issues to show Schedule L "Total" field.
*   FECCheck - Removed warning message "Subtotal $xxx.xx not supported by other lines" when a report contains no transactions.
*   FECCheck - C7 type committees are now able to file a Form 99 without fatal error.
*   FECLoad - Removed error message "incorrect password" when uploading the report to the TEST server.
*   FECLoad - System no longer saves the previously provided fax number. NOTE: Filer will need to enter the fax number at each upload instance if a fax receipt is needed. This function is slated to be removed in a subsequent release.  

**[](http://fecload-update.fec.gov/cgi-bin/fecfile)****Build 8.1.0.1  
Release date – March 13, 2014**  
[  
](http://fecload-update.fec.gov/cgi-bin/fecfile)Updates:

*   FECPrint - Form 24 Schedule E "Total Independent Expenditures" now shows the correct value.
*   FECPrint - 24/48 Hour notice Memo Code "X" now shows in its correct location.
*   FECPrint - Image rendering performance has been improved with less memory usage.
*   FECCheck - Form 5, discontinued occupation and employer check for (removed) check-box "qualified non profit".

**  
Build 8.1.0.0  
Release date – January 14, 2014**  
[  
](http://fecload-update.fec.gov/cgi-bin/fecfile)Updates:

*   Form 5 - New "Original Amendment Date" field.
*   Form 5 - Removed field "Qualified Nonprofit Corporation".
*   Schedule E - New "Date of Dissemination" field.

**[  
](http://fecload-update.fec.gov/cgi-bin/fecfile)****Build 8.0.1.11  
Release date – December 17, 2013**  
[  
](http://fecload-update.fec.gov/cgi-bin/fecfile)Updates:

*   FECLoad - The upload settings (TCP/IP and SSL URL addressing) have changed.  

**Build 8.0.1.10  
Release date – June 12, 2013**  
[  
](http://fecload-update.fec.gov/cgi-bin/fecfile)Updates:

*   FECCheck - The Transaction ID maximum length (A/N-20) is now enforced.
*   FECLoad - The SSL Java session time-out has been extended.
*   FECLoad - The TCP/IP setting previously checked for proxy settings. This unnecessary check has been removed.  

**Build 8.0.1.9  
Release date – April 29, 2013**  
[  
](http://fecload-update.fec.gov/cgi-bin/fecfile)Updates:

*   FECFile is now compatible with Microsoft Windows 8.
*   Check Limits function has been updated with the current limits.The auto installation of FECFile will load the limits and the current committee list.
*   FECLoad - "File to test server.." check-box text has been changed from "...agency" to "...FEC"..
*   FECLoad - Upload output log text has been changed to clarify language for filer's not connecting to the electronic filling system while attempting to upload.
*   FECLoad - An icon in the taskbar is now shown when FECLoad is launched and running.

**Build 8.0.1.8  
Release date – June 26, 2012**  
[  
](http://fecload-update.fec.gov/cgi-bin/fecfile)Updates:

*   Form 1 - New second committee email box added.
*   Form 5/Schedule E - now displays aggregate.
*   Form 5/Form 3X - Independent Expenditure, Calendar Year-to-Date for election sought updated to not aggregate if either the Election Type or Election Year is not provided.
*   Schedule C - Last page totals now carry forward to Line 3 (Total Outstanding Loans) on the Schedule D.
*   Schedule C/D - Loan/Debt Accruals are now differentiated from Loan/Debt Payments by the letter “a” preceding the line number, and by a different color.
*   Schedule C/D - Partially forgiven Loan/Debts now display the Remaining Balance, Forgiven/Settled, and Forgiven Amount values, in the Loan/Debt Tab.
*   Schedule L - Line 4(e) Line 4 Total Field is now mapping correctly.
*   FECLoad - New auto SSL retry added if TCP/IP upload method fails.
*   FECPrint - Form 3X / F3P correctly plugs "Monthly" Report Type check box (MYE).
*   FECPrint - Schedule C1 "Due Date" mapping issue corrected.
*   FECPrint - Form 7.6 (each communication) now prints all transactions.
*   FECPrint - Form 7.6 (each communication) now prints memo transactions.
*   FECPrint - Updated the imager to allow and print the Section Symbol (§).
*   FECCheck - Form 9.4 (Federal Candidate List) Transaction ID fatal error resolved.

**Build 8.0.1.7  
Release date – March 2, 2012**  
[  
](http://fecload-update.fec.gov/cgi-bin/fecfile)Updates:

*   Form 5 - 24/48 Summary Totals now show correctly.
*   Form 3 - Mid-Year Report option removed from the report selection drop-down.
*   Form 3L - Coverage and election dates now reset when choosing/toggling between report types.
*   Schedule C1 - "Date Account Estab" is now outputting correctly for Form 3, Form 3X, and Form 3P.
*   Text corrected in the summary section of Form 5 receipts.
*   Loan forgiveness date now shows correctly.
*   ‘Next Entry’function now permits multiple transaction entry from Receipt/Disbursement Tab.
*   Check Limits function changed to not auto-launch on report upload.
*   FECCHECK - Schedule L "back-reference error" message now references the correct field number.
*   FECPrint - Form 3L Semi-Annual Codes now show marked correctly.

**Build 8.0.1.6  
Release date – January 13, 2012**  
[  
](http://fecload-update.fec.gov/cgi-bin/fecfile)Updates:

*   Date Picker/Date Field now allows tabbing out.
*   Form 3 - Monthly drop down options have been removed.
*   Form 3L - Date error corrected when choosing Semi-annual report type.
*   New Comments/Suggestions hyperlink to on-line Comments/Suggestions web form has been added to the "Help" tab.
*   New User Manual hyperlink to on-line FECFile User Manual has been added to the"Help" tab.
*   FECPrint - Form 3X /3P for Monthly filers now correctly checks the Monthly "YE" box.
*   FECPrint - Schedule C1 "Due Date" now prints correctly.
*   FECCheck - Erroneous Schedule H3 back-reference warning removed .
*   FECCheck - Form 1S failing error message added for records submitted blank.

**Build 8.0.1.5  
Release date – December 14, 2011**  
[  
](http://fecload-update.fec.gov/cgi-bin/fecfile)Updates:

*   Form 6 - Now supports in-kind transaction activity.
*   Lookup Database - Now downloads and decompresses correctly.
*   Software install - Installation process now checks for JAVA 6 (a minimum requirement).
*   FECPrint - Form 99 Imaging/pagination page count discrepancy corrected.
*   FECPrint - Form 3S, Section III and IV totals, now printing correctly.
*   FECPrint – Transaction text records now display correctly for Form 6.

**Build 8.0.1.4  
Release date – October 13, 2011**  
[  
](http://fecload-update.fec.gov/cgi-bin/fecfile)Updates:

*   Importing - PGI indicator imports all election codes.
*   Importing - Schedule B "Purpose Description" truncation corrected.
*   Form 1 - SSF chosen option is now retained in the report.
*   Loans/Schedule C - Corrected problem with previously forgiven loans.
*   Check Limits - Check Limits function now operates and checks against correct limits.
*   FECPrint - Form 2 candidate first name now appears.
*   FECPrint - Black command window now disappears when a print preview is executed.
*   Installation - FECFile no longer crashes after installation or auto-update on restrictive networks.
*   Proxy Setting - Settings modified via the menu bar are now stored correctly.

**Build 8.0.1.3  
Release date – October 6, 2011**  
[  
](http://fecload-update.fec.gov/cgi-bin/fecfile)Updates:

*   Date Picker has been updated to allow for manual data entry.
*   Form 3S/Form 3PS - Post Election Summary Page logic corrected to only display if the report ending coverage date is greater than election cycle end date.
*   Form 3 - Line 12 drop-down entity type is now open to all entities.
*   Form 4 – Column B Line 7 now outputs correct value.
*   FECPrint - Schedule H4 "Purpose" now printing correctly.
*   FECPrint - Schedule H4 Direct Candidate support now totals correctly for Federal portion.
*   FECPrint - Form 2 Candidate first name now displays.
*   Import Formats and import instructions have been updated to Version 8 specifications.
*   Import Fomats - Schedule B import issue corrected.

**Build 8.0.1.2  
Release date – September 26, 2011**  
[  
](http://fecload-update.fec.gov/cgi-bin/fecfile)Updates:

*   Form 24 - Is now amendable.
*   Form 6 - Is now amendable.
*   New welcome dialog box displays recent available data files (*.dcf) and allows an "Always open file" function.
*   Committee/Organization Fields have been expanded to accommodate 200 characters.
*   City Fields have been expanded to accommodate 30 characters.
*   A new calendar "date picker" function has been added.
*   Desktop icons have been replaced with FEC logo.
*   Form 3 Line 12 - "Individual" has been added to drop-down as possible entity type.
*   Form 3X Line 27 - Now accommodates interest rate and due date.
*   Schedule C - New partial loan forgiveness.
*   Next Entry Button - corrected to work as designed.
*   FECPrint - New PDF viewer with schedule navigation and enhanced functionality.
*   FECCheck - Updated validator with new rules associated with Forms 1, 2, 3Z, P, 5, 6, and 9\.
*   FECCheck - Updated validator with new rules associated with Schedules C, E, and F.
*   FECLoad - Updated security and new email auto-save.

**  
Build 7.0.1.2  
Release date – June 7, 2011**  
[  
](http://fecload-update.fec.gov/cgi-bin/fecfile)Updates:

*   FECPrint - Form 3S Summary totals mapping issue has been corrected.
*   FECPrint - Form 3X 12 Day Pre-Special abbreviation has been corrected (12S).
*   Schedule B - Beneficiary Fields are no longer flagged as warning errors.

**Build 7.0.1.0  
Release date – April 4, 2011**  
[](http://fecload-update.fec.gov/cgi-bin/fecfile)  
Updates:

*   Form 3P/3PS - Software has been enabled to collect and total unitemized contributions from "(a) Individuals/Persons Other Than Political Committees".
*   Validator (FECCheck) has been converted to an operating system independent Java platform. Java 5 or greater is now a minimum requirement.
*   FECPrint, Form 3P/3PS Detailed Summary Pages, has been updated to show totals for unitemized contributions from "(a) Individuals/Persons Other Than Political Committees".

**Build 6.4.2.2  
Release date – November 15, 2010**  
[](http://fecload-update.fec.gov/cgi-bin/fecfile)  
Updates:

*   Form 5 24/48 Report - now outputs the Line 7 "Total Independent Expenditures" amount.
*   Auto-update feature - corrected a problem where the software would not recognize that an update had been issued.
*   Auto-update feature - Auto-update becomes active this version. Existing FECFile users will no longer have to perform a hard software install when an update has been issued.

**Build 6.4.2.1  
Release date – October 12, 2010**  

NOTE!  
Form 5 has changed! The methodology for creating Form 5s (Quarterly and 24/48 Hour Reports) and adding transactions has been updated. Older, previously filed, Form 5s in your data set may have also been altered. Please call the FEC Electronic Filing Office if you have any questions.  
Updates:

*   Form 5 has been updated , there is a new process for creating and adding transactions.
*   Form 5 - 24/48 Hour Reports can now be created without coverage dates. Those reports will no longer affect creation of regularly scheduled Form 5 reports.
*   Form 5 - Schedule E "Calendar Year-To-Date Per Election for Office Sought" aggregates correctly.
*   Two new Committee Types have been added: Joint Fundraising Committee (Authorized) and Joint Fundraising Committee (Unauthorized).
*   When printing transactions, FECFile no longer cuts off or skips entries.
*   The Print Preview screen now shows the toolbar.

**Build 6.4.2.0  
Release date – June 1, 2010**  

Note: Any previous version of FECFile must be uninstalled prior to installing the updated version.  
Updates:

*   FECFile is now compatible with Microsoft Windows 7\.
*   New "auto-update" feature simplifies the software update process.
*   New look (tab displays replace window pane views, new toolbar ICONs, more).
*   Corrected aggregate summing on Form 5 contribution/expenditure totals.

**Build 6.4.1.2  
Release date – July 8, 2009**  
Updates:

*   FECPrint - Form 3, corrected Summary Page mapping issue on Line Numbers 6-10\.

**Build 6.4.1.1  
Release date – June 25, 2009**  
Updates:

*   New set-up splash screen.
*   Corrected aggregate rounding problem.
*   Form 3L - corrected Report Codes for validation.
*   Form 3L - changed FECPrint to not display "0.00" in amount fields with empty values.
*   FECPrint - moved Text Record, associated with the report, to print after the signature page.
*   FECPrint - transaction Text Records now print "A.","B.","C.",…etc., corresponding to its transaction.

**Build 6.4.1.0  
Release date – May 14, 2009**  
Updates:

*   New Form 3L, Report of Contributions Bundled by Lobbyists/Registrants and Lobbyist/Registrant PACs.
*   Removal of Form 3Z-1 and other related Millionaire’s Amendment fields.
*   Expanded transaction "Description" fields from 40 to 100 characters.
*   FECPrint - relocated transaction Text Records to print on the page following the transaction.
*   FECPrint - relocated report Text Record to print on the page following the last summary page.
*   Corrected Form 3 "Election State" field to output correctly.
*   Corrected problem where Schedule H4 "names" were importing blank.

**Build 6.3.1.1  
Release date – March 10, 2009**  
Updates:

*   Corrected a problem where all transactions would auto-itemize.

**Build 6.3.1.0  
Release date – March 10, 2009**  
Updates:

*   Form 1 updated for Lobbyist/Registrant regulations.
*   Values display correctly for summary pages, Form 3 and Form 3PS, sections III/Column C and IV/Column C.
*   New "Go to Page Number" function when viewing a report.

**Build 6.2.1.0  
Release date – June 9, 2008**  
Updates:

*   New data converter tool for importing (.csv to ASCII 28).
*   Revised import instructions and made clarifications on the import layouts.
*   Changes to Form 1 (new fields).
*   Changes to Form 9 (new fields).
*   Schedule H6 - output mapping of Act/Event corrected .
*   Form 1 - "None" has been removed as a type of connected organization.
*   Form 3X, Line 16 - In-Kind check-box removed.
*   Percentage outputs corrected for mapping and made consistent across all forms and schedules.
*   Year-End Report for Monthly filers will now print the correct check-box.
*   Removed previous filing ID field from the "Close report" process.
*   Form 3Z-1 pop-up updated and can now be filed with any report.
*   Back-Reference fields are now populated for transaction splits.
*   Schedule C - added "Memo" check-box.
*   Schedule C - added "Personal funds" check-box.
*   Form 3X, Schedule B refunds - added “Refund to Prior Calendar Year’s Receipt.”
*   Form 3, Schedule B refunds - added “Refund to Prior Election Cycle Receipt.”
*   Form 3P, Schedule B refunds - added “Refund to Prior Election Cycle Receipt.”
*   Schedule L - “Beginning COH” now carries forward from previous Year-End reports.
*   Schedule L - Column B totals now appear instantly, no longer after closing the DCF and re-opening.
*   Affiliated Committee pop-up added.
*   Redesignation transactions now generated as memo.
*   Schedule B - Beneficiary validation removed.
*   Merge Names feature to include middle name exception to prompt if one middle name is blank.
*   FECLoad - Background status window modified to be more descriptive.
*   FECPrint, Form 3P - Added the “-P” to the schedules to reflect the paper rendition.
*   FECPrint - Text Record Description modified to avoid overlapping TranID.
*   FECPrint, Schedule C2 – Guarantor State field now maps correctly.
*   FECPrint, Schedule C/C1 – Convert all loan percentage decimals to percent values (.0450 è 4.5%).
*   FECPrint Form 6 – Added “Electronically Filed by” to signature .

#### **Build 6.1.1.3  
****Release date – January 24, 2008**

Update:

*   Merge feature corrected so that like records merge properly (state codes).

#### **Build 6.1.1.2  
****Release date – January 17, 2008**

Updates:

*   Corrected an import problem where data fields were importing offset.
*   Form 3Z-1 now can be created and submitted with any report that contains "12/31" or "6/30" in its coverage period prior to the candidate's General Election. Pop-up reminder message only appears on Year-End and July Quarterly Reports.
*   District codes now output with preceding "0" if the district code is 1-9\.
*   Schedule B CCM/CAN (candidate committee/candidate) now outputting to correct data fields.
*   Form 24 aggregate feature removed.
*   Campaign committees now able to link a candidate to committee in the Individuals/Organizations.
*   Schedule L now outputting Field Column A "11\. Ending Cash on Hand".
*   Software installation now retains existing upload settings from previous version.
*   Schedule H4 activity check-boxes now print correctly.
*   Form 1, Name Change and Address Change Check-boxes, now print correctly.
*   Corrected schedule titles on the printed Form 3P.
*   Form 9, Employer and Occupation Fields are now printing.

#### **Build 6.1.1.1  
****Release date – January 2, 2008**

Updates:

*   New software splash screen.
*   New Form 5.
*   New Form 9.
*   “Update Committee List” feature has been enhanced. It now contains and loads current contribution limits in addition to the FEC master committee list.
*   New transaction check-box to force aggregate memo activity on Schedule A and Schedule Es.
*   Added text description “H4” to the summary page line number 21B.
*   Corrected leading space problem in memo text created by a forgiven loan.
*   Terminated committees are now removed from the FEC download Committee List.
*   Corrected Form 3P run-time error on new disbursements window.
*   Added presidential category code to validation for Form 3P, Schedule B.
*   Corrected FECFile data output to read “11AI”, instead of “11A1”.
*   Field 27 of Schedule C, if populated in the .fec output file, will now show “13”.
*   Removed duplicate primary/general options listed in transaction pull-down.
*   New pop-up encourages F3 filers to change election cycle on Year-End Reports of even years.
*   Schedule E aggregate totals now aggregate accurately based on calendar year per election and office sought.
*   Changed default location for the validator output file.
*   Added “Recount” to the primary/general pull-down options.
*   Added feature to auto-archive, if an archive folder exists.
*   Added military state codes to transaction pull-down.
*   FECFile output now eliminates the requirement for quotes around text.
*   FECFile output now contains separate fields for all names components (last, first, middle, prefix, suffix).
*   FECFile now outputs district codes always as two digits.
*   Corrected regulation citation in the “Personal Funds” pop-up to reflect “100.33”.
*   Corrected the F1 “None” functionality to not replace Authorized Committees with the word “None”.
*   Import formats have been updated to meet Version 6.1 specifications.
*   Schedule F interface corrected to only allow the entry of a Designated Committee or a Subordinate Committee per transactions.

#### Build 5.3.1.2  
Release date – June 20, 2007

Updates:

*   Aggregate totaling problem from Build 5.3.1.1 corrected.

#### Build 5.3.1.1  
Release date – June 8, 2007

Updates:

*   Validation output file error corrected (temp file now defaults to FECFile folder, instead of the root directory).
*   MS Vista compatible

#### Build 5.3.1.0  
Release date – February 6, 2006

Updates:

*   Check Limits function updated with current contribution limits.
*   Help function hyperlink updated with the current FEC web site address for obtaining user manuals.
*   Corrected the spelling of "Massachusetts" in the state drop down of the Individuals/Organizations function.
*   FECPrint viewer corrected to prevent overlapping of text for larger filings.
*   FECPrint viewer corrected to accommodate scrolling for large filings (missing scroll bar).

#### Build 5.2.0.1  
Release date – February 10, 2005

Updates:

*   F3X, line 11i and 11ii Column B totals, now show on the printed report.
*   F1 now has a 'Signed By' field so that the report can be signed by the assistant treasurer.
*   The Schedule H1 check-boxes can now be used and selected even if 50% is selected.

**Build 5.2.0.0  
Release date – February 2, 2005**

Updates:

*   Validation routine will run, even if the election cycle field is not filled in on Form 99 and Form 1.
*   Form 99 – A carriage return may now be used when entering memo record information in the Form 99.
*   Form 3P no longer requires a state to be selected when creating a report. However, the option to enter a state remains as part of this transaction entry.
*   The error message associated with transaction and name imports is more descriptive to support proper use of new name fields.
*   Printed reports are improved to address some text, content, and format issues.
*   General print parameters now print 10 transactions / names per page, rather than 20 to assure universal support for all printer types.
*   F1 (Agent/Affiliate Window) defaults to: “Business, Financial institution…” entity type, when adding a new affiliation.  This makes it possible to enter “None” or other user text if there is no match in the list/search box.
*   Category Code for Form 99, now excludes “Conduit Type – MSJ” from the list of category codes.
*   Cloning for in-kind transactions is no longer allowed. Due to the complexity of in-kind transactions, these are to be directly entered. Note: Probable cause of "run-time error" issue, experienced with the deleting of cloned in-kind transactions.
*   Refund calculation for Schedule A has been modified so that if a refund to an entity is created, then the aggregate of that entity will be reduced by the refund amount.
*   Schedule L now provides a delete function and will also be automatically amended when filers amend the parent report.
*   A new search function allows filers to search transactions based on a text matching search, present the results in a separate window, and work with the search results as though in the “All Transactions” window.
*   Support for loan handling has been enhanced.  When a loan is forgiven or the forgiven status rescinded (as indicated by checking or un-checking the forgiven box on the loan screen) the system automatically generates a memo noting the action.
*   Joint Fundraisers on Form 2, are selectable in the drop down list as “PAC/Affiliated”.
*   The FEC ID label for the information entry screens now changes to match information needed for each selectable drop down item (e.g., Candidate ID for drop down item “Candidate”).
*   The system now routes committees to complete committee information before proceeding to enter reports.
*   A Miscellaneous Document is now also labeled as Form 99 in the form type menu.
*   The screen now remains at a transaction, (after the transaction is selected for viewing or modification), instead of returning to the top of the list of transactions.
*   The validator has been updated to include new forms and checks including embedded quotes and federal funds total checks.
*   When an unauthorized committee is entering their committee information the “Authorized Candidate Field” is grayed out since it not applicable.
*   The upload function, and the .ini has new default URLs for SSL and direct connections, linking with enhanced server sites for FEC filing.
*   The import function is updated to import the description field for H4s, and to exclude an extra field in Schedules A/B.
*   Schedule L allows creation of a receipt from the ‘View Receipt’ page.
*   Line # 30a and 30b are included in the choices for loan/debt payments.
*   Software includes the recent changes to the Schedule H Series.
*   User manuals have been updated (not yet posted).
*   The 'None' radio selection will auto-fill the name with "None" on F1/F2.
*   The Debt Owed By Committee now prints on the correct line number (10).
*   Loans Made now generates a memo text when forgiving a loan.
*   The dial-up string for the test server now reflects the correct number.
*   When the 'Open All' option is selected on the menu bar, all windows in FECfile now open.
*   The Due Date For Loans is free text and prints correctly.
*   The HDR version in the output *.fec file reflects 5.2 as the filing format.
*   'Public Communications' now added as an event type.
*   The spelling of the word 'FUNDRAISER' has been corrected on the printed form of Schedule H2.

#### **Build 5.1.2.0  
Release date - January 21, 2004**

Updates:

*   "Copy All" function in Committee Lookup populates Organization field for non-individuals rather than Last Name field.
*   "Print Preview" function works from all the transaction views

**Build 5.1.1.0  
Release date - January 7, 2004**

Updates:

*   "Names" format change implemented for improved query and clarity - format Version 5.1
*   F3P expenditure state allocation added.
*   Form 2 can be amended.
*   Form 1 candidate state is picked up from Candidate name information if Committee information is blank.
*   Form 99 codes updated.
*   Memo text update now indicates that the file needs to be saved.
*   Partnership records can be entered even if the date range falls in the period of a closed report.
*   Check number and account identifier added to SA/SB.
*   Debt-to-payments itemization problem corrected.
*   24 hour notices show the aggregates.
*   Obsolete loans/debts/accruals no longer show in the loans and debts window.
*   F3P verbiage changed to improve clarity.
*   Clipboard size for copying Validator window increased
*   SC/1 allows interest rate to be alphanumeric (like SC).
*   F99 text limit increased: 20,000 characters.
*   Software help content removed, replaced with a reference to the user manual on the FEC web-site.
*   Download Menu item reads "Update Committee List."

**Build 2.0  
Release date - July 2, 2003**

Updates:

*   Disabled ability to open and work from READ ONLY data files.
*   Updated F99 Document Type codes.
*   Added reminder pop-up message upon closing report for F3Z-1 filers.
*   Enabled text copy and paste from FECheck (validator) output.
*   Revised H4 print presentation to sort transactions by event first, then by date, then by order entered into software.
*   Improved ability to enter multiple account names for softmoney accounts.
*   Limited transactions per page on schedules from 20 to 10 to prevent  
    truncation during printing.
*   Enabled 'Cash on Hand' for F3X to display in Column B when no other  
    activity is reported.
*   Corrected F3X Column B 18(a) and 18(b) totaling bug.
*   Corrected bug that continued reporting Debt/Loan after being forgiven.
*   Corrected H4 bug that duplicated the event type within the description field.

**Build 1.0  
Release date – April 10, 2003**

Updates:

*   Corrected F3X Line 21a (H4) totaling error.
*   Corrected F3X summary page column b line 20 totaling error.
*   Enabled error/warning descriptions for FECheck5 validation output.
*   Disabled ability to delete special events.
*   Disabled ability to create in-kind SA/SB in SL.
*   When importing from DCF 4 Changed Admin/Voter drive from dcf 4 to Administrative.
*   Category code values updated.
*   Enabled Schedule F memo text to be created, viewed and printed.
*   Updated warning message received when user tries to modify a closed report to read: "This report is already closed…" instead of "This report is already filed…."

**Build 0.0  
Release date – March 14, 2003**  
Bipartisan Campaign Reform Act (BCRA):

*   SL has been added.
*   F3X has been updated with the new summary page with SL, line 18 and line 30\.
*   Schedule H5 and H6 have been added to F3X.
*   Schedule H1 modified to reflect version 5 BCRA layout.

Updates:

*   F3 has 3Z-1 right click option to generate 3Z-1\.
*   SA has increased limits for F3s; SB has Refund check box.
*   Form 99 can select Document type.
*   Category code has been added to all the expenditures.
*   Schedule F has "Increased limits" checkbox.
*   You can add Schedule F to F24 now.
*   New system events for Generic Voter Drive and Exempt activity added.  
    Administrative/Voter Drive has been modified to reflect only Administrative.
*   YE does not select default dates.
*   Form 2 fax number has been added

Page last updated June 7, 2017
