# Extension-Variables

Simple plugin showcasing the capabilities of handlebars and chat metadata in extensions.

## How to use

Type the following variables in the user messages or have these generated by the AI bots.

1. `{{getvar "foo"}}` - gets replaced with the value of the variable "foo".
2. `{{setvar "foo", "bar"}}` - sets a value of "bar" to the variable "foo".
3. `{{listvar}}` - gets replaced with the comma-separated list of all the previously defined variables.

## FAQ
1. Quotes around the strings are important.
2. Can't be used in the A/N, WI, or character cards. Only in the chat messages!
3. Variables are persisted per chat, and saved to the chat_metadata object.
