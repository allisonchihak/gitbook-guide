# Employee Profile

Employee profiles are used to give employees access to Mews. Using these profiles, you can track activity, assign responsibility, and allow or restrict the rights of each employee that works at your property.

Any time a new employee profile is created, the system will automatically assign it below the user who created it in the staff hierarchy, so your property’s admin—the most senior member of your staff—should be responsible for creating new profiles. There is no limit to the amount of profiles that can be created in Commander, so employees should never share a profile. 

Go to your employee settings using the following path:

* **`Main menu > Settings > Employees`**

On this page you will find a list of all currently-existing employees in the system. Profiles are displayed in a hierarchical structure to give an accurate visual representations of the chain of command at your property. Employee profile images are also displayed next to each name for easy identification.

Each employee is listed with the following overview details:

* **Name** - The name of employee as entered in their profile.
* **E-mail** - The employee's e-mail address, which was used to create the account.
* **Department** - The department that the employee is assigned to.
* **Admin** - States whether the employee has been given admin rights. If yes, they are awarded all privileges. If no, you can hover the mouse over `No` to see a list of the employee's privileges. Please note that this list will only appear if a non-admin employee has been assigned some work privileges. For more information about admin privileges, see below. 
* **Cashiers** - A list of all cashiers the employee is permitted to use.
* **Authenticator** - Indicates whether the user has enabled two-factor authentication. 
* **Enabled** - If the employee's profile is enabled for only a specific amount of time, the dates in which it is enabled will display here. If no dates are specified, the field will say `For eternity`. 
* **Options** - Any additional privileges granted to the employee.

One major benefit of ****a cloud-based system like Mews Commander is that it can be accessed at any time and from any location. This allows employees to sign in to the system even when they are not physically at the property, so it is important for each property to have a strict security policy in place. Please ensure that an employee's profile is deleted when that employee leaves his or her position.

## Create

On the main Employees page, click the `+` button and then complete the following details to create a new employee profile:

* **E-mail** - Enter the employee's e-mail address. Please note that only one employee profile can be linked with each valid e-mail address. 
* **Superior employee** - Here, you'll see a drop-down of other employees at your property. Choose the person that this new employee should report to. They will automatically be added to their proper place in the property's hierarchy, which is visible from the main Employees page.  

Once created, the employee's e-mail address cannot be edited. If incorrect, you must fully delete the profile and create a new one with the correct details. When all fields are correctly completed, click the `Create` button**.**

Once the profile is created, a one-time activation an e-mail is sent to the employee, which allows users to sign in, set their password, and edit their profile details. Please note that it is the employee's responsibility to add their first and last name to their profile. 

To see more details or to edit a profile, navigate to the main Employees page and click on an employee's name.

{% hint style="info" %}
### Mews Clues

It is not possible to create employee profiles in Mews without an e-mail address, as the initial login to the system is sent to that e-mail address.

When you create a subordinate profile, you can assign that person the same or less rights than you have for yourself in Mews. Please note that it is not possible to create a profile for anyone who is higher in your property's chain of command.
{% endhint %}

## Privileges

Upon clicking the `Create` button, you will see these additional fields appear in their employee profile.

The following fields must be completed in to assign proper user rights and privileges for each employee:

* **Department** - Select that employee's [department ](https://mews-systems.gitbook.io/guide/commander/settings/users-settings/departments)to assign tasks or notifications to employees of that department only.
* **Enabled from** - Choose the date of this profile's activation. \(e.g. if you have new hires starting later, give them access starting on a certain date\).
* **Enabled to** - Choose the date of this profile's deactivation. \(e.g. if you know an employee is leaving, use this to ensure you don't forget to restrict their system access\).
* **Admin** - Select this option to give a user admin rights. Admin users will automatically be given all user rights available in the system. In addition to those privileges, admin employees will be able to modify the [editable history window \(EHW\)](https://mews-systems.gitbook.io/guide/commander/settings/finance-settings/accounting-configuration). If you select this option, the `Workplace privileges` selection will disappear, as all rights apply and it is no longer necessary. Please note that this privilege should be given sparingly and to your most trusted employees as it allows them to edit tax documents and important system data. 
* **Receive customer messages** - Select this option if user should receive messages from customers using the Mews Navigator.
* **Workplace privileges** - Choose any of the following privileges that this user should have.
  * **Configure enterprise** - Access to change the general settings of the property \(e.g. e-mails, editable history window, etc.\).
  * **Configure services** - Employee can manage services and products**.**
  * **Configure spaces** - Employee can modify spaces and place rooms Out Of Order. Please note that placing rooms OOO has a direct impacts your property's room inventory, so this privilege should be given sparingly.
  * **Issue invoices** - Rights to create invoices with future payment date.
  * **Manage companies** - User can create and manage Company Profiles.
  * **Manage customers** - User can create and manage Customer Profiles.
  * **Manage employees** - Select this option if this employee should have access to create new employees. User will also be able to assign workplace privileges to the employee profiles that they create. This should be reserved only for senior management.
  * **Manage reservations** - User can amend booking details.
  * **Manage travel agency contracts** - User can create and manage travel agency profiles.
  * **Overbook services** - Rights to create additional bookings even if space type is fully booked.
  * **Perform housekeeping** - Rights to change room status. 
* **Cashiers** - Assign one or multiple cashiers to the user.

If an employee forgets their password, they can log in to `https://www.mews.li` and use the password reset feature to have a link with instructions sent to their e-mail address.

## Chain Access

If you operate more than one property with Mews, one employee can be given access to all or some of your locations.

To give one user access to multiple properties, you must create a new employee in each hotel using the same name and e-mail address. The system will recognize the duplicate information and will automatically merge the accounts.

When this user logs in, they can switch between the newly added properties using the user profile icon in their dashboard header.

{% hint style="info" %}
### Mews Clues

Please note that when adding additional properties for a user to access, the system will not send a password setup e-mail to the user each time, as the password was already set upon the initial creation.

If an employee forgets their password, they can use the password reset feature to have a link with instructions sent to their registered e-mail address.
{% endhint %}

## Delete

To delete a user, navigate to the main Employees page, select the user's name, and then click the `Trash can` icon.

When an employee leaves his or her position at the property, it is important to delete their user profile as soon as possible. As Mews is a cloud-based solution, employees are able to sign in to the system even when they are not physically at the property. Having a strict departure procedure in place will ensure that all employee profiles are properly deleted in Commander when employees leave their positions at the company. 

Please note that only superior employees have rights to delete users in the system.

{% hint style="info" %}
### Mews Clues

If you are deleting an employee that is the manager of a team, you must first migrate all of their subordinate profiles to a different superior employee before it will be possible to delete the user.
{% endhint %}

## Two-Factor Authentication

Every user has the option to enable or disable two-factor authentication \(2FA\). Before you can enable this feature in Commander, download an authentication app to your mobile device. 

To enable two-factor authentication, click the user profile icon in the Dashboard header, select **Profile**, and then go to the `Security` tab. This feature will be disabled by default; to enable, click `Edit`, and follow the onscreen instructions. Please note that the pin number should be entered without any spaces. When you have completed all fields, click `Authenticate`. 

The system will automatically generate ten recovery codes for your account, which can be used to sign in to the system if you are unable to retrieve the authenticator pin from your phone. Please note that these codes should be stored in a secure location as they will only be displayed on this page once

Once two-factor authentication is enabled, you will need to enter a unique pin generated by your authenticator app each time you sign in to Mews. Please note that this pin should not include any spaces.

