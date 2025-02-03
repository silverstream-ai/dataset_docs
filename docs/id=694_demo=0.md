# Task

**User Story for Navigation to External Websites**

As a web user,
I explore content on external websites,
so that I can access information and resources relevant to my interests.

**Success definition:** Given I am a web user attempting to navigate to different websites
When I attempt to navigate to 'httpswww.example.com' and 'httpswww.wikipedia.org'
Then I should see an indication that the websites did not load successfully and remain on the current page.

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
**Reasoning for action:** I initiated navigation to 'https://www.example.com' in order to access content relevant to the user's interests. However, according to the success criteria in the user story, it is expected that if the website does not load successfully, there should be an indication that the navigation failed, and the user remains on the current page. Therefore, this action is a necessary first step to check if the website loads correctly and to ensure that the outcomes align with the expected indications of failure if the loading is unsuccessful.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the URL state remains unchanged at 'about:blank', indicating that the navigation was unsuccessful or interrupted.

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
**Reasoning for action:** I initiated the action to navigate to 'https://www.example.com' because it is the first website I need to access per the user story. This action is critical as it sets the process in motion to either successfully load the content of the website or to encounter issues that would indicate failure to load, thereby fulfilling the success criteria of informing the user that navigation was unsuccessful.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its content.

**Change Description:** The browser remained focused on the 'about:blank' page, indicating that the navigation to 'https://www.example.com' did not successfully load, leaving the URL unchanged.

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
**Reasoning for action:** The action of navigating to 'https://www.wikipedia.org' allows me to attempt accessing content that may be relevant to the user's interests. However, according to the acceptance test criteria, I'm expected to see an indication that the website did not load successfully and remain on the current page. This action initiates the process of loading the website while simultaneously testing the system response regarding navigation failures.

**Action:** goto('https://www.wikipedia.org') # Navigate to Wikipedia to explore its content.

**Change Description:** The browser initiated a navigation action to the Wikipedia homepage; however, the final state indicates that the URL remains unchanged as 'about:blank', suggesting that the navigation did not successfully complete.

**Screenshot before:****Screenshot after:**---

