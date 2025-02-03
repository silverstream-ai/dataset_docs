# Task

**Explore External Websites**

As a curious internet user,
I navigate to various websites to explore their content,
so that I can gather information and learn more about different topics.

**Success definition:** Given I start navigating the web from the initial URL
When I attempt to access external websites like 'httpswww.example.com' and 'httpswww.wikipedia.org'
Then I should see that my browser remains on 'aboutblank' after each navigation attempt, indicating a failed state change.

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
**Reasoning for action:** I attempted to access 'https://www.example.com' to facilitate the user's goal of exploring website content. However, since the browser is currently at 'about:blank', this action would likely fail due to security or configuration settings that prevent navigation from this state. This aligns with the acceptance criteria, as it confirms that the browser remains on 'about:blank', indicating a failed state change.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the URL in the accessibility tree representation remains 'about:blank', indicating that the navigation did not successfully update the browser state.

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
**Reasoning for action:** I initiated the action to navigate to 'https://www.example.com' because the user story mentioned a curiosity to explore various websites. However, the acceptance criteria state that after such navigation attempts, the browser should remain on 'about:blank', suggesting that the operation will not succeed. This action was essential to fulfill the task of verifying whether the navigation results in a successful state change or not.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its content.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the URL remains unchanged as 'about:blank', indicating that the navigation did not successfully occur.

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
**Reasoning for action:** I attempted to navigate to 'https://www.wikipedia.org' because the user is interested in exploring various websites to gather information on different topics. However, based on the success criteria, this action should not succeed, as the browser is supposed to remain on 'about:blank' after any navigation attempt. Therefore, while the action was executed in the spirit of exploration, I expected that it would not lead to a change in the URL, thus confirming the user's requirements.

**Action:** goto('https://www.wikipedia.org') # Navigate to Wikipedia to explore its content.

**Change Description:** The browser navigated to 'https://www.wikipedia.org', but the URL in the accessibility tree representation is still displayed as 'about:blank', indicating that the navigation did not successfully change the browser's state.

**Screenshot before:****Screenshot after:**---

