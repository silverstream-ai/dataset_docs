# Task

**User Story for Website Navigation Issue**

As a web explorer,
I navigate to various websites to explore their content and elements,
so that I can gather information and understand how different platforms present their data.

**Success definition:** Given I am on the Requestly website
When I attempt to navigate to 'httpswww.example.com' and 'httpswww.wikipedia.org'
Then I should see that the browser does not change the URL from 'aboutblank' and I should be informed of the navigation failure.

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
**Reasoning for action:** I initiated a navigation action to 'https://www.example.com' to fulfill the user's requirement of exploring different websites' content. However, given the task's specific success criteria, I must keep in mind that the URL should not change from 'about:blank' to indicate a navigation failure. This step is to illustrate the attempted navigation, allowing me to check the response from the browser and see if it adheres to the acceptance test conditions.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its elements.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the URL in the final state remains 'about:blank', indicating that the navigation did not successfully load the website.

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
**Reasoning for action:** I initiated the action to navigate to 'https://www.example.com' to fulfill the user story, which involves exploring different websites and gathering information. However, given the current state, the URL is set to 'about:blank' and according to the acceptance criteria, I need to ensure that I check how the navigation attempt behaves instead of completing it successfully.

**Action:** goto('https://www.example.com') # Attempt to navigate to a sample website to explore its elements.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the URL in the accessibility tree representation remained as 'about:blank', indicating that the navigation did not successfully change the webpage.

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
**Reasoning for action:** Before taking this action, I considered that the task requires me to navigate to the specified URLs, starting with Wikipedia. However, the user story indicates that I should see a failure in navigation and that the URL should remain 'about:blank'. Since my current state shows 'about:blank', executing the goto action will help me test the navigation behavior and observe if the browser fails to navigate as expected, allowing me to gather insights into how lift failures in URL handling are displayed.

**Action:** goto('https://www.wikipedia.org') # Navigate to Wikipedia to explore its elements.

**Change Description:** The browser remained focused on the RootWebArea and the URL did not change from 'about:blank', indicating that the navigation to 'https://www.wikipedia.org' did not successfully load the Wikipedia page.

**Screenshot before:****Screenshot after:**---

