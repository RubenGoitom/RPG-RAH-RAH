# RPG-RAH-RAH
RPG-RAH-RAH - ReadMe file of unit testing.

Char package test suite.
This test suite verifies the functionality of the Char package, which contains classes for different types of characters in a role-playing game (RPG). It includes tests to ensure that the character classes and their associated methods are working correctly.

Tested features The test suite covers the following features of the Char package:

Character attributes and level: This includes tests to verify the starting level and attribute values of each character class, as well as their ability to level up and update their attribute values.

Item usage: This includes tests to ensure that characters can only equip items that are appropriate for their class and level, and that their attributes and DPS are updated correctly when they equip new items.

Attack and damage: This includes tests to verify that the character's health is updated correctly when they are attack, and that they can attack other characters and deal the correct amount of damage.

Skill and ability usage: This includes tests to ensure that the character can use their skills and special abilities, that their cooldowns are tracked correctly, and that the abilities have the desired effects on the character and other objects in the game.

Requirements This test suite requires the following classes to be present in the same package:

RPG.Char.Mage 

RPG.Char.Ranger

RPG.Char.Rogue

RPG.Char.Warrior

RPG.Exceptions.InvalidArmorException

RPG.Exceptions.InvalidWeaponException

RPG.Item.Armor

RPG.Item.Item

RPG.Item.Slot

RPG.Item.Weapon

Running the tests.
To run the tests, use a testing framework such as JUnit. The test suite contains a number of test methods that can be run individually or as a group.

Note The test suite assumes that the character classes in the Char package are implemented correctly and behave as expected. If any of the tests fail, it may indicate that there is an issue with the implementation of the character classes.
