# AOSP-Dictionary

Test Dictionary files for AOSP keyboard: FUTO keyboard, HeliBoard... 

Most of the files here are word lists created from dictionaries, broken up into groups, for anyone wanting to create their own dictionary. There are a couple test dict files, tiny and big, that were used to test frequency behavior.

A usable dict file for those wanting an AOSP dic that's not massive and filled with acronyms and capitalized words: 

I took the HeliBoard word lists and purged them of:

1. All all cap words
2. Capitalized words with f=130 and lower
3. Removed cap words from bigrams 
4. All words below f=10
5. Spell checked it to remove misspelled words
6. Removed extra meta data

You can find them in the "cleaned" folder. 

Note: currently FUTO keyboard does not hide words that are f=0 and it generally suggests words with very low f#, therefore, there isn't a way to have a comprehensive dictionary without deteriorating glide typing, therefore, it's best for glide typing to use a smaller more focused dictionary. 











