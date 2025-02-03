# Task

**User Story for URL Navigation Attempt**

As a A curious internet user,
I explore various websites and gather information,
so that I can broaden my knowledge and find resources that interest me.

**Success definition:** Given I am on a web browser with the initial state set to 'aboutblank'
When I attempt to navigate to 'httpswww.example.com' and 'httpswww.wikipedia.org'
Then I should see no change in the URL, remaining on 'aboutblank', indicating that navigation attempts were unsuccessful.

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
**Reasoning for action:** My reasoning for taking this action was to fulfill the user's goal of exploring the website 'https://www.example.com'. However, since the user story indicates that the URL should remain 'about:blank' after the navigation attempts, my next steps would focus on seeing if there are restrictions or conditions preventing successful navigation, thus confirming that I need to investigate further to align with the expectation of no changes to the URL.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the URL remains unchanged as 'about:blank', indicating that the navigation did not successfully update the page or may have been aborted.

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
**Reasoning for action:** My reasoning for this action is to assess the browser's navigation capability from its initial state of 'about:blank'. By attempting to access 'https://www.example.com', I am checking if the browser allows the navigation to take place, which is part of the user story involving exploring and gathering information. However, since the acceptance test indicates that the URL should not change, I will need to observe whether this action results in any change or not, in line with the user's goal of staying on 'about:blank'.

**Action:** goto('https://www.example.com') # Attempt to navigate to a sample website again.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the state remained unchanged, still showing 'about:blank' as the focused URL, indicating that the navigation was unsuccessful.

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
**Reasoning for action:** My reasoning for this action is to fulfill the user's task of exploring websites to gather information. By attempting to navigate to Wikipedia, a well-known resource for diverse information, it aligns with the user story. However, the acceptance criteria specify that the URL should not change and remain 'about:blank', indicating that this action would not meet the specified success criteria.

**Action:** goto('https://www.wikipedia.org') # Navigate to Wikipedia to load content.

**Change Description:** The browser did not load any new content or change the displayed URL after the action, remaining on the initial state of 'about:blank' with no navigation to Wikipedia.

**Screenshot before:****Screenshot after:**---

