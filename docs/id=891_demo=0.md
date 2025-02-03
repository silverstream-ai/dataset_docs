# Task

**User Experience Tracking on Navigation Attempts**

As a website explorer,
I navigate to different websites to gather information,
so that I can access various content and learn more about different topics.

**Success definition:** Given I am on a fresh browser session
When I attempt to navigate to 'httpswww.example.com' and 'httpswww.wikipedia.org'
Then the system should confirm that neither navigation was successful and I remain on 'aboutblank'.

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
**Reasoning for action:** My reasoning for this action is based on the user story, which requires navigating to different websites to gather information. By executing the 'goto' command with the URL 'https://www.example.com', I am trying to fulfill the user's goal of exploring content on a sample website. However, based on the success criteria, I expect that this navigation will not be successful and I will remain on 'about:blank', which aligns with the acceptance test requirements.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the URL in the accessibility tree representation remains 'about:blank', indicating that the navigation did not successfully change the page.

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
**Reasoning for action:** In this action, I initiated a navigation command to 'https://www.example.com', which is meant to take me to a sample website for exploration. The user story mentions gathering information from various websites, and this step is crucial to test if the navigation will succeed or not, as outlined in the acceptance criteria.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its content.

**Change Description:** The browser's URL was intended to change to 'https://www.example.com', but the focus remained on 'about:blank', indicating that the navigation did not successfully complete.

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
**Reasoning for action:** I chose to navigate to 'https://www.wikipedia.org' because this website is a key source of informative content and will help in fulfilling the user story of exploring various topics. However, this action will not change the current state of the browser to a successful navigation, as the acceptance criteria specifies that navigation attempts should result in failure, leaving the browser on 'about:blank'.

**Action:** goto('https://www.wikipedia.org') # Navigate to Wikipedia to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.wikipedia.org', but the URL did not successfully change from 'about:blank', indicating that the navigation did not complete.

**Screenshot before:****Screenshot after:**---

