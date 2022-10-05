## cop3502c-act01
lots of dynamic memory allocation, pointers, and pointer arrays

### details 
several small monster trainers have come to you for advice regarding expeditions they're planning into various regions. write a program to estimate how many monsters of each type they can expect to capture in each region.

you've got a Small Monster Index that tells you the name, type, and relative commonality of all the small monsters in question.\
you've also got an atlas that tells you about the relevant regions and which small monsters are present in them.\
each trainer tells you which regions they're visiting, and how many monsters they intend to capture per region.\
to estimate the number of a given monster M a trainer will capture in a region R: divide relative population of M in R by R's total relative population, multiply the result by the total number of captures the trainer intends per region. round this result to the nearest integer. .5 rounds up, so use round(). 

### data structures 
the structures used for the monsters, regions, itineraries, and trainers are provided in the header file. i will allocate, read, compute upon, output from, and subsequently free: the monster index, region atlas, and list of trainers. 
