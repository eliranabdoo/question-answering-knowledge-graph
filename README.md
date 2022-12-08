# question-answering-knowledge-graph
A small project for question answering free-text questions from large-text in a indirect manner, where hops might be needed
Uses classic NLP methods to convert sentences to Entity-Relation-Entity triplet and build a knowledge graph, followed by TransH as a next-step ranking mechanism,
and finally uses an (perhaps novel) adaption for beam search to traverse through the graph.
