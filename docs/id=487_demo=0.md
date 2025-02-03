# Task

**User Navigation Journey**

As a curious internet user,
I explore various websites and their content,
so that I can gather information and learn from diverse sources.

**Success definition:** Given I am on a browser with an aboutblank state
When I attempt to navigate to 'httpswww.wikipedia.org' and 'httpswww.google.com'
Then I should observe that the URL remains unchanged at 'aboutblank', indicating that the navigation failed.

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
**Reasoning for action:** The user's objective is to navigate to various websites to gather information. By trying to go to 'https://www.example.com', I'm initiating a browser action to explore its content. However, since the instruction states that any attempt to navigate should fail and keep the URL at 'about:blank', I need to ensure this action adheres to the specified conditions that demonstrate the browser won't navigate away from this state.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the URL remains unchanged as 'about:blank', indicating that the navigation did not successfully take place.

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
**Reasoning for action:** However, given the success criteria indicates that the URL should remain unchanged at 'about:blank', I need to confirm that this navigation does not actually succeed. Generally, if the browser is indeed in an 'about:blank' state, an invalid URL format without the proper scheme (like 'https://') will not lead to a proper navigation, thus resulting in the expected behavior.

**Action:** goto('https://www.wikipedia.org') # Navigate to Wikipedia to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.wikipedia.org', but the URL remained 'about:blank', indicating that the navigation did not occur and the initial state was unchanged.

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
**Reasoning for action:** I initiated the navigation to 'https://www.google.com' in order to fulfill the user's goal of exploring diverse sources of information online. However, given that the current browser state is 'about:blank', this action aims to verify whether the URL successfully changes. According to the acceptance test, the expectation is that the URL will remain 'about:blank', thus confirming the failure of the navigation attempt. This helps to validate the current conditions outlined in the success criteria.

**Action:** goto('https://www.google.com') # Navigate to Google to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.google.com', but the URL remains unchanged at 'about:blank', indicating that the navigation did not successfully take place.

**Screenshot before:****Screenshot after:**---

