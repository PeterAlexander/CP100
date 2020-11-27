











 <img src=".//media/image35.jpeg" style="width:5.135in;height:2.2425in" /
 How to Perform a SAP Cloud for Customer Integration with SAP Marketing
 Cloud Business Scenario


 We want to change a business partner in the SAP Sales Cloud (1). This
 changed record is processed via a predefined iFlow (2) and sent to the
 SAP Marketing Cloud (3) where the customer is automatically changed as
 well.



 After the exercise: Set Up Your Training Environment you are logged in
 to Common Training and have created and logged in to two connections:

-   dx-s4c1911-sactest

-   dy-ecc617ciscc-\#\#\#\#



#### 1.  Choose dx-s4c1911-sactest.
   1.  Choose *dx-s4c1911-sactest* as your desktop.

#### 2.  Log on to three different SAAS apps.

 In the next steps you will log in to 3 different SaaS applications via
 the browser. To make navigation easier for you, Windows tiles have
 been created for this purpose.

1.  Click on the window symbol on the bottom on the left side.

2.  ![](.//media/image36.jpeg)Click on the arrow.

3.  Find the Tiles SAP CPI – v0536 (1), SAP Hybris Marketing Cloud (2),
    and SAP Sales Cloud (3).

 ![](.//media/image37.jpeg)

1.  These are:

    1.  Number 1 = https://v0536-tmn.avt.eu1.hana.ondemand.com/itspaces.

    2.  Number 2 = https://wdflbmt7189.wdf.sap.corp/ui.

    3.  Number 3= https://my331933.crm.ondemand.com.


1.  Configure the SAP Cloud Integration
Use the following data:

<table
<thead
<tr class="header"
<thField</th
<thValue</th
</tr
</thead
<tbody
<tr class="odd"
<tdUrl</td
<tdhttps://v0536-tmn.avt.eu1.hana.onde- mand.com/itspaces</td
</tr
<tr class="even"
<tdUsername</td
<tdP1942636339</td
</tr
<tr class="odd"
<tdPassword</td
<tdWelcome4</td
</tr
</tbody
</table



1.  You are logged on to the training landscape, see previous task.

2.  ![](.//media/image38.jpeg)Log on with the window tile *SAP
    CPI-v0536* as described before. Optionally you can insert the URL
    above to log in with your Browser.

3.  Click the design symbol (Pen) to change to the *Design* view.

4.  ![](.//media/image39.jpeg)In the *Search* bar, search for *SAP Cloud
    for Customer Integration with SAP Marketing*.

5.  Find and click on the row *SAP Cloud for Customer Integration with
    SAP Marketing*.

6.  Choose the *Artifacts* tab.

 ![](.//media/image40.jpeg)

1.  Find *Replicate Business Partner to SAP Marketing* and choose
     *Configure* at the *Action*

 ![](.//media/image41.jpeg)button

1.  In the pop-up window choose the *Receiver* tab.

 ![](.//media/image42.jpeg)

1.  Within the drop-down box in the Receiver tab, choose **yMKT** as
     *Receiver*.

2.  Check if the *Protocol-Hostname-Port* is
     *https://c4chyb2t77.tdc.sap.com/dx-s4c1911- sactest-wdflbmt7189*.

3.  Do not change anything else and click on *Deploy*.

4.  On the bottom of the left side, click on the *Operations View* icon.

 ![](.//media/image43.jpeg)

1.  Click on the *All* tile to see if your iFlow is started.

 In the training situation you cannot see which of the starting iFlow
 is yours because the only difference is the different receiver.

 ![](.//media/image44.jpeg)

### 1.  Change the Business Partner Name in SAP Cloud for Customer and SAP
### Sales Cloud.
Use the following data:

![](.//media/image2.png)

1.  You are logged on to the training landscape, see the step before.

2.  Log on with the window tile SAP Sales Cloud as described before.
     Optionally you can insert the URL above to log in with your
     Browser.

3.  Navigate to *Customers* → *Individual Customers*.

 ![](.//media/image45.jpeg)

1.  Click on one of the listed Individuals.

2.  ![](.//media/image46.jpeg)In the *Detail* page click on the *pen* to
    edit a data record.

3.  Save your changes.

4.  The data message will be sent automatically to the iFlow in the CPI.


### 1.  Check the Message iFlow Use the following data:



1.  If not already there, log on to the CPI Tenant as you did before.

2.  Navigate to the *Operations View* and click on the *All* tile .

3.  ![](.//media/image47.jpeg)As you cannot see, which of the starting
    iFlow is yours, click on the first iFlow and on the detail Page
    click on the link *Monitor Message Processing*.

4.  You will see a message with status **Completed**.

5.  ![](.//media/image48.jpeg)Click on it to see details.



### 1.  Check the changed Business Partner Data in SAP Cloud for Marketing
     Use the following data:


1.  You are logged in to the training landscape *dx-s4c1911-sactest*,
    see the step before.

2.  Log on with the window tile SAP Hybris Marketing Cloud as described
    before. Optionally you can insert the URL above to log in with your
    Browser.

3.  In your browser, log on to the *SAP Cloud for Customer* with URL,
    user and password mentioned above.

4.  Choose the *Contacts and Profiles* tab

5.  ![](.//media/image49.jpeg)Click on the *Contacts* tile.

6.  Search for the name of your customer.

 ![](.//media/image50.jpeg)

1.  ![](.//media/image51.jpeg)Choose *Personal Data* to check its
    details. Note, that the changes are made.

## LESSON SUMMARY

 You should now be able to:

-   Detect the position of your company in terms of culture, team,
     process and white criteria. With the help of the matrix, you can
     now sketch your goals and how to get there

 Learning Assessment
===================

1.  Cloud native is a service based architecture to solve business
    requirements.

 *Determine whether this statement is true or false.*

 True

 False

1.  What are the three types of corporate culture?

 *Choose the correct answers.*

1.  Agile

2.  Open

3.  Resilient

4.  Cloud native

5.  Waterfall


1.  What are possible deployment models?

 *Choose the correct answers.*

1.  Community cloud

2.  Public cloud

3.  Hybrid cloud

4.  Private cloud


1.  What are the three core processes of IT value creation?

 *Choose the correct answers.*

1.  Operate

2.  Automate

3.  Scale

4.  Implement software

5.  Create software


1.  All hardware maintenance and configuration is done in a fully
     automated way by your cloud provider's platform.

 *Determine whether this statement is true or false.*

 True

 False

<img src=".//media/image1.png" style="width:0.39289in;height:0.22548in" / Learning Assessment - Answers
========================================================================================================

33
--

1.  Cloud native is a service based architecture to solve business
    requirements.

 *Determine whether this statement is true or false.*

 True

 False

 This is correct. Cloud native is a service based architecture to solve
 business requirements.

1.  What are the three types of corporate culture?

 *Choose the correct answers.*

1.  Agile

2.  Open

3.  Resilient

4.  Cloud native

5.  Waterfall

 This is correct. Correct are waterfall, agile and cloud native.

1.  What are possible deployment models?

 *Choose the correct answers.*

1.  Community cloud

2.  Public cloud

3.  Hybrid cloud

4.  Private cloud

 This is correct. All answers are correct.

1.  What are the three core processes of IT value creation?

 *Choose the correct answers.*

1.  Operate

2.  Automate

3.  Scale

4.  Implement software

5.  Create software

 This is correct. The three core processes are: create software,
 operate and scale.

1.  All hardware maintenance and configuration is done in a fully
     automated way by your cloud provider's platform.

 *Determine whether this statement is true or false.*

 True

 False

 This is correct. The statement is correct.
