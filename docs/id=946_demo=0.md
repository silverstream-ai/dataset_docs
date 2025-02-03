# Task

**User Story for Navigating Web Content**

As a web explorer,
I navigate between different websites to explore varied content,
so that I can find specific information and broaden my knowledge from reliable sources.

**Success definition:** Given I am on the initial web page of Struct app
When I attempt to navigate to Wikipedia, then to Google
Then the system should reflect that the navigation was unsuccessful and the URL remains unchanged.

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
**Reasoning for action:** The user's goal is to explore different websites to find specific information. By navigating to 'https://www.example.com', I am making the first step in this exploration process. This action allows me to access the content of a sample website, which is necessary to broaden my knowledge from the reliable sources provided in the user's story.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its content.

**Change Description:** Despite the action taken to navigate to 'https://www.example.com', the browser state remains unchanged with the URL still displaying 'about:blank', indicating that the navigation did not occur successfully.

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
**Reasoning for action:** Since the user story states that they want to explore varied content by navigating between websites, my action of attempting to navigate to Wikipedia is aligned with their goal. However, the acceptance test specifies that the navigation should be unsuccessful and the URL should remain unchanged. The browser state at this moment is 'about:blank', indicating there is no valid page loaded yet. Therefore, the action of navigating to Wikipedia should not change the URL as per the defined success criteria.

**Action:** goto('https://www.wikipedia.org') # Navigate to Wikipedia to explore its content.

**Change Description:** The browser state remained focused on the initial web area and the URL did not change, indicating that the navigation to Wikipedia did not occur successfully.

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
**Reasoning for action:** However, this action does not align with the user's goal of remaining on the initial page of the Struct app while testing unsuccessful navigation. The navigation to Google directly contradicts the test condition that states the URL should remain unchanged. In this scenario, I should not have proceeded with the goto action, because it would mean the navigation was successful instead of reflecting an unsuccessful navigation.

**Action:** goto('https://www.google.com') # Navigate to Google to explore its content.

**Change Description:** The browser initiated a navigation action to 'https://www.google.com', but the URL in the accessibility tree representation remains 'about:blank', indicating that the navigation was unsuccessful or not completed.

**Screenshot before:****Screenshot after:**---

