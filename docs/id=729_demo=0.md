# Task

**User Navigation Experience**

As a website tester,
I assess the reliability of external websites through navigation attempts,
so that I can ensure users are able to access content without issues.

**Success definition:** Given I am a website tester planning to navigate to an external site
When I attempt to navigate to 'httpswww.example.com' three times
Then I should observe that the navigation fails each time, with the URL remaining 'aboutblank'.

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
**Reasoning for action:** Since the user story specifies that the user wants to assess the reliability of external websites by trying to navigate to them, taking this action allows me to initiate the navigation process. The goal here is to confirm whether or not the external site is accessible. By attempting to navigate to 'https://www.example.com', I will determine if the site loads correctly or if the URL remains 'about:blank', fulfilling the requirement of my testing.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its elements.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the URL remained unchanged at 'about:blank', indicating that the navigation did not successfully load the new site.

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
**Reasoning for action:** My reasoning for taking this action is that navigating to 'https://www.example.com' is necessary to assess the website's reliability for the given task. Since the user story outlines that I need to attempt navigation three times, the first step should be to initiate the navigation to see if it succeeds or fails, and to subsequently determine whether the URL remains 'about:blank' as specified in the acceptance test.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its elements.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the URL remained 'about:blank', indicating that the navigation did not succeed or the page did not load.

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
**Reasoning for action:** I chose to navigate to 'https://www.example.com' to initiate the first attempt to access the external website as part of the testing process. By doing this, I can determine whether the site is accessible or if it fails to load, which aligns with the user story of assessing reliability through navigation attempts.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its elements.

**Change Description:** The browser did not successfully navigate to 'https://www.example.com' as indicated by the unchanged URL, remaining at 'about:blank', suggesting that the intended navigation failed or was not completed.

**Screenshot before:****Screenshot after:**---

