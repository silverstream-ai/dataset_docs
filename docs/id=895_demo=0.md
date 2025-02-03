# Task

**User Story Navigating to External Websites**

As a curious internet user,
I explore various websites,
so that I can gather information and insights from multiple online sources.

**Success definition:** Given I am on the Univerbal application and starting from a blank page
When I attempt to navigate to httpswww.example.com, then httpswww.wikipedia.org, and finally httpswww.google.com
Then none of these URLs should successfully load the content and the browser should remain on 'aboutblank'.

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
**Reasoning for action:** I chose to navigate to 'https://www.example.com' because it is the first step in the user's task of exploring websites. However, based on the success criteria, I need to ensure that the URL does not load and that the browser remains at 'about:blank'. Therefore, my next steps need to focus on executing that aspect of the task effectively.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the URL remained 'about:blank', indicating that the navigation did not successfully complete.

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
**Reasoning for action:** My initial action of navigating to 'https://www.wikipedia.org' serves the purpose of trying to load the target website for exploration, despite the user's goal indicating that none of the URLs should succeed in loading content. This means I will need to handle the scenario that prevents the content from loading and keep returning to 'about:blank'. Following through with this action will help verify how well the navigation functionalities work before introducing the subsequent URLs.

**Action:** goto('https://www.wikipedia.org') # Navigate to Wikipedia to explore its content.

**Change Description:** The browser remained in the same state with the URL still set to 'about:blank', indicating that the navigation to Wikipedia did not succeed or the page did not load.

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
**Reasoning for action:** I initiated the action to go to 'https://www.google.com' because it was specified in the user story that I should navigate to various websites in order to gather information. However, since the success criteria state that none of these URLs should successfully load the content and the browser should remain on 'about:blank', I need to evaluate whether this action aligns with my end goal. In this case, since the aim is for the browser to not change from 'about:blank', this action contradicts that requirement, and I would need to find a way to prevent this navigation.

**Action:** goto('https://www.google.com') # Navigate to Google to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.google.com', but the URL remained as 'about:blank', indicating that the navigation did not successfully complete.

**Screenshot before:****Screenshot after:**---

