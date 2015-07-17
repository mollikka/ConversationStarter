Conversation Starter
=========

Dialog tree editor for generic game development

[See it in action](https://mollikka.github.io/ConversationStarter/)

## Current features

- Create and connect dialog nodes in a graphical interface
- Create dialog that branches out, merges or loops based on player choice (directed graphs, really)
- Export dialog as XML
- Specify actors for dialog lines
- Specify special event identifiers that can trigger events in your game

## Future features

- Manage actors and their portraits and assign actors to dialog lines
- Set named flags based on player choice and have it affect dialogue later
- Test/Play conversations before integrating into a game
- Include variables in the dialog (such as the player's name for example)
- Load previously saved dialog

## Implementation details

Application runs in the browser.
Implemented in Javascript using [jsPlumb 1.6.2](http://jsplumbtoolkit.com/).

Requires dom.jsPlumb-1.6.2-min.js to run.

## XML Schema

See schema.xsd for the current version.

## Purpose of the project

Conversation Starter is developed for my own projects and for the needs of my team. Since the scope of the tool is quite limited and not targeted at a second party, the main requirement is to have something working fast.

Feel free to use output generated using the tool without attribution. See LICENCE for exact rules.
