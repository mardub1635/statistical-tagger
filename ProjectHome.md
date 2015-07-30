This tagger was my first big python project in first year of NLPMaster, I did all alone. This tagger takes a text as an input and a dictionary called 'dico.txt'.

The dictionary is a list of words with their grammatical categories :
le article nom pronom
poule nom
un article
etc.

The text must contain sentences with  ambiguous or non-ambiguous words of the dictionary. The program will learn from the position of the non-ambiguous words what is the best tag to give to ambiguous words.

At the end the program gives you the tagged text "textEtiq.txt" where most of the ambiguous words are correctly tagged.

example of result on an ambiguous text written in texte.txt :
  * (I read a book and I book a ticket) -> I<['pronom']>read<['verbe']>a<['article']>**book<'nom'>**and<['conj']>I<['pronom']>**book<'verbe'>**a<['article']>ticket<['nom']>

_To run this program go to "download" unzip the file and run in a terminal 'python StatTagger.py'_

**What did I learn with this project ?**

  * I discovered that I like writing code and imagine the bests algorithms
  * that having a readable code is the best way to limit bug's and correct the problems. That's why I decided to complete my formation with the class of Stanfordhttps://www.coursera.org/course/programming1 : to correct my coding style, and to know how to write comment properly.