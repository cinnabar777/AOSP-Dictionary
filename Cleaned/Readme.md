
# AOSP-DICTIONARY 

A usable dict file for those wanting an AOSP dictionary that's not massive and filled with acronyms and capitalized words: 

I took the HeliBoard word list and purged it of:

1. All all cap words
2. Capitalized words with f=130 and lower
3. Removed cap words from bigrams 
4. All words below f=10
5. Spell checked it to remove misspelled words
6. Removed extra meta data

This folder contains both the default and experimental HeliBoard dictionaries. 


# UNIFIED

The unified files combine the HeliBoard main and experimental with the FUTO keyboard dictionary, then"cleaned" as above, removed low level words..., and instead of removing all the capitalized words I reduced their rank to f=1, after discussion with Gemini this seemed the best option to minimize capitalized words constantly being suggested on FUTO keyboard, as it doesn't handle offensive words like AOSP keyboard do, it totally and permanently blocks them. All the offensive have been given f=0.

# WARNING

FUTO keyboard does not seem to adhere to the offensive block, some words are blocked during glide typing and others are not though they have the flag. 

I set the offensive flag to AOSP standard with all words that are flagged to f=0, but an exact gesture will most likely bring up the word.





