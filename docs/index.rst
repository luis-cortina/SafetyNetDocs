.. SafetyNet Tools for C# documentation master file, created by
   sphinx-quickstart on Mon May 13 21:06:28 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to SafetyNet Web Automation Tools for C#'s documentation!
==================================================

SafetyNet Tools for C# is a test automation tool for Visual Studio developers and testers.

It enables the following features in your applications:

| **Recording all control inside website areas** 
| Click on a div or content control and record all interactable web elements inside of it. You can also record individual elements depending on your needs.

| **Automated CSS Selector generation** 
| The recorded controls will automatically have unique css selectors that are optimized for uniqueness and resiliency once the application changes.

| **C# Object Model** 
| All your recorded controls will be transformed into C# objects with specific types matching the web element type. We support the Page Object Model by allowing you to create multiple UI Maps files.

| **Drag and Drop UI for test creation** 
| Create tests with no previous knowledge of Selenium or C# coding. This helps your testers to collaborated with devs to create automated UI Tests.


.. toctree::
   :maxdepth: 2
   :caption: Contents:



Not a Record and Playback kind off tool
==================

We do not believe that Record and Playback is the right way to create a successful test automation framework, so we don't currently support this feature. Our suggested workflow is: 

* Record your User Interface and group controls into UI Maps following the Page Object Model.
* Create your tests using the recorded controls and reuse functionality as much as possible.
