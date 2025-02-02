# CygnusClassification
CygnusClassification is a classification of tons of different types of the Cygnus extension.

## Cygnus
Is a main server software. But it still doesn't have the game logic yet. But it will trying to find current server type on environment variables.
When the server type is found, it will then go to this repository to download the existing url by server type ID.

## Cygnus extension
Cygnus extension is an extension of Cygnus that will run the game logic, for example Crystal Wars, Sky Block, etc. It will be also using Elnath as the Game API.

## Questions
A: Why didn't just implement the game in Cygnus?
B: Because our server is will be dynamically changed overtime. And we can't just implement all of the games logic into Cygnus itself, because it would make the server size larger.
