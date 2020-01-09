.. SafetyNet Tools for C# documentation master file, created by
   sphinx-quickstart on Mon May 13 21:06:28 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to SafetyNet Web Test Tools for C#'s documentation!
=================================================================

SafetyNet Tools for C# is a test automation tool for Visual Studio developers and testers.

It enables the following features in your applications:

| **Recording all control inside website areas** 
| Click on a div or content control and record all interactable web elements inside of it. You can also record individual elements by clicking on them.

| **Automated CSS Selector generation** 
| The recorded controls will automatically have unique css selectors that are optimized for uniqueness and resiliency once the application changes.

| **C# Object Model** 
| All your recorded controls will be transformed into C# objects with specific types matching the web element type. We support the Page Object Model by allowing you to create multiple UI Maps files.

| **C# Coded Tests** 
| A powerful way to allow developers to create and maintain tests.

| **Drag and Drop UI for test creation** 
| Create tests with no previous knowledge of Selenium or C# coding. This helps your testers to collaborated with devs to create automated UI Tests.


Not a Record and Playback Tool
==============================

We do not believe that Record and Playback is the right way to create a successful test automation framework, so we don't currently support this feature. Our suggested workflow is: 

* Record your User Interface and group controls into UI Maps following the Page Object Model.
* Create your tests using the recorded controls.
* Create reusable functionality snippets to speed up maintenance.
* Test early and often to maximize the test framework benefits.


.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: Introduction

   intro/getting_started
   intro/recording

.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: Recording Controls

   recording/area_recording
   recording/click_recording
   recording/add_custom_css
   recording/control_attributes

.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: UI Maps Maintenance

   maintenance/uimap_maintenance

.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: Writing Tests

   tests/coded_tests