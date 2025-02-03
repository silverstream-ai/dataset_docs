# Task

**User Journey on Finni Health Website**

As a curious user,
I explore various health and wellness websites,
so that I can gather information and assess available resources for personal health management.

**Success definition:** Given I am starting with the Finni Health site
When I attempt to navigate to different sample websites
Then I should see the URL remain as 'aboutblank' indicating that navigation did not complete successfully.

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
**Reasoning for action:** By attempting to navigate to 'https://www.example.com', I am trying to fulfill the user's objective of exploring health and wellness websites to gather information. However, according to the success criteria, the URL should remain 'about:blank' to indicate that the navigation did not complete successfully. This action will help confirm whether the conditions for obtaining useful information are met or if the navigation fails as expected.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its content.

**Change Description:** The browser did not navigate to 'https://www.example.com' as intended; the URL remained 'about:blank', indicating no change in the page content or state.

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
**Reasoning for action:** I initiated the action to navigate to a sample website because this step is essential for exploring resources related to health and wellness. However, I must ensure the conditions of the user story are met, in which navigation should not complete successfully. Thus, I'm testing whether the URL remains as 'about:blank' after this action, confirming that the navigation does not work as expected.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the URL remained 'about:blank', indicating that the navigation did not successfully change the website currently displayed.

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
**Reasoning for action:** I aimed to explore external health and wellness resources starting from the Finni Health site. However, since the task specifies that I should see the URL as 'about:blank', this indicates that navigation should not successfully complete. By navigating to Wikipedia, I test whether this condition remains true or if the URL changes, which would help identify the behavior of the current browser setup regarding link navigation.

**Action:** goto('https://www.wikipedia.org') # Navigate to Wikipedia to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.wikipedia.org', but the URL remained unchanged at 'about:blank', indicating that the navigation did not successfully complete.

**Screenshot before:****Screenshot after:**---

