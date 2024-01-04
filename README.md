# Language_Identification

CASE 1: Languages with no similarities
This case involves vastly different languages with very few or almost no similarities like English, Chinese, Hindi, etc.
Dataset Overview: The dataset from HuggingFace included 20,000 text samples across 20 distinct languages, uniformly distributed. It consisted of two columns: one with the text and the other with language labels corresponding to the text.

CASE 2: Languages with Common Linguistic Roots(Roman Script)
This case focuses on European languages like French, Spanish, German, etc. due to their script and linguistic affinities.
Dataset Overview: The dataset for this case was obtained from Tatoeba.com, contains 12,000 text excerpts spanning 12 European languages, including Danish, Dutch, English, French, German, Swedish, Italian, Latin, Portuguese, Spanish, Irish, and Polish. It is structured with two columns indicating Language Labels and Text Samples.

CASE 3: Languages with shared dialects
This case explores different language families such as British and American English, Brazilian and European Portuguese, etc., aiming to discern differences in pronunciation, vocabulary, idiomatic expressions, and occasional grammar nuances.
Dataset Overview: Utilized DSL Corpus dataset with 100,000 text samples for 10 Languages. These languages encompass 4 distinct dialects: English, Portuguese, Spanish and Slavic. This is the repository for the DSL Corpus Collection (DSLCC). The DSLCC is a multilingual collection of short excerpts of journalistic texts. It has been used as the main data set for the DSL shared tasks organized within the scope of the workshop on NLP for Similar languages, Varieties and Dialects.
