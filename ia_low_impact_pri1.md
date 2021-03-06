# NIST 800-53 IA Low Impact Priority 1

This file is generated by a script. To modify, update source file [./ia_low_impact_pri1.yaml](./ia_low_impact_pri1.yaml).

## As the CIO, I want to document and communicate our organization's identification and authentication policy.

*Why:*
Defining and properly-sharing an identification and authentication policy is essential to ensuring that privileged information remains secure.


*How:* 
* Define roles in addition to ISSO or ISSM that the identification and authentication policy is to be disseminated to. (State if there are no additional roles)
* Ensure that the identification and authentication policy and procedures are disseminated
* Define frequency at which to review and update the identification and authentication policy and procedures (Annually).
* Maintain audit trail of reviews and updates.


*Acceptance Criteria / Evidence:*
* List of personnel to whom identification and authentication policy and procedures are to be disseminated
* Authentication policy
* Authentication policy version update page
* Authentication policy audit trail of reviews and updates


*Links:*
* https://web.nvd.nist.gov/view/800-53/Rev4/control?controlName=IA-1
## As the CISO, I need to ensure that accounts for all employees, contractors, guest researchers, etc are properly secured.

*Why:*
To prevent unwanted access to secure data, we need to ensure that all network and local access to privileged accounts are secure.


*How:* 
* Use multifactor authentication for all employee-level accounts.
* If this is a federal agency, use inter-operable credentials that comply with HSPD-12 and FIPS-201.



*Acceptance Criteria / Evidence:*
* Documentation of multifactor authentication system in organization's identification and authentication policy.
* Proof of HSPD-12 compliance.


*Links:*
* [HSPD-12 program](https://cio.gov/protect/identity-management-hspd-12/)
* [Federal Identity Resources](https://www.idmanagement.gov/IDM/s/)
* [FIPS-201 WikiPedia article](https://en.wikipedia.org/wiki/FIPS_201)
* https://web.nvd.nist.gov/view/800-53/Rev4/control?controlName=IA-2

*Labels:*
* IA
* IA-2
* security
* accounts
## As the CISO, I want to ensure that all employee-level account creations and configuration is done according to an approved workflow.

*Why:*
To prevent unwanted access to secure data, we need to ensure that all network and local access to privileged accounts are secure.

*How:* 
* Define an employee registration process that requires:
  * Unique personal identifiers that are applied to specific devices or roles
  * Supervisor authorization
  * Multiple forms of certification of individual identification be presented to the registration authority
  * Periodic (monthly) review and disabling of inactive accounts
* Define an employee registration authority that:
  * Follows the registration process
  * Co-ordinates with external organizations for cross-organization management of identifiers
* Define and enforce a password policy (IA-5):
  * Minimum password complexity (length, minimum number of upper/lowercase/number/special characters)
  * Unique passwords with at least x characters changed when new passwords are created
  * Encrypt all passwords for transmission and storage using a cryptographic module that meets the requirements of applicable federal laws, Executive Orders, directives, policies, regulations, standards, and guidance for such authentication (IA-7)
  * Minimum and maximum password lifetime
  * Use temporary passwords that can be immediately changed to a permanent password for password resets.

*Acceptance Criteria / Evidence:*
* Documented registration process are part of the organization's identification and authentication policy.
* A role within the organization's IT operations that will act as the organization's registration authority.
* Password policy included in the organization's identification and authentication policy

*Links:*
* https://web.nvd.nist.gov/view/800-53/Rev4/control?controlName=IA-4
* https://web.nvd.nist.gov/view/800-53/Rev4/control?controlName=IA-6
* https://web.nvd.nist.gov/view/800-53/Rev4/control?controlName=IA-7

*Labels:*
* IA
* IA-4
* IA-5
* IA-7
* security
* accounts
## As the CISO of a federal agency, I need to ensure that all non-employee access follows federal guidelines.

*Why:*
All outside access, 3rd party integrations, or API connects to our organization's IT systems need to be secure to ensure the safety of privileged information.

*How:* 
* Accept and electronically verify Personal Identity Verification (PIV) credentials from other federal agencies.
* Only use FICAM-approved third-party credentials.


*Acceptance Criteria / Evidence:*
* Non-employee access guidelines are part of the organization's identification and authentication policy
* Docuentation of all third-party credentials and proof of FICAM approval.

*Links:*
* [FICAM Guidance](http://info.idmanagement.gov/2012/04/federation-ficam-and-guidance.html)
* [List of FICAM TFS Approved Identity Services](https://www.idmanagement.gov/IDM/s/article_detail?link=approved-identity-services)
* https://web.nvd.nist.gov/view/800-53/Rev4/control?controlName=IA-8

*Labels:*
* IA
* IA-8
* federal
* security
* accounts
