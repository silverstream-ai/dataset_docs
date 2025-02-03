# Task

**Website Navigation Exploration**

As a web explorer,
I navigate to various websites to explore their elements,
so that I can understand the layout and content of different types of web pages.

**Success definition:** Given I am on a clean browser session at aboutblank
When I attempt to navigate to 'httpswww.example.com' and then 'httpswww.wikipedia.org'
Then the browser should show an error indicating that the navigation was unsuccessful, keeping the URL as aboutblank.

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
**Reasoning for action:** My reasoning for this action is to initiate the navigation process to the sample website (https://www.example.com), which is part of the user story requiring exploration of different web page elements. However, this action is intended to result in an error due to the specification in the acceptance test that the navigation should be unsuccessful and retain the URL as 'about:blank'. Therefore, I am setting up the conditions to observe and process this error message, aligning with the user's goal of understanding how navigation elements behave.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its elements.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the URL remained unchanged as 'about:blank', indicating that the navigation did not complete successfully.

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
**Reasoning for action:** The user's goal is to navigate to the examples provided and see if the browser behavior aligns with the expectation of showing an error. Attempting to navigate to 'https://www.example.com' satisfies the requirement to assess how the browser responds to navigation attempts. I anticipate that this might lead to an error given the inherent task based on the acceptance criteria.

**Action:** goto('https://www.example.com') # Attempt to navigate to a sample website again.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the URL remained unchanged as 'about:blank', indicating that the navigation was unsuccessful.

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
**Reasoning for action:** I performed the action of navigating to 'https://www.wikipedia.org' in order to follow the user story which requires exploring web pages and understanding their layout and content. However, I'm aware that this URL is incorrect as it is missing the protocol (https://) and the browser will not be able to resolve it correctly. Thus, the expected result is that the navigation will fail, and the browser will remain at the about:blank state, meeting the acceptance test criteria.

**Action:** goto('https://www.wikipedia.org') # Navigate to Wikipedia to explore its elements.

**Change Description:** The browser remained focused on the 'about:blank' URL, indicating that the navigation to 'https://www.wikipedia.org' was unsuccessful or did not complete, leaving the state unchanged.

**Screenshot before:****Screenshot after:**---

