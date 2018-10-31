Here we have two csv files to import into sqlite to practice doing queries.

parent.csv  -- contains parents names and id's.
child.csv  -- contains children names, ages, parentid's and id's.

Use the power of sql to make a report with parent names, and their youngest and oldest children.


# Setup

import this csv's into tables.

you should be able to see

## Tasks

    Make a list of parent names, with their youngest and oldest children

For example:

ParentName, Youngest, Oldest
John, bobby, david
Marcela, ginny, juan

## Desired Result

    Sue, bobby, maximillian
    bob, christy, NULL
    amol, meep, meepmeep
    peppy, blahhhh, blech
    archibald, NULL, NULL

How would you do this?  Could you do it in a single query?  CTE?  Union of queries?



