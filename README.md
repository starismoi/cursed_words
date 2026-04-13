# Cursed Words
a python name generator

## The Why
1. I was bored in chemistry class
2. I wanted to save my cellular data instead of searching 'epic fantasy names pls' on g*ogle every 2 days
3. Why not?

## The How
1. Neovim on termux. Unfortunately, I am not very knowledged in Lua yet, so its unconfigured and it's essentially vim.

## Specifications
Cursed words categorises characters and groups of characters into *vowels*, *consonants*, *continuable consonants*, *s*, *t*, *l*, *r* and *consonant suffixes*. 
*s* and *t* are a part of the *continuable consonants* set, but they have certain exceptions on what *consonant suffixes* can be followed. As for *s*, *sch* cannot
follow *s*, and for *t*, it would be unnatural for a consonant to follow *tt*, so we enforce a vowel to follow such character groups. (This is a revised feature.)
*l* and *r* are regular *consonants*, but can be considered as the end of a syllable, and hence any character may follow.

The algorithm itself is generally quite simple, and it's effectively, cursed.
It would be a good time to inform you that this is called Cursed Words not because the words are cursed, but because the efficiency of this algorithm is cursed.
The words being cursed are an unintentional, albeit entertaining, byproduct.
