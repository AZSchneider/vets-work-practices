# Getting Started with Developer Documentation

To build a service on the Veteran Tools Platform, which can be anything from a digital form to a map-based facility locator, developers will create a Frontend experience in React on Vets-Website, and connect it to an Integration on Vets-API, which manages the data flow to and from VA systems.

<hr>

* [Getting started](#getting-started)
* [Development](#development)
* [Getting help](#getting-help)

<hr>

## Getting started

1. Confirm that your team Project Manager has added your name, email address, and Github username to the team spreadsheet and sent it to DSVA. You'll know when you can visit [this Github repo and see the content](https://github.com/department-of-veterans-affairs/vets.gov-team).

1. Follow the steps to <a title="go to create ssh keys" href="https://github.com/department-of-veterans-affairs/vets-work-practices/blob/master/Onboarding-External-Contractors/request-access-to-tools.md#additional-onboarding-steps-for-developers">create new SSH keys, configure, and test the SOCKS proxy</a>.

1. Verify that you have
    * Access to the [Veteran Tools Platform code repositories](#code-repositories)

    * Credentials for the shared testing environments &mdash;  <a title="go to dev.vets.gov" href="https://dev.vets.gov" target="_blank">dev.vets.gov</a> and <a title="go to staging.vets.gov" href="https://staging.vets.gov" target="_blank">staging.vets.gov</a>

    * Access to [Internal Tools](internal-tools-access.md)
      * **Tip**: If you have a problem or can't get access, reach out to your DSVA Contact.

1. Review all the content the Vets Developer Docs section (everything after this page).

1. Review the frontend documentation for <a title="Go to Vets-Website readme" href="vets-website/vets-website-readme.md" target="_blank">Vets-Website</a>.

1. Review the backend documentation for <a title="Go to Vets-API readme" href="vets-api/vets-api-readme.md" target="_blank">Vets-API</a> (including the section named "Integration Overview").


## Development

#### Code repositories

The Veteran Tools Platform is broken into three parts:

1. <a title="Go to Vets-Website" href="https://github.com/department-of-veterans-affairs/vets-website" target="_blank">Vets-Website</a>, which contains frontend applications and components users interact with

1. <a title="Go to Vets-API" href="https://github.com/department-of-veterans-affairs/vets-api" target="_blank">Vets-API</a>, a JSON-based API used by the frontend to provide data to and from VA systems

1. <a title="Go to Vets-JSON-Schema" href="https://github.com/department-of-veterans-affairs/vets-json-schema" target="_blank">Vets-JSON-Schema</a>, which contains shared resources used to structure and validate form data between Vets-Website and Vets-API.


### Internal Tools

To access metrics, build logs, deployment information and exception details, see the the [Internal Tools](internal-tools-access.md) documentation.


## Getting help

DSVA engineering resources are available to provide guidance and support through the development effort.

If you encounter issues or have any questions, raise them in your team's Slack channel or reach out to your DSVA Contact.

<hr>

Back: [Welcome](README.md)

Next: [Environments](environments.md)
