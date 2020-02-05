# CSV-sorter-for-sketchengine
Sort a list of lexical data and their frequencies in a CSV file and separate garbage data in it

This is just a simple exercise for a practical task of separating noise from actual Tagalog language data (lexical units with the initial ik(in)a-. 
The program opens the csv data file downloaded from sketchengine.eu. Then, regexs are used to find all data items containing digits, numerals, or only one syllable after the initial ik(in)a-, since these are more likely not to be causal voice forms.
The separated data is written into files in order to be checked manually afterwards to identify any mistakes in the sorting process.
