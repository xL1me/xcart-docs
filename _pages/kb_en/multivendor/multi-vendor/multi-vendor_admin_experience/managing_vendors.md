---
lang: en
layout: article_with_sidebar
updated_at: '2018-03-15 10:41 +0400'
identifier: ref_6OTbIwfd
title: Managing vendors
order: 200
published: true
---
## Approving/rejecting vendor applications

A user who wants to become a new vendor on the marketplace can submit an application via the Become a seller page in the Customer area. When this happens, the store administrator is notified of the new vendor registration via a bell notification and an email notification sent to their inbox. The administrator needs to review this application and either approve or reject it.

To do so, the administrator needs to find the profile of the user who has applied to become a vendor in the Users section of the store's Admin area (They will have a regular user profile record in the store's user list and will be marked as an "Unapproved vendor"):
![xc5_mv_unapproved_vendor_list1.png]({{site.baseurl}}/attachments/ref_SkW62BgH/xc5_mv_unapproved_vendor_list1.png)

To decide whether the new vendor application should be approved, the administrator may want to review the details of the vendor profile. Note that a vendor profile is populated with the information that the user has provided at the time of submitting their vendor application; this includes the prospective vendor's email, name, company name, company description and company address and, if required, ship-from address. This information can be found on the tabs of the prospective vendor's user profile.

After reviewing the user profile of the prospective vendor, the administrator needs to approve or reject the application using the buttons **Approve vendor** / **Decline vendor**. 
![xc5_mv_approve_decline.png]({{site.baseurl}}/attachments/ref_SkW62BgH/xc5_mv_approve_decline.png)

If needed, before approving a vendor profile, the administrator may want to re-adjust the new vendor's access information (for example, to change the user's access permissions by changing the role that was assigned to them by default, to give the user a non-default membership level, or to re-adjust the account settings so the user will be requested to change their password on next login). This, of course, can also be done *after* the new vendor approval.

## Adding new vendors via the Admin area

The store administrator can create user profiles for vendor users via the Users section of the store's Admin area.

To create a new vendor profile, the administrator needs to do one of the following: 

*   creates a new user profile with the access level "Vendor":
    ![]({{site.baseurl}}/attachments/8749143/8719604.png)
*   creates a new user profile with the access level "Admin" and the role "Vendor" (or other vendor-related role, if such a role has been configured by the administrator):
    ![]({{site.baseurl}}/attachments/8749143/8716890.png)

With this method, a new vendor user is created right away:
    ![xc5_multi-vendor_profile_created.png]({{site.baseurl}}/attachments/ref_SkW62BgH/xc5_multi-vendor_profile_created.png)

The new vendor can log in and start selling immediately after the creation of their profile.

## Editing vendor profiles

If a vendor requests a change of their profile information (for example, if the vendor is selling their business, and the change of the business owner needs to be reflected in the vendor profile details), the store administrator can edit the respective vendor profile via the Users section of the store's Admin area.
![xc5_multi-vendor_admin_access2vendorprofile.png]({{site.baseurl}}/attachments/ref_6kbIUy5R/xc5_multi-vendor_admin_access2vendorprofile.png)

For details on the management of vendor profile information, see {% link "Managing vendor profile information" ref_b7PTQMgf %}

## Exporting vendor profile information
If the information from the profiles of some or all of the store's vendors needs to be used outside the X-Cart store (for example, if the store owner wants to have this information in a spreadsheet editor or wishes to use it in some kind of other external application), the store administrator should consider exporting vendor profile information from the X-Cart store to a CSV file:
![xc5_multi-vendor_export.png]({{site.baseurl}}/attachments/ref_6kbIUy5R/xc5_multi-vendor_export.png)

## Removing vendors

If the access of any existing vendor to the marketplace needs to be discontinued, the store administrator can remove their user profile via the Users section of the store's Admin area:
![xc5_multi-vendor_removal.png]({{site.baseurl}}/attachments/ref_6kbIUy5R/xc5_multi-vendor_removal.png)
