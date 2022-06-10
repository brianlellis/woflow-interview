# Solution and Reasoning
 1. All that was asked was a max_occ and unique_length. Otherwise I would have rendered a tree mapping representative of the call that was done over fragmented API calls.

 2. Object mapping was the easiest method to be readable and give final values. Promise.all was used (this was vanilla otherwise a method similar to the aggregate axios method would have been used).

 3. Did not pass root into tree object as it was assumed that the root could simply be added in calculation as the prescence of root could have unintended infinite loop issue if there root was a child which would cause self referential circular invocations or abrupt stop of script.

# Additional Info if Needed
Can render a tree representation client side if required or if the solution would like to be realized in another language.