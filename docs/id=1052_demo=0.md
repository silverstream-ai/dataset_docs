# Task

**Exploring External Websites**

As a curious user,
I navigate to various online resources,
so that I can explore and analyze different website elements for better understanding.

**Success definition:** Given I have started on the initial URL 'httpsfrigade.com'
When I attempt to navigate to external websites
Then I should see an error indicating that the navigation did not complete successfully.

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
**Reasoning for action:** I chose to navigate to 'https://www.example.com' as it is a well-known sample website that typically contains various elements to explore. However, given that the acceptance test indicates I should see an error for navigation failures, my reasoning suggests that this action will result in an error message since external navigation is expected to fail according to the user's acceptance criteria.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its elements.

**Change Description:** The browser attempted to navigate to 'https://www.example.com', but the URL remains 'about:blank', indicating that the navigation did not successfully update the page content or URL.

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
**Reasoning for action:** Since the user story indicates an interest in exploring and analyzing website elements, navigating to 'https://www.example.com' is a step that allows me to engage with an external web resource. However, the requirement specifies that when attempting to navigate to external websites, an error indicating the navigation did not complete successfully should be displayed. This means I need to monitor the navigation process to ensure that the expected error occurs, as this will allow us to validate the defined criteria in the acceptance test.

**Action:** goto('https://www.example.com') # Navigate to a sample website to explore its elements.

**Change Description:** The browser navigated to 'https://www.example.com', but the URL did not update in the final state representation, indicating that the navigation did not complete successfully and the page remained at 'about:blank'.

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
**Reasoning for action:** In order to fulfill the user story of exploring and analyzing different website elements, I attempted to navigate to Wikipedia, which is a well-known resource that offers a variety of elements for analysis, such as text, images, links, and navigation menus. However, according to the acceptance test criteria, I expect to see an error indicating that the navigation did not complete successfully. This means that my action of going to an external site may lead to an error, which is what the acceptance criteria specifies.

**Action:** goto('https://www.wikipedia.org') # Navigate to Wikipedia to explore its elements.

**Change Description:** The browser navigated to 'https://www.wikipedia.org', but the focus remains on 'about:blank', indicating that the page is not fully loaded or that navigation did not complete successfully.

**Screenshot before:****Screenshot after:**---

