# email_partner

_email_claim_ is a module that adds an _Email_ button to Odoo's _Partner_ form. 

The email button will open the compose dialog. Currently, it uses a hard-coded template ID, which must be created manually by you. 

##### Example Values for email template:

- From: ```${object.user_id.email or object.company_id.email}```
- To: ```${object.email}```

##### To Do:

- Create default template
- Allow selecting template from Odoo settings
