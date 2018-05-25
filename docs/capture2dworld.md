# capture2dworld

*Author: Ruthgul*<br />

### Configurable capture source for world messages
---
#### Features:
* Captures are made to an invisible 'dummy' world that is invisible to the user.
* Captures can are broadcast to other plugins which can display the messages.
* Original colors are preserved.
* Filters can be applied for both PCs and NPCs
* Supports clan chat talk, alliance talk, form talk, public channels (such as relays) and more.

#### Dependencies:
* captures.mcl

#### Aliases:
* **capture** \<channel>
  > Start capturing the target channel.
  > | Supported Channels: |||||
  > | --- |||||
  > | alliance | aucverb | irc | page | talk |
  > | announce | clan | ircverb | relay | tell |
  > | archon | form | notify | say | yell |
  > | auction | guide | novice | shout | |

* **capture relay** \<name>
  > Start capturing the target relay by name.

* **clear captures**
  > Clears the capture window. Note that this does _not_ alter the output of other plugins unless they have been explicitly designed to detect this change.

* **filter char** \<name>
  > Add a PC or NPC name to a filter list for exclusion.

* **filter word** \<word>
  > Add a custom word name to a filter list for exclusion.

* **list captures**
  > Display a list of captured channels and relays.

* **list filters**
  > Display a list of filtered names and words.

* **list relays**
  > Display a list of captured relays.

* **uncapture** \<channel>
  > Stop capturing the target channel.

* **uncapture relay** \<name>
  > Stop capturing the target relay by name.

* **unfilter char** \<name>
  > Remove a PC or NPC name from the filter list.

* **unfilter word** \<word>
  > Remove a word from the filter list.
