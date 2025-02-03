# Task

**User Story for Website Navigation**

As a curious internet user,
I explore various online content,
so that I can gather information and learn about different topics.

**Success definition:** Given I am on the starting URL httpsreadily.co
When I attempt to navigate to 'httpswww.example.com', 'httpswww.wikipedia.org', and 'httpswww.google.com'
Then the navigation attempts should indicate that the content was not loaded successfully, resulting in an unchanged URL of 'aboutblank' for each attempt.

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
**Reasoning for action:** By navigating to 'https://www.example.com', I'm testing the system's capability to load a webpage. The user story requires me to explore online content, and this action initiates that process. If the navigation is unsuccessful, it will confirm that the URL remains 'about:blank', which aligns with the criteria that content should not load and the URL should effectively stay unchanged.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its content.

**Change Description:** Although the action to navigate to 'https://www.example.com' was taken, the browser's URL remains 'about:blank', indicating that the navigation did not succeed or was not reflected in the final state.

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
**Reasoning for action:** I chose to navigate to 'https://www.wikipedia.org' because it is a popular source of information on a wide range of topics, aligning with the user's goal of gathering information and learning. However, since the task specifies that the navigation attempts should result in an unchanged URL of 'about:blank', I anticipate that this attempt will not succeed and will reflect the required outcome.

**Action:** goto('https://www.wikipedia.org') # Navigate to Wikipedia to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.wikipedia.org', but the URL remained unchanged as 'about:blank', indicating that the navigation did not successfully complete.

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
**Reasoning for action:** My reasoning for this action is that the user story indicates a desire to explore various online content, and navigating to Google, a well-known search engine, is a first step in fulfilling that exploration. However, the success criteria specify that the URL should remain 'about:blank' due to the navigation attempts indicating unsuccessful loading of content. Therefore, this action will illustrate that the website failed to load properly by changing the URL to 'about:blank', aligning with the user's requirement.

**Action:** goto('https://www.google.com') # Navigate to Google to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.google.com', but the URL remained 'about:blank', indicating that the navigation did not succeed and the page content did not change.

**Screenshot before:****Screenshot after:**---

