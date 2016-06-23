# Chits
Chits is an extensible chatbot platform, where you simply use a trigger word to create your own "Chitbot".

## Chitbots
Chitbots are the core of Chits. They are essential to providing the functionality of Chits. Even the repeating check, that makes sure commands don't get repeated until the next command is sent, is controlled by a Chitbot.

### Chitbot Types

There are 3 types of Chitbots: Core, Command, and Toggle. Here's a list of what they do:

* Core - Essential to Chits, cannot be disabled by the Per-Chitbot Toggler, if deleted can break Chits.
* Command - Do something when a certain command (or more) are typed in
* Toggle - 4 commands that toggle a variable. Official ones use `.enable___`, `.disable___`, `.toggle___`, and `.check___`.

### All Official Chitbots

Here is a list of all official Chitbots as of v2.0. Commands that Chitbots add can be found in the help menu. *(the command for the help menu is your command prefix plus `help`.)*

* Time
* Helper
* Repeating Check Toggle
* Traces
* End Chat
* MSG Count
* Command Count
* Toggle
* Counter
* Matrix
* Defaults
* MSG Sender
* Prefix

An official Chitbot is one that follows the guidelines and comes as part of the default .SB2 and .SWF files. They also cannot overlap functionality with other commands.
