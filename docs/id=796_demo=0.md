# Task

**User Navigation Exploration**

As a web explorer,
I navigate to various websites,
so that I can discover different content and sources of information.

**Success definition:** Given I am on the Dioxus Labs website and want to explore online content
When I attempt to navigate to different websites like Wikipedia and Google
Then the navigation actions should result in an error state, preventing me from viewing the intended websites, and the URL should remain as 'aboutblank'.

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
**Reasoning for action:** My reasoning for this action is that the user story indicates a desire to navigate various websites for exploration and discovery of content. However, according to the success criteria, any navigation should result in an error state to meet the acceptance test. By navigating to 'https://www.example.com', I am attempting to demonstrate the action of exploring content, but it will also lead to an error due to the current restrictions on navigation. This aligns with the user's goal of exploring while also fulfilling the constraint set by the acceptance criteria that states navigation should not succeed.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the URL in the accessibility tree remained unchanged as 'about:blank', indicating that the navigation either failed or did not complete.

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
**Reasoning for action:** My reasoning for this action is to fulfill the user's desire to explore different websites, specifically Wikipedia, which is a significant source of online information. However, given the user story context, this navigation should ideally result in an error state where I cannot access the site, keeping the URL at 'about:blank'. Thus, I aim to verify if the system's behavior aligns with the acceptance criteria, meaning I will check if the navigation can be completed or if it will be blocked.

**Action:** goto('https://www.wikipedia.org') # Navigate to Wikipedia to explore its content.

**Change Description:** The browser initiated a navigation action to 'https://www.wikipedia.org', but the final state remains unchanged with the URL still set to 'about:blank', indicating that the navigation did not complete successfully.

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
**Reasoning for action:** Given the user story indicates that the goal is to explore different content on various websites, I attempted the navigation to Google's website. However, it is important to note the success criteria specify that this action should result in an error state, preventing access to the intended website. Therefore, this action directly targets the ability to confirm the presence of an error state based on the criteria while attempting to maintain the current URL as 'about:blank'.

**Action:** goto('https://www.google.com') # Navigate to Google to explore its content.

**Change Description:** The browser navigated to 'https://www.google.com', but the URL displayed in the state remained 'about:blank', indicating that the navigation to Google did not complete successfully or was reverted.

**Screenshot before:****Screenshot after:**---

