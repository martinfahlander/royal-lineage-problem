# Royal heir problem
Calculates the most suitable heir in a royal family, based on the heritage of the candidates. The heritage is calculated by examining the heritage of the candidate's parents, whose heritage also is examined if necessary. This is repeated through a recursive function until either the king or an individual without royal blood is found.
# Input
Input syntax:
```
number_of_relations number_of_candidates
king
descendant parent parent
descendant parent parent
descendant parent parent
candidate
candidate
candidate
```
Input example:
```
5 2
charles
philip charles diana
elizabeth charles diana
louis philip matilda
victoria philip matilda
arthur louis helena
arthur
victoria

```
# Output
Output syntax:
```
name_of_heir
```
Output example:
```
victoria
```
