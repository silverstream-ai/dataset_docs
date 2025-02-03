# Task

**Browsing Limitation Experience**

As a curious internet user,
I explore different websites for information,
so that I can gather knowledge from various sources.

**Success definition:** Given The user is on the Infinity App home page
When The user attempts to navigate to multiple websites example.com, wikipedia.org, google.com
Then The user should experience that none of the websites load correctly, and the URL remains unchanged as 'aboutblank'.

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
**Reasoning for action:** I chose to navigate to 'https://www.example.com' because it is the first website in the list of destinations the user wants to explore. Since the goal is to ensure that none of the websites load correctly, doing this will allow me to observe the expected behavior where the URL remains unchanged as 'about:blank'. This directly aligns with the user's intention of exploring different sites for knowledge.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the URL in the accessibility tree representation remained 'about:blank', indicating that the page did not load successfully.

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
**Reasoning for action:** I selected the action to navigate to Wikipedia because the task requires exploring different websites for information. However, according to the acceptance criteria, I need to ensure that the website does not load correctly, which means there should be a deliberate failure in navigation. Therefore, while the action is meant to access Wikipedia, I must eventually ensure that the user experience reflects the failure to load the page and leaves the URL unchanged as 'about:blank'.

**Action:** goto('https://www.wikipedia.org') # Navigate to Wikipedia to explore its content.

**Change Description:** The browser navigated to 'https://www.wikipedia.org', but the final state remained unchanged as the URL continued to display 'about:blank', indicating that the navigation did not succeed or was interrupted before the page could fully load.

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
**Reasoning for action:** Since the user is attempting to navigate to various websites to explore them, I initiated the action to go to Google. However, based on the acceptance criteria, it is expected that the URL remains 'about:blank' and that the website does not load correctly. This action serves to simulate the user's intention to explore, while also preparing for the next steps to ensure the website does not load properly.

**Action:** goto('https://www.google.com') # Navigate to Google to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.google.com', but the URL has not changed and remains 'about:blank', indicating that the navigation was unsuccessful and no content from Google was loaded.

**Screenshot before:****Screenshot after:**---

