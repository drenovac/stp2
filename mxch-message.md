
# Here's some more information on Single Touch Payroll (STP) phase 2.
Remember, the ATO's XML message implementation guide (MIG) can be found on [the SBR website](https://mktg.messagexchange.com/e/509431/mployer-obligations-eo-PAYEVNT/qppcfs/1114704571?h=I7U0AFDzbymXHWJmBdxP2IJY-S3BeKxK98FY0zEgsEI).

## Here's what we suggest doing next:
Firstly, read over [our FAQs](https://mktg.messagexchange.com/e/509431/-discussions-topics-7000041289/qppcfv/1114704571?h=I7U0AFDzbymXHWJmBdxP2IJY-S3BeKxK98FY0zEgsEI). Then:

1.	**Make the changes needed to your software**
You can find the changes required in the message implementation guide (MIG) and the business implementation guide (BIG).

2.	**Get whitelisted for PAYEVNT.0004 and start testing against the External Vendor Testing Environment (EVTE)**

If you haven't already, add PAYEVNT.0004 as a new service for your existing product through DSP online. Make sure you use your test ProductID (not your production ProductID). Contact us if you need to confirm your MessageXchange testing details, such as endpoint and credentials. 
o	If you submit the XML through API: Change the <action> within the <metadata> to reference "Submit.004.00" or "Update.004.00"
o	If you submit the XML through sFTP: If you're providing us with <metadata> in the STP XML, please change it to reference "Submit.004.00" or "Update.004.00"

3.	**Request entry to Extended Conformance Testing (ECT) by submitting a ticket to the Digital Partnership Office (DPO)**

Once approved, you'll be provided with test cases to execute in the next step.

4.	**Undertake ECT**
Ensure you successfully complete the test cases the ATO has provided you.
5.	**Wait for ECT results to be reviewed**

The ATO will review them and let you know, via the ticket you raised in step 3, when it's been completed.

6.	**Be notified of production whitelisting**

The DPO will confirm successful testing and let you know when your product has been whitelisted for production.

## These documents might be of use to you:

•	**The ATO PAYEVNT.0004 2020 Business Implementation Guide (BIG)**

[Find it here on the SBR website](https://mktg.messagexchange.com/e/509431/mployer-obligations-eo-PAYEVNT/qppcfs/1114704571?h=I7U0AFDzbymXHWJmBdxP2IJY-S3BeKxK98FY0zEgsEI)
This should help you understand the business requirements and design of functionality for STP phase 2 software products and services.
•	**The STP Phase 2 Extended Conformance Testing (ECT) Guide**
[Find it here on the Developer portal](https://mktg.messagexchange.com/e/509431/laborate-display-DSD-STPPhase2/qppcfz/1114704571?h=I7U0AFDzbymXHWJmBdxP2IJY-S3BeKxK98FY0zEgsEI)
This assists DSP/SSPs to understand ECT requirements and how to incorporate into your development and testing cycles.
•	**Our list of frequently asked questions (FAQs)**
[Find them in this article](https://mktg.messagexchange.com/e/509431/-discussions-topics-7000041289/qppcfv/1114704571?h=I7U0AFDzbymXHWJmBdxP2IJY-S3BeKxK98FY0zEgsEI)
This answers a lot of the questions we've received so far. Just let us know if you have others, and we can add them.