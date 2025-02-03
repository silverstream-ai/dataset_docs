# Task

**User Story Exploring External Content Sources**

As a user exploring online resources,
I view content from different websites,
so that I can gather information from various sources for my research.

**Success definition:** Given I am on the URL httpsusedill.com
When I attempt to navigate to multiple external websites
Then I should see that the browsing state remains at 'aboutblank', indicating navigation failures to the specified external sites.

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
**Reasoning for action:** My reasoning for this action is to fulfill the user story by trying to visit an external website. However, based on the user story's success criteria, I anticipate that this navigation will fail because the current browser state is 'about:blank'. This indicates that the system likely restricts browsing to maintain this state, and thus, I need to verify if this action leads to the expected navigation failure.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the URL remained 'about:blank', indicating that the navigation was unsuccessful or not completed.

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
**Reasoning for action:** I initiated the navigation to 'https://www.wikipedia.org' to fulfill the user's goal of accessing different websites for information gathering. However, since the criteria state that external site navigation should result in the browsing state remaining 'about:blank' due to navigation failures, this action will serve to test that functionality.

**Action:** goto('https://www.wikipedia.org') # Navigate to Wikipedia to explore its content.

**Change Description:** The browser remained on the same URL ('about:blank') and did not navigate to Wikipedia, despite the action intended to do so.

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
**Reasoning for action:** I aimed to access content on Google to gather research material. However, I noted that the requirement specifies that the browsing state should remain at 'about:blank', which indicates that navigation to external sites like Google would ultimately fail. Understanding this, I recognize that this action might contradict the expected outcome, which is to ensure that the browsing state stays at 'about:blank' due to navigation failures.

**Action:** goto('https://www.google.com') # Navigate to Google to explore its content.

**Change Description:** The browser initiated a navigation action to 'https://www.google.com', but the final state shows that the URL remains 'about:blank', indicating that the navigation did not complete successfully.

**Screenshot before:****Screenshot after:**---

