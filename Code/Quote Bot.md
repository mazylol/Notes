# Objective
---
Create a bot that can quote a users message

## Commands
* `/quote`
	* `/quote add <title> <text> <author>` -> Adds a quote
	* `/quote del <id>`
	* `/quote get <keyword> <author>` -> Gets a quote with a specific keyword in the title from an author
	* `/quote list <author>?` -> Lists the titles of every quote from an author defaults to yourself

## Stack
* Lang - C#
* Discord Lib - DSharpPlus
* Database - Mongo