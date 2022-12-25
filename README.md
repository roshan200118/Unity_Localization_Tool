# Unity Localization Tool

The goal of this project is to create a localization system for a game using the Unity3D Editor API. The system allows for easy text editing in multiple languages and enable the game to seamlessly switch between languages. This project is developed in C# using Unity3D Editor API, ScriptableObjects, CustomEditors and OOP. 

#### This Localization Tool:
* Defines a set of **ScriptableObject** classes that store multiple strings for each language
* Use **Unity3D Editor API** to create **CustomEditors** to make it easy to create, add, and edit Languages and their key-value pairs
   * The **CustomEditors** allows for the addition, modification, and deletion of key-value pairs and ensures that the keys are consistent across all Languages 
* The tool uses the Unity UI system to create an in-game text box that utilizes the language data and can be associated with a particular key
   * The contents of this text box should update when the selected language of the game is changed
* The language selection can be made before run-time as part of the custom editor or during run-time to allow the player to dynamically change the language

#### How to Use:
* Add TextLocalizerUI script to TextUI component
* Type in the key of the value under the "Localized String" field
* Click "Search" button to search for localized values based on inputted key
    * Click the "Remove" button to very left of key-value pair in search result list to **remove** it
* Click "Edit" button to **add** a key-value pair
* If key-value pair already exists, it will **update** instead
* Can update dynamically too, to update language:
    * Navigate to Unity Edtitor Menu, select the "Languages" menu item and select the desired language
    
    

https://user-images.githubusercontent.com/61467608/209457215-eebf1fcf-5f33-4f69-acaf-848ad95f47c2.mp4

