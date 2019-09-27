<h1>Natural Language Processing</h1>

<h3> Introduction: </h3>
Language is a beautiful thing and is used for communicating thoughts, ideas, emotions and more. <br>

Natural language processing has to following issues: <br>
1. Ambigious: John shot an elephant in his pyjamas. (Its tough to tell who was wearing the pyjamas.) <br>
1.1. Ambigious Compounds: pretty little girls school. A pretty and little school for girls / A school for little girls who are pretty. <br>
2. Compositional <br>
3. Context: I am worried. It is woobly? (What does it stands for in this case) <br>
4. Cultural: What could be a positive sentiment from a statement in a culture, could be a negative sentiment in another culture. 
5. Personal: Meaning changes on personal context. Example That's sick. (For an old person this line means the things is bad, for 
young person that may mean that the thing is cool) <br>

Flavours of NLP: (linguistics)-> <br>
Concentric circles from small to big one. -> Phonetics(speech sound), Phonology(phonemes), Morphology(words), Syntax(phrases and sentences)
, Semantics(literal meaning of phrases and sentences), Pragmatics(meaning in context of discourse). <br>

Topics covered in NLP in class are of two types: <br>
1. Analysis: Word Representations, Sentence Representations, Linguistic Structure. <br>
2. Applications: Relation extraction, Question Answering, Machine translation, Language generation. <br>

<h3> Tensor flow introduction: </h3>
Written in tensor flow article, only mentioning the parts which are missing over there. <br>
Advantages of tensor flow:- <br>
1. Parallelism: One of the graph computation can happen parallely at local system and other at a remote system. The graph needs to be such that it can be independetly computed for this to happen.<br>
2. Distributed exection: The computation can happen on CPU's, GPU's and TPU's parallely as each edge can run on sepearte CPU's, GPU's etc. There is proper coordination and protcols between them to handle the communication. <br>
3. Portability: The code can be written in python and the computational graph can be generated, after that it can be converted to the low level languages like C++ from the computational graph. 
4. Complier: Tensor flow XLA compiler can be used to generate the code faster from your computational graph. <br>

There are 3 types of file generated when you run a tensor flow model: <br>
1. .meta file: It stores the graph structure. <br>
2 .data file: It stores the value of each variable in the graph. <br>
3 .index file: It stores the checkpoint information. <br> 

