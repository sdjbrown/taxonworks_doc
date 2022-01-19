# Biological relationship composer

Before a biological relationship can be assigned, the nature of the relationship needs to be created using the Biological relationship composer task (`PROJECT/tasks/biological_relationships/composer`).

Creating a biological relationship minimally requires a `Name` which describes the relationship between the focal taxon and its associate. It also is able to accept an `Inverted name` which describes the associates relationship with the focal taxon.

Examples include:
| Name | Inverted name |
| ---  | --- |
| feeds on | predated by |
| parasite of | host of |



There are also two check boxes which can be selected if desired, but are not necessary for creating the relationship:
- Is transitive
- Is reflexive 

## Transitive relationships
A relationship is transitive, if the same relationships of the associate can truly be  relates back to the focal organism.

The following are examples of transitive relationships:
- If *a* > *b* and *b* > *c* then *a* > *c*

The following are *not* examples of transitive relationships:


## Reflexive relationships
A relationship is reflexive, if it relates back to the focal organism.

The following are examples of reflexive relationships:
- "Is equal to"
- "Is less than or equal to"

The following are *not* examples of reflexive relationships:
- "Is not equal to"
- "Is less than"

## Deleting biological relationships
If a relationship is no longer required, it can be deleted from the Biological relationship data page (`PROJECT/biological_relationships/list`).
