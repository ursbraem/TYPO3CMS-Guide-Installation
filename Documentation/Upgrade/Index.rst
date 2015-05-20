﻿.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. include:: ../Includes.txt


.. _upgrade:

Upgrade
-------

When a new version of TYPO3 is released, you should follow the
guideline in this chapter in order to do an upgrade. Also follow any
additional upgrade information carefully. You might e.g. want to skim
the included ChangeLog to see if any features affect the way your site
works. (Look for lines prepended with "!!!" - those are the really
important ones!)

.. note::

   **Version specific upgrade notes**

   While this guide is the general guideline to follow for a TYPO3
   Upgrade, some `version specific information are additionally available
   in the TYPO3 Wiki <http://wiki.typo3.org/Upgrade>`_. Use them as an
   amendment to this guide!

.. note::

   **Think of active users**

   Think of users who might want to do any changes during your upgrading
   and/or fallback. Inform them **before** you start!

.. note::

   **Links to unofficial upgrade walkthroughs**

   <https://jweiland.net/typo3/vortraege/typo3camp-berlin-2014.html>
   <http://stackoverflow.com/questions/28675796/how-to-upgrade-typo3-4-5-to-6-2>


Basically these are the steps to be done to update your TYPO3 site:


.. toctree::
   :maxdepth: 5
   :titlesonly:
   :glob:

   Backup/Index
   InstallTheNewSource/Index
   ConvertGlobalExtensions/Index
   UseTheUpgradeWizard/Index
   RunTheDatabaseAnalyzer/Index
   ClearCachesAndUserSettings/Index
   RemoveTemporaryCacheFiles/Index
   ChangelogAndNewsmd/Index
   UpdateExtensions/Index
   UpdateTranslations/Index

