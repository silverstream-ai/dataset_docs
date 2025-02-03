# Task

**User Navigation Exploration**

As a web explorer,
I navigate to various external websites to explore their elements,
so that I can understand how different web pages are structured and what features they offer.

**Success definition:** Given I am on the cloudchipr website and want to explore external sites
When I attempt to navigate to 'httpswww.example.com' and 'httpswww.wikipedia.org'
Then I should see that the navigation does not successfully load either page, indicating a potential issue with website access or navigation settings.

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
**Reasoning for action:** I took this action to initiate the navigation process to 'https://www.example.com', which is essential for fulfilling the user story of exploring external websites. By trying to access this URL, I am testing the functionality of the web explorer in observing how the browser responds to navigation requests. This is a key step towards the acceptance test where I need to verify whether the page loads successfully or indicates a navigation issue.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its elements.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', however, the URL remained as 'about:blank', indicating that the page did not load successfully or the focus did not shift from the initial state.

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
**Reasoning for action:** I chose to navigate to 'https://www.example.com' in order to fulfill the user story's requirement of exploring external websites. This action is necessary to check if the website loads properly, which will provide insights into its structure and features. Since the current browser state shows 'about:blank', this action is a crucial first step toward loading the desired external content and understanding potential navigation issues.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its elements.

**Change Description:** The browser performed a navigation action to load 'https://www.example.com', but the final state shows that the URL remains 'about:blank', indicating that the navigation was unsuccessful and the page has not changed.

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
**Reasoning for action:** By initiating the navigation to 'https://www.wikipedia.org', I am directly following the user's intent to explore external websites. This action is designed to load the Wikipedia page to see if it can be accessed successfully. If the navigation doesn't work, it will confirm the user's suspicion about potential issues with website access or navigation settings, thus aligning with the acceptance criteria.

**Action:** goto('https://www.wikipedia.org') # Navigate to Wikipedia to explore its elements.

**Change Description:** The browser attempted to navigate to 'https://www.wikipedia.org', but the URL remained unchanged as 'about:blank', indicating that the navigation did not successfully load the Wikipedia page.

**Screenshot before:****Screenshot after:**---

