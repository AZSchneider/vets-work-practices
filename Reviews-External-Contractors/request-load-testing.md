# Load Testing -- IN PROGRESS

* **This document applies only to External Contractors.**

* **Definitions for terms used in this folder:**

  * *"DSVA" refers to DSVA team members and DSVA detailees.*

  * *"Internal contractors" refers to DSVA's primary vendor contractor (e.g., AdHoc) and its subcontractors.*

  * *"External contractors" refers to any other contractor team working on the Veteran Tools Platform.*

<hr>

* [General](#general)
* [Prepare for Load Testing](#prepare-for-load-testing)
* [Request for Load Testing](#request-for-load-testing)

<hr>

### General

* All applications (and new features for existing applications) on the Veteran Tools Platform need to go through load testing.
* **Do not perform load testing without explicit approval from DSVA** -- a DSVA devops engineer is required to coordinate and perform your load testing.
* **External Contractor teams should initiate the Request for Load Testing** 
  * When the complete and final build is on staging and you're confident it's ready to launch
  * At least 1.5 weeks prior to launch

<hr>

## Prepare for Load Testing

For reference, you can [review existing load tests here](https://github.com/department-of-veterans-affairs/devops/tree/master/loadtest).

After you submit the request for load testing, a DSVA devops engineer will work with your team to define what load tests to write, what they should include, and how to conduct the load test under DSVA supervision.

<hr>

## Request for Load Testing

1. File an issue in ```vets-team repo```.
    * Title: ```Request for Load Testing```
    * Labels:
      * ```loadtest```
      * ```external-request```
      * ```[your team's Github label]```, e.g., "BAH-526"
    * Assign the issue to: ```[your DSVA contact]```
    * Comment: Include the following information.
      * **Context**: Provide a high-level description of the functionality involved in this request, for example:
        * ```Functionality adds a new dataset to the Facility Locator so users can search for and view non-VA health providers on the map, as well as in list and detail views.```
      * **URL**: ```link to your project on staging```
1. **Within 2 business days**, DSVA will contact the person who created the Github Issue to coordinate the load testing.
    * If you don't hear anything after 2 business days, reach out to your DSVA Contact.
1. DSVA will collaborate with your team to set up and perform the load test.
1. DSVA will close the Github issue when the load testing is complete.
1. When the issue is closed, Github will send a notification to the issue creator. This is your team's signal that this pre-launch activity is complete.
