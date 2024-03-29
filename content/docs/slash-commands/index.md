---
title: "Slash Commands"
date: 2024-01-29T21:56:14+01:00
draft: false
weight: 1
---

Tibby supports some slash commands that don't require much explanation. Those are described here :)

<!--more-->

{{< callout type="info" >}}
When reading using these commands, `[]` indicates optional parameters and `<>` indicates required ones
{{< /callout >}}

#### /8ball
**Usage**: /8ball [message]  

Provides you with a yes or no answer, if you give it a message (ideally a question) it will be included in the response.

#### /radlibs
**Usage**: /radlibs \<message\>  

Takes a message with tokens and replaces those tokens with words from the corresponding category.  

The tokens currently supported are as follows:
 - $NOUN (Singular nouns)
 - $NOUNS (Plural nouns)
 - $VERB (verb, root)
 - $VERBING (verb, root + "ing")
 - $ANIMAL
 - $FRUIT
 - $ADJ (Adjective)
 - $ADVERB
 - $CHATTER (picks a random person from chat, tries to get a nickname first but the Discord API is a little inconsistent)

#### /wisdom
**Usage:** /wisdom [quoteID]  

Returns a random quote from the quotable.io API. Each quote has an ID and you can retrieve a specific quote with its ID by passing it to the command.






