UI Map Maintenance
==================

One of the biggest challenges to test automation projects is how to evolve with the application under test. 
Developer tools are as productive as ever but test automation tools haven't been as good adapting to change.
The way this tool attempts to solve this issue is just a start to becoming more productive and it consists of three main steps:

#. Finding controls that are missing or the CSS Selector doesn't work anymore.
#. Using Area Recording, repeat the recording of the areas that are saved into the UI Maps to find new controls, or old controls with updated CSS Selectors.
#. Updating References so our tests keep working the same.

We will be planning new and better ways to do this in the future as the tool matures.

Locate All controls
-------------------

In a nutshell, Locate all controls iterates over the controls in the UI Map and identifies the ones that can't be found using the current CSS Selectors.
Missing controls will be marked in red.

.. image:: images/locating_controls.gif
   :align: center

Repeat Area Recording
---------------------

Repeat Area Recording is an easy way to repeat the recording within the areas you clicked while first creating the UI Map. This will take into account the recording settings currently saved
to the file. This will add any new controls that is not currently in the UI Map.

.. image:: images/repeat_area_recording.gif
   :align: center

Update Controls with new References
-----------------------------------

The third step is to update broken controls with new ones recorded using either the area recording or the click recording tool.

.. image:: images/update_control_refs.gif
   :align: center
