<!--
{
"name" : "practical-introduction",
"version" : "0.1",
"title" : "A Practical Introduction to Go",
"description" : "I will show you how to develop a simple network server that does something useful and is easy to understand.",
"freshnessDate" : 2012-01-01,
"homepage" : "http://synflood.at/tmp/golang-slides/mrmcd2012.html#1",
"canonicalSource" : "http://synflood.at/tmp/golang-slides/mrmcd2012.html#1",
"license" : "All Rights Reserved"
}
-->

<!-- @section -->

## A Practical Introduction to Go

I could bore you with describing every single feature of Go one by one.

…or, I could simply show you how to develop a simple network server that does something useful and is easy to understand.

I will show you how to develop a telnet chat server, step by step. This is what it’s supposed to be doing:
* The user connects to the chat server by telnet and is asked for a nickname.
* After entering the nickname, the user joins the chat room.
* By typing and pressing return, the user can post text that all other connected users can see.
* When the user disconnects, all other users are informed that the user left the chat room.

See the [full presentation](http://synflood.at/tmp/golang-slides/mrmcd2012.html#5).

[![Intro to Go slide](https://raw.githubusercontent.com/outlearn-content/go-path/master/assets/intro-to-go.jpg)](http://synflood.at/tmp/golang-slides/mrmcd2012.html#5)
