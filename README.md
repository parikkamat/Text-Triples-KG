# Text-Triples-KG

Firstly we have unstructured text that can any documents like in this am using PDF so after that am cleaning the text like removing URL's and Contents under brackets then i do parellelly tokenize the text then and remove the punctuations but not full stop then i have just apply sentence tokenization to segement the text.

After Segmenting the text am passing each and every sentence to a function called get_entities and get_relation. so get_entities extract the head and tail entity that we called as subject, object respectively and get_relation function will exxtract the predicate from the sentence.

Finally, we have triples now that is subject,predicate and object so after applying matplotlib i just get the Knowledge Graph from that triples.
