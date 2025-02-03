# Task

**Accessing External Website**

As a web user,
I navigate to a sample website to explore its content,
so that I can gather information and insights from different online resources.

**Success definition:** Given I am on the home page of my browser
When I attempt to visit 'httpswww.example.com' three times
Then I should see that the browser failed to navigate away from 'aboutblank' for all attempts.

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
**Reasoning for action:** The user wants to visit 'https://www.example.com' to explore its content. By executing the goto action with this URL, I initiate the navigation process, which is a crucial step towards meeting the user's goal of gathering information. However, I anticipate that it might not succeed if the browser state does not allow for navigation away from 'about:blank', which aligns with the provided success criteria.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its content.

**Change Description:** The browser initiated a navigation action to 'https://www.example.com', however, the focus and URL remained unchanged at 'about:blank', indicating that the navigation did not successfully occur.

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
**Reasoning for action:** I initiated the navigation to 'https://www.example.com', which is the URL I need to visit to explore content as specified in the user story. This action is intended to see if the browser will successfully navigate away from 'about:blank' to the specified website. However, the task requires that I check if the navigation fails, so I need to monitor the response of the browser to see if it remains on 'about:blank'.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the URL did not change from 'about:blank', indicating that the navigation was unsuccessful or incomplete.

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
**Reasoning for action:** I am trying to visit 'https://www.example.com' from the current browser state, which is 'about:blank'. Since the user story requires me to navigate to a sample website three times and check if the browser fails to navigate away from 'about:blank', this action initiates the first attempt to navigate away from the current state. I need to observe if the navigation is successful or if it fails, which will inform me of the browser's behavior in this scenario.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the URL remained unchanged as 'about:blank', indicating that the navigation did not successfully complete.

**Screenshot before:****Screenshot after:**---

