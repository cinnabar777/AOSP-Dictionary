# AOSP-Dictionary

Test Dictionary files. 

Most of the files here are word lists created from dictionaries, broken up into groups, for anyone wanting to create their own dictionary. There are a couple test dict files, tiny and big, that were used to test frequency behavior.

A usable dict file for those wanting an AOSP dic that's not massive and filled with acronyms and capitalized words: 

I took the HeliBoard word list and purged it of:

1. All all cap words
2. Capitalized words with f=130 and lower
3. All words below f=10
4. Spell checked it to remove misspelled words
5. Removed extra meta data

It went from ~14Mb to 3.4! The [dict file is here](https://github.com/cinnabar777/AOSP-Dictionary/blob/main/Personal_Dic/HeliBoard_trimmed.dict) and the [cleaned word list is here](https://github.com/cinnabar777/AOSP-Dictionary/blob/main/Personal_Dic/HeliBoard_trimmed.txt), in the personal folder.

