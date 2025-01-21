# FileComparison

The code takes 2 pdf files, converts it to text, converts it to english and then finds semantic similarities - it gives the key differences between the two and the percentage of similarity

#How to Use this

- I mean, I coded this in colab - ps: Not an expert
- Upload both the files and then copy the filepath to the code area marked filepath1 and 2
- It should ideally work but then it is like me at times - dumb

Install dependencies

!pip install deep_translator \n
!pip install langdetect
!pip install PyPDF2 spacy scikit-learn numpy
!python -m spacy download en_core_web_md

After this, restart your kernel

If it does not work, do not contact me. I know just as much as you
