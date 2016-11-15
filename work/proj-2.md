---
title: Scrabble C++
---

![Scrabble]({{ site.github.url }}/assets/img/work/proj-2/scrabble.jpg)


For my scrabble program, I created the board from my board class, with a pointer to a class that was a DLL, which that had another pointer to another DLL. I designed the gameplay to promp$
        For my bag class, I have an array of 27 pieces for letters ‘A’ through ‘Z’, plus the ‘ ‘ blank tile. To use this class efficiently, I made sure that as pieces are randomly drawn f$
        The validity of my approach to this program is seen from my zero memory leaks, and the efficiency I have when I have the player insert x-y-coordinates to insert their word, which $
        My board shows a complete object oriented programming hierarchy, it contains: the row pointer (creating the board and can pass pieces into it for inserting, as well as counting th$
        The major design changes I had to make was in the beginning, where I thought the board was impossible to make DLL of DLL, so Instead I implemented a “triply-linked list”, with thr$
        The average efficiency of using a DLL for building it is O(1) since it’s recursively adding at the end ‘N’ amount of times based off what the user wants the size of the board to b$
        Besides a DLL of DLL, I’ve heard from tutors that a multi-threaded array would have been more efficient that a DLL of DLL since we can have direct access to the x and y coordinate$
        For my hand and bag, I used an array and now I understand why I should have picked a different data structure. Using an array is not useful for deleting since I had to reorganize $
        If I had more time, for my hand and bag, I would just have used a DLL of DLL for the bag, and a DLL just for the hand, since I already wrote and implemented them. Deleting and reo$
        For my debugger process, I used gdb to run through my row pointers, making sure my previous and next pointers were connected at the correct places, and figuring out why my x and y$
        A problem that I had that I was able to fix with gdb was my draw piece function from my bag, which at the beginning was drawing the same pieces over and over again into my player’$
        For the valgrind, I was able to see where my destructors were going wrong, and from this I learned that you cannot delete arrays the same as you do with your DLL of DLL. DLL need $

![Scrabble]({{ site.github.url }}/assets/img/work/proj-2/scrabble2.jpg)
Although the game wasn't perfect and you can literally play any word, it was a fun learning experience - as coding always should be. If you don't have fun, don't code it.