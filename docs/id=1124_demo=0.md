# Task

**Password Reset Attempt**

As a user who has forgotten their password,
I request a password reset,
so that I can regain access to my account.

**Success definition:** Given I am on the password reset page
When I submit an email address that is not associated with an account
Then I should see a message stating 'User not found' indicating that my password reset request was unsuccessful.

## Trajectory

**Step 1:**

**Url (before/after):** 

https://dashboard.durate.com/login

https://dashboard.durate.com/reset-password

**Content (before/after):** 

```
RootWebArea Docflow - On-call Scheduling Simplified, focused, url='https://dashboard.durate.com/login'
	image Docflow Logo, url='https://docflow-images.s3.us-east-2.amazonaws.com/Docflow+Gradient.png'
	heading Sign in to your Docflow account
	paragraph
		StaticText Not registered yet?
```
<details><summary>Show more</summary>

```
		[46] link Bring Docflow to your program., center=(1283,422), url='https://www.surveymonkey.com/r/ZJ98PJR'
	LabelText
		StaticText Email address
	[53] textbox Email address, center=(1247,524), autocomplete=email, contenteditable=True, required, type=email
	LabelText
		StaticText Password
	[57] textbox Password, center=(1247,616), autocomplete=current-password, contenteditable=True, required, type=password
	[58] link Forgot password? Click here., center=(1158,650), url='https://dashboard.durate.com/reset-password'
	[61] checkbox Remember me, center=(1066,698), checked='false', contenteditable=True, type=checkbox
	LabelText
		StaticText Remember me
	[64] button Sign in, center=(1247,752), type=submit
	heading Physician scheduling, simplified.
```
</details>



```
RootWebArea Docflow - On-call Scheduling Simplified, focused, url='https://dashboard.durate.com/reset-password'
	image Docflow Logo, url='https://docflow-images.s3.us-east-2.amazonaws.com/Docflow+Gradient.png'
	heading Reset your password
	paragraph
		StaticText Made a mistake?
```
<details><summary>Show more</summary>

```
		[46] link Go back to login, center=(1216,516), url='https://dashboard.durate.com/login'
	LabelText
		StaticText Email address
	[53] textbox Email address, center=(1244,610), autocomplete=email, contenteditable=True, required, type=email
	[55] button Reset password, center=(1244,658), type=submit
	heading Physician scheduling, simplified.
```
</details>

**Reasoning for action:** I clicked on the 'Forgot password? Click here.' link because it is essential to reach the password reset page in order to initiate the password reset process. This step directly supports the user story by allowing the user to request a password reset, which is the first requirement for regaining access to their account. By reaching the password reset page, I can then enter an email address to proceed with the test for the success criteria.

**Action:** click('58') # Click on the 'Forgot password? Click here.' link.

**Change Description:** The browser navigated from the login page to the password reset page after clicking the 'Forgot password? Click here.' link, changing the URL to 'https://dashboard.durate.com/reset-password' and updating the heading to 'Reset your password' while adding a button to reset the password and a link to go back to the login page.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

https://dashboard.durate.com/reset-password

https://dashboard.durate.com/reset-password

**Content (before/after):** 

```
RootWebArea Docflow - On-call Scheduling Simplified, focused, url='https://dashboard.durate.com/reset-password'
	image Docflow Logo, url='https://docflow-images.s3.us-east-2.amazonaws.com/Docflow+Gradient.png'
	heading Reset your password
	paragraph
		StaticText Made a mistake?
```
<details><summary>Show more</summary>

```
		[46] link Go back to login, center=(1216,516), url='https://dashboard.durate.com/login'
	LabelText
		StaticText Email address
	[53] textbox Email address, center=(1244,610), autocomplete=email, contenteditable=True, required, type=email
	[55] button Reset password, center=(1244,658), type=submit
	heading Physician scheduling, simplified.
```
</details>



```
RootWebArea Docflow - On-call Scheduling Simplified, focused, url='https://dashboard.durate.com/reset-password'
	image Docflow Logo, url='https://docflow-images.s3.us-east-2.amazonaws.com/Docflow+Gradient.png'
	heading Reset your password
	paragraph
		StaticText Made a mistake?
```
<details><summary>Show more</summary>

```
		[46] link Go back to login, center=(1216,516), url='https://dashboard.durate.com/login'
	LabelText
		StaticText Email address
	[53] textbox Email address value='user@example.com', center=(1244,610), autocomplete=email, contenteditable=True, focused, required, type=email
	[55] button Reset password, center=(1244,658), type=submit
	heading Physician scheduling, simplified.
```
</details>

**Reasoning for action:** By filling out the email address field with 'user@example.com', I am preparing to submit a password reset request. This step is crucial because the user story requires the submission of an email address to test the reset functionality. Since the acceptance criteria states that this email is not associated with any account, it will help validate that the system correctly processes this scenario and will eventually display the message 'User not found' as specified.

**Action:** fill('53', 'user@example.com') # Fill in the email address field with a sample email.

**Change Description:** The email address field was updated with the value 'user@example.com', making it focused, while all other elements on the page remained unchanged.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

https://dashboard.durate.com/reset-password

https://dashboard.durate.com/reset-password

**Content (before/after):** 

```
RootWebArea Docflow - On-call Scheduling Simplified, focused, url='https://dashboard.durate.com/reset-password'
	image Docflow Logo, url='https://docflow-images.s3.us-east-2.amazonaws.com/Docflow+Gradient.png'
	heading Reset your password
	paragraph
		StaticText Made a mistake?
```
<details><summary>Show more</summary>

```
		[46] link Go back to login, center=(1216,516), url='https://dashboard.durate.com/login'
	LabelText
		StaticText Email address
	[53] textbox Email address value='user@example.com', center=(1244,610), autocomplete=email, contenteditable=True, focused, required, type=email
	[55] button Reset password, center=(1244,658), type=submit
	heading Physician scheduling, simplified.
```
</details>



```
RootWebArea Docflow - On-call Scheduling Simplified, focused, url='https://dashboard.durate.com/reset-password'
	image Docflow Logo, url='https://docflow-images.s3.us-east-2.amazonaws.com/Docflow+Gradient.png'
	heading Reset your password
	paragraph
		StaticText Made a mistake?
```
<details><summary>Show more</summary>

```
		[46] link Go back to login, center=(1216,500), url='https://dashboard.durate.com/login'
	LabelText
		StaticText Email address
	[53] textbox Email address value='user@example.com', center=(1244,594), autocomplete=email, contenteditable=True, required, type=email
	[55] button Reset password, center=(1244,642), type=submit
	StaticText User not found
	heading Physician scheduling, simplified.
```
</details>

**Reasoning for action:** By clicking the 'Reset password' button, I triggered the submission of the form containing the email address. This is a critical step in fulfilling the user's goal of requesting a password reset. The next expected outcome will be processing the email input and checking if it is associated with an existing account. If the email does not match any user account, the system should respond with the message 'User not found', thus allowing me to verify the acceptance criteria of the task.

**Action:** click('55') # Click on the 'Reset password' button to submit the password reset request.

**Change Description:** After clicking the 'Reset password' button, the browser displayed an additional message stating 'User not found,' indicating that the password reset request was processed, but the provided email address did not match any user in the system. Additionally, the position of the 'Go back to login' link and the 'Email address' textbox slightly shifted.

**Screenshot before:****Screenshot after:**---

