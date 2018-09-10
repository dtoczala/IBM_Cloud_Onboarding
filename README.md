# Welcome to IBM Cloud Onboarding
The IBM Cloud can be complex and somewhat overwhelming, but we're here to help you make sense of it.  This is a technically focused set of pages that will allow you to more easily onboard and effectively use the technology, see the latest best practices, and help you master the IBM Cloud.

# Contents
- **[Introduction - Getting Started](https://github.com/dtoczala/IBM_Cloud_Onboarding/tree/master#introduction---getting-started)**
  - [Cloud Basics](https://github.com/dtoczala/IBM_Cloud_Onboarding/tree/master#cloud-basics)
  - [Organization of the Materials](https://github.com/dtoczala/IBM_Cloud_Onboarding/tree/master#organization-of-the-materials)
- **[IBM Cloud Onboarding for Strategists](https://github.com/dtoczala/IBM_Cloud_Onboarding/tree/master#ibm-cloud-onboarding-for-strategists)**
  - [Account types on the IBM Cloud](https://github.com/dtoczala/IBM_Cloud_Onboarding#account-types-on-the-ibm-cloud)
  - [Setting up a Functional ID for your Account Owner](https://github.com/dtoczala/IBM_Cloud_Onboarding#setting-up-a-functional-id-for-your-account-owner-see-admin)
  - [Federation of your IBM Cloud ID's](https://github.com/dtoczala/IBM_Cloud_Onboarding#federation-of-your-ibm-cloud-ids)
  - [Security Models](https://github.com/dtoczala/IBM_Cloud_Onboarding#security-models)
  - [Project types and IBM Cloud Usage](https://github.com/dtoczala/IBM_Cloud_Onboarding#project-types-and-ibm-cloud-usage)
- **[IBM Cloud Onboarding for Administrators](https://github.com/dtoczala/IBM_Cloud_Onboarding/tree/master#ibm-cloud-onboarding-for-administrators)**
  - [Setting up a Functional ID for your Account Owner](https://github.com/dtoczala/IBM_Cloud_Onboarding#setting-up-a-functional-id-for-your-account-owner)
  - [Naming Conventions](https://github.com/dtoczala/IBM_Cloud_Onboarding#naming-conventions)
  - [Administrative Tasks](https://github.com/dtoczala/IBM_Cloud_Onboarding#administrative-tasks)
  - [Suggested Documentation](https://github.com/dtoczala/IBM_Cloud_Onboarding#suggested-documentation)
- **[IBM Cloud Onboarding for Users](https://github.com/dtoczala/IBM_Cloud_Onboarding/tree/master#ibm-cloud-onboarding-for-users)**
  - [How to Get an IBM ID](https://github.com/dtoczala/IBM_Cloud_Onboarding#how-to-get-an-ibm-id)
  - [Choosing Services](https://github.com/dtoczala/IBM_Cloud_Onboarding#choosing-services)
  - [Joining Projects](https://github.com/dtoczala/IBM_Cloud_Onboarding#joining-projects)
  - [Account Context](https://github.com/dtoczala/IBM_Cloud_Onboarding#account-context)
  - [Educational Resources](https://github.com/dtoczala/IBM_Cloud_Onboarding#educational-resources)

---
# Introduction - Getting Started
You want to work on the IBM Cloud - but you want to be smart about what youy are doing.  We're here to help.  This is a collection of best practices and guidance on how to best administer, govern, configure and have your users onboard onto the IBM Cloud.  We're doing this as an open project on GitHub so we can share these practices with the wider community of IBM professionals and our customers.  Please feel free to contact [Daniel "Tox" Toczala](mailto:dtoczala@usibm.com), if you would like to contribute to this project.

The IBM Cloud is rapidly evolving and changing to better meet the needs of our customers.  If you have topics or subjects that you would like to see addressed here, please open an issue for this project, so we can have other community members begin to contribute and address these areas.

## Cloud Basics
The IBM Cloud has two major components, and it is good to have a basic understanding of both.   The first model is based on Cloud Foundry.  The [Cloud Foundry access model](https://console.bluemix.net/docs/iam/cfaccess.html#cfaccess) is a framework for establishing a hierarchy of user access and security roles for an organization.  It is based on a hierarchy of conceptual groupings, with the **Account** at the top, which may have one or more **Organizations** which belong to the **Account**.  Each **Organization** may have one or more **Spaces** which are associated with it.  Each Account/Organization/Space represents a working environment.

The IBM Cloud started out with ONLY the Cloud Foundry model, but now also has support for a [IAM (IBM Cloud Identity and Access Management)](https://console.bluemix.net/docs/iam/users_roles.html#userroles) which uses the concept of Resource Groups and Access Groups to provide user access and security controls.  

### References for Further Reading
- [Signing Up for the IBM Cloud](https://console.bluemix.net/docs/account/adminpublic.html#signing-up-for-ibm-cloud) - Documentation on getting started.
- [Bluemix and Watson – Getting started right](https://developer.ibm.com/dwblog/2017/ibm-cloud-bluemix-watson-new-customers/) - a good primer on getting started with IBM Watson services on the IBM Cloud.
- [IBM Cloud – Identity and Access Management](https://github.com/jamesbeltonIBM/IBMCloudIAM) - An EXCELLENT beginner’s guide to understanding IAM written by [James Belton](https://github.com/jamesbeltonIBM).  My recommendation for the place to start when attempting to understand IAM on IBM Cloud.
- [Bluemix CLI Commands for Managing Keys and Policies](https://console.bluemix.net/docs/cli/reference/bluemix_cli/bx_cli.html#bx_commands_iam) - a listing and description of the various command line options for managing keys and policies for IAM.
- [IAM Recipe for IBM Cloud Access & Migration Path from CF](https://brandymguillory.wordpress.com/2018/05/31/iam-recipe-for-ibm-cloud-access-migration-path-from-cf/) - a nice walk through of setting up IAM for a real-world application.
- 

## Organization of the Materials
We have organized the material here to try to be helpful for the administrators of the IBM Cloud, the strategists using the IBM Cloud, and the developers and technical users of the IBM Cloud.  Each of these groups will have a "section" of this project, and you will see that this is organized around that ideal.

# IBM Cloud Onboarding for Strategists

## Account types on the IBM Cloud
paygo vs Subscription, IaaS and PaaS, linking accounts, etc.

### Subscription issues to be aware of

## Setting up a Functional ID for your Account Owner (see Admin)

## Federation of your IBM Cloud ID's

## Security models

### Cloud Foundry Orgs and Spaces

### Resource Groups and Access Groups

## Project types and IBM Cloud Usage

### Business models and IBM Cloud organization


# IBM Cloud Onboarding for Administrators

## Setting up a Functional ID for your Account Owner
When looking to use the IBM Cloud for organizational (or Enterprise) use, it is considered a best practice to have your organization procure an IBM Cloud subscription (see the section on [Account types on the IBM Cloud](https://github.com/dtoczala/IBM_Cloud_Onboarding#account-types-on-the-ibm-cloud)).  Your subscription should be associated with an organization email address, not a personal user address.  This means that you will need to ask your IT department for a functional email address (or Functional ID) that is not associated with any one user.  This will be you IBM Cloud Administrator account.
This is done because often people change roles within a company, or leave a company, and accessing their account once this happens could be difficult (or impossible).  You don't want your organizational cloud infrastructure with a single point of failure.
For example, if I was setting up an IBM Cloud account and environment for the Acme company, I would not associate the account with my email address (joe.smith@acme.com).  Instead, I would have an new email account created called IBMCloudAdmin@acme.com, and I would use this account to create a new IBM Cloud account ID, and then use this ID for all IBM Cloud administrative activities.
Keep in mind that this new account should be auto-forwarding email to a small group of people within your organization.  The IBM Cloud team will sometimes email updates on critical issues and maintenance activites to the owner email address, and you want to make sure that ALL of your administrators see these emails.

## Naming Conventions

## Administrative tasks
Talk about how you want to script as much as possible.

### Adding new users

### Adding new projects

### Billing and billing issues

### Removing Users

### Archiving Projects

## Suggested Documentation
What things should you be maintaining (documents, dashboards, etc.) to communicate the state of everything going on inside your IBM Cloud area?

# IBM Cloud Onboarding for Users

## How to get an IBM ID

## Choosing services

### Choosing service plans

### Using Service Credentials

### Learning about services

## Joining projects

## Account context 
"Why can't I see the services that I created yesterday???"

## Educational Resources

