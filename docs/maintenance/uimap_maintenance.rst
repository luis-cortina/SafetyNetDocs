UI Map Maintenance
==================

One of the bigger challenges to test automation projects is how to evolve with the application under test. 
Developer tools are as productive as ever but test automation tools haven't been as good as adapting to change.
The way the tool attempts to solve this issue is just a start to becoming more productive and it consists of three main steps:

#. Finding controls that are missing or the CSS Selector doesn't work anymore.
#. Using Area Recording, repeat the recording of the areas that are saved into the UI Maps to find new controls, or old controls with updated CSS Selectors.
#. Updating References so our tests work the same.

We will be planning new and better ways to do this in the future as the tool matures.

Locate All controls
-------------------

In a nutshell, Locate all controls iterates over the controls in the UI Map and identifies the ones that can't be found using the current CSS Selectors.
Missing controls will be marked in red.



Repeat Area Recording
---------------------

Update Controls with new References
-----------------------------------

