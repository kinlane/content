---
layout: post
title: 'EXT JS and Solid Framework'
---
I have blogged about my usage of EXT JS Framework. I am adopting it for usage at my company right now and plotting the next stages in our event management software products.<p></p>
It has taken me some considerable work to learn how EXT JS works and how to adopt it for the best usage throughout our software. Some simple things just become real hard for me to do.<p></p>
However the separation of the presentation layer is awesome. I truly feel like I have things separated now.<p></p>
I have built a whole middle layer using CFC in ColdFusion to return JSON to the EXT JS calls. The CFC in turn use stored procedures to handle all the database queries.<p></p>
Its clean....it works. When I want to add a new way at getting at data....I can usually use the same stored procedure and extend an object to return the data I need....slightly configure the EXT JS element...and done.<p></p>
Its definitely a different way of programming...seems more true to the way I like to program. Now I have to sell it to the rest of our development staff.
