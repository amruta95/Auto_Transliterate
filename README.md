# Auto_Transliterate

Named entity phrases are being introduced on a daily basis in the form of personal
names,organizations,locations,temporal phrases,monetary expressions.While the identica-
tion of named entities has received signicant attention,translation of all entites has not.This
translation problem is especially challenging because new phrases can appear out of nowhere,and
because many are domain specfic and can't be found in bilingual dictionaries.In this project,
we present an approach to measure the transliteration similiarity of English-Hindi word-
pairs.We propose a bi-directional mapping between one or more characters in Roman script(English)
to be transliterated into Devanagri script. We present an algorithm for computing a simi-
larity measure between the two scripts. 

This project covers following points:
1. Framework for inputting utf-16 based regional language support using roman keyboard
which will be backed by a database.
2. It will use algorithms+database to generate a sequence of utf-16 characters for given
string of ASCII characters.
3. There will be an option to add new transliterations to the database based on GUI to
teach new languages to the software.
4. The initial language support will be provided for Marathi.
