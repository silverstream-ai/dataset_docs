# Task

**Navigation Testing User Story**

As a website tester,
I examine the ability to navigate to different external URLs without experiencing issues,
so that I can ensure that navigation functionalities work correctly and users can access the intended content.

**Success definition:** Given the browser is opened and ready for navigation
When the user attempts to navigate to 'httpswww.example.com' and 'httpswww.wikipedia.org'
Then the user should see that both URLs do not load successfully and the browser state remains as 'aboutblank'.

## Trajectory

**Step 1:**

**Url (before/after):** 

about:blank

about:blank

**Content (before/after):** 

```
RootWebArea, focused, url='about:blank'
```


```
RootWebArea, focused, url='about:blank'
```
**Reasoning for action:** Since the user's goal is to test navigation functionalities, I initiated a navigation to 'https://www.example.com'. By doing this, I can verify whether the website loads correctly or if it leads to an error, which is essential for understanding if there could be issues with navigating to external URLs. This first step brings me closer to gathering the necessary data for the acceptance criteria.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the URL in the accessibility tree representation remains 'about:blank', indicating that the navigation did not occur successfully.

**Screenshot before:****Screenshot after:**---

**Step 2:**

**Url (before/after):** 

about:blank

about:blank

**Content (before/after):** 

```
RootWebArea, focused, url='about:blank'
```


```
RootWebArea, focused, url='about:blank'
```
**Reasoning for action:** In order to test the user's ability to navigate to external URLs, I need to initiate a navigation action. By going to 'https://www.example.com', I can observe whether the page loads correctly or if it fails to load, which will inform my understanding of the navigation functionality as required by the user story.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its content.

**Change Description:** Despite the action taken to navigate to 'https://www.example.com', the browser state remains unchanged with the URL still set to 'about:blank', indicating that the navigation did not occur successfully.

**Screenshot before:****Screenshot after:**---

**Step 3:**

**Url (before/after):** 

about:blank

about:blank

**Content (before/after):** 

```
RootWebArea, focused, url='about:blank'
```


```
RootWebArea, focused, url='about:blank'
```
**Reasoning for action:** My reasoning for this action is based on the user story which requires testing the navigation functionality to external URLs. By attempting to navigate to 'https://www.wikipedia.org', I am initiating a test to see if the URL will load successfully or not, thereby allowing me to evaluate the current functionality of the navigation system. This step is crucial because it directly addresses the need to confirm whether the navigation capabilities of the browser are performing as expected.

**Action:** goto('https://www.wikipedia.org') # Navigate to Wikipedia to explore its content.

**Change Description:** The browser navigated to 'https://www.wikipedia.org', but the final state shows the URL remains 'about:blank', indicating that the navigation did not successfully complete or was reverted.

**Screenshot before:****Screenshot after:**---

