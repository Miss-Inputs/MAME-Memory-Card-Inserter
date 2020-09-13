# MAME-Memory-Card-Inserter

A MAME plugin that automatically inserts a memory card into Neo Geo games (AES or arcade machines) for you. Will probably need MAME 0.212 or later because [this commit](https://github.com/mamedev/mame/commit/cd6cd78dbe66332548eca2a259be5f767b5e68fd#diff-74ebee72075f3aa1030503e70e0a6602) is required.  

To use this, clone/download the repo and put the folder in your pluginspath, put "memory_card_inserter.ini" in homepath and edit that to have a line like this:  
`memory_card_path=/path/to/where/you/want/your/memory/cards`  
Spaces around = should probably work.  

Might not work on Windows, might not work with other weird system configurations, who knows.
