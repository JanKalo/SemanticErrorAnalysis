# Understanding Distantly Supervised Relation Extraction through Semantic Error Analysis


## Abstract:
Automatic knowledge graph construction, using supervised relation extraction from text, has become the state-of-the-art to create 
large-scale repositories of background knowledge for various applications. 
Recent advances in machine learning and Natural Language Processing (NLP), in particular the advent of the large language models, have 
improved the performance of relation extraction systems significantly.  
Traditional leaderboard style benchmark settings show very high performance, suggesting that these models can be employed in practical applications.
Our analysis shows that in reality, though, the extraction quality varies drastically from one relation to another, with unacceptable performance 
for certain types of relations.
To better understand this behaviour, we perform a semantic error analysis on a popular distantly supervised benchmark dataset, using ontological meta-relations to describe various error categories, which 
shows that relations that are confused by state-of-the-art systems are often semantically closely related, e.g., 
they are inverses of each other, in subproperty relations, or share the same domain and range.
Such an extensive semantic error analysis allows us to understand the strengths and weaknesses of extraction models in a semantic way and 
to provide some practical recommendations to improve the quality of relation extraction in the future.



## Reference:



```bibtex
@inproceedings{kalo2022semerror,
  title={Understanding Distantly Supervised Relation Extraction through Semantic Error Analysis},
  author={Kalo, Jan-Christoph and Kruit, Benno and Schlobach, Stefan},
  booktitle={Automated Knowledge Base Construction},
  year={2022}
}

}
