# coronavirus-headlines

This is a repository of my work and the supporting files from my upper division computer science class at CMC. 

Basically, names.py is a python file that works to analyze headlines related to COVID-19 and utilizes machine learning in order to build a model that will determine the news organization that it came from.

The corona.multilang100.jsonl.gz file is the multilingual dataset that was ulitilized for this project.

The explain outputs folder is to show the model in action both at a character and word based level. The saturation level of the green is to show a human viewer what the model has determined to be important for its decision-making, the darker the color the more important it is.

The embeddings folder is the version of the model that I ended up with, after numerous hours of training to ensure that it was largely accurate. It had grouped the headlines into numerous groups based on the similarity of the headlines across languages.
