# Task

**Website Navigation Failure**

As a web explorer,
I navigate to various websites,
so that I can explore content from different sources.

**Success definition:** Given I am on a blank browser page
When I attempt to navigate to 'httpswww.example.com', 'httpswww.wikipedia.org', and 'httpswww.google.com' in sequence
Then I should not successfully load any of the websites and remain on 'aboutblank'.

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
**Reasoning for action:** My reasoning for this action is based on the task requirements where I need to attempt to navigate to various websites in sequence. By initiating the navigation to 'https://www.example.com', I am following the user's intention to explore content from that site. However, the success criteria specifies that the navigation should not be successful, and I should remain on 'about:blank'. Thus, performing this action sets up a sequence where I will eventually check if the navigation is blocked as expected.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the URL remained unchanged as 'about:blank', indicating that the navigation did not successfully update the page content.

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
**Reasoning for action:** I need to navigate to the specified websites in the user's story; however, the goal is to remain on 'about:blank'. By attempting to go to 'https://www.wikipedia.org', I am fulfilling the requirement of the test to attempt to load a website. This action does not indicate a successful load, as the acceptance criteria specify that navigating should not lead to a successful load of any site, allowing me to remain focused on 'about:blank'.

**Action:** goto('https://www.wikipedia.org') # Navigate to Wikipedia to explore its content.

**Change Description:** The browser was instructed to navigate to 'https://www.wikipedia.org', but the URL displayed remains 'about:blank', indicating that the page did not load successfully or that the navigation was incomplete.

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
**Reasoning for action:** I initiated this action to follow the user's instruction of exploring various websites. However, since the acceptance criteria specify that the websites should not load and the browser should remain on 'about:blank', this action does not fulfill that requirement. I need to ensure that I do not successfully load any of the websites.

**Action:** goto('https://www.google.com') # Navigate to Google to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.google.com', but the URL remains unchanged as 'about:blank', indicating that the navigation did not successfully complete.

**Screenshot before:****Screenshot after:**---

