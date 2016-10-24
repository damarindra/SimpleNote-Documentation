.. SimpleNoteDocs documentation master file, created by
   sphinx-quickstart on Tue Oct 18 15:25:15 2016.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to SimpleNoteDocs's documentation!
==========================================

Simple Note is a plugin for taking a note inside Unity Editor.

Create a Global Note
--------------------

- Open Notes window by click Window/SimpleNote/Show Notes

.. image:: /img/SimpleNoteGlobalShow.PNG

- Click button Add a Note
- Click text to Edit
- click button 'x' to remove
- click button '-' to minimize

.. image:: /img/SimpleNoteGlobal.PNG

Create a Note to GameObject
---------------------------

- Select GameObject which want to add a note
- Right click the GameObject on hierarchy and Select SimpleNote/Add or Remove Note

.. image:: /img/SimpleNoteAdd.PNG

- Then a new note appears in Scene View.
- Click text to edit

.. image:: /img/SimpleNoteGameObject.PNG

Add a Note to Script Component and Variable
--------------------------------

- Open Script you want to add Note
- If you want to add note at the Main Class, write Attribute ``[SimpleNote]`` before declare class.
- If you want to add note at Variable, write Attribute ``[HelpBox("Note", MessageType)]`` before declare variabel

.. image:: /img/SimpleNoteClassImplementation.PNG

.. image:: /img/SimpleNoteClass.PNG

Simple Note Preferences
-----------------------

Windows : Edit/Preferences/Simple Note

Mac : Unity/Preferences/Simple Note

.. image:: /img/SimpleNotePreference.PNG
