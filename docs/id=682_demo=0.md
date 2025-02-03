# Task

**User Story for Browsing Experience**

As a user interested in exploring various online content,
I navigate to different websites to view their information,
so that I can broaden my knowledge and find useful content for my research.

**Success definition:** Given I am on the homepage of the browser
When I attempt to navigate to multiple websites including Wikipedia and Google
Then I should see an error indicating that the navigation failed and the URL should remain as 'aboutblank'.

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
**Reasoning for action:** Although the user's goal is to explore various online content, the success criteria states that an error should occur when navigating to multiple websites. Therefore, by choosing to navigate to 'https://www.example.com', I am fulfilling the task and actively trying to see if the navigation will succeed or trigger an error as outlined in the acceptance test. This action directly tests the conditions provided by the success criteria.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the URL remained 'about:blank', indicating that the navigation did not successfully change the current webpage.

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
**Reasoning for action:** I initiated the action to navigate to Wikipedia to allow the user to access a wealth of information for their research. Although the expected outcome is an error indicating navigation failure, this step represents the user's intent to explore content. Monitoring how the page responds will provide feedback on the browsing capabilities of the current state.

**Action:** goto('https://www.wikipedia.org') # Navigate to Wikipedia to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.wikipedia.org', but the URL remains 'about:blank', indicating that the navigation did not successfully occur.

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
**Reasoning for action:** My reasoning for this action was based on the user story, which states the need to explore various online content. Navigating to Google will allow access to a wide range of information. However, considering the success criteria, if the navigation fails, it will confirm that the URL remains as 'about:blank', thereby meeting the acceptance tests. Regardless of the current state, it is important to attempt to access Google to see if it can change from 'about:blank'.

**Action:** goto('https://www.google.com') # Navigate to Google to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.google.com', but the URL remained 'about:blank', indicating that the navigation did not successfully complete and the webpage content did not change.

**Screenshot before:****Screenshot after:**---

