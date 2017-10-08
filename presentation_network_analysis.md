# Presentation Template

## 1) Discussion Questions

*Write at least 3 questions that you have regarding the reading which can be discussed in class. Try to move beyond questions about content to more analytical, methodological, or fundamental questions.*

1) Do you find Algree-Hewitt's findings interesting? Why or why not?

2) What are the pros and cons of analyzing differences in character networks across different literary texts compared to focusing on one literary text alone?

3) Under which circumstances would you find it relevant to use Piper & Vala's computational tool for character analysis? (The tool analysis characters on four parameters: Distinctiveness, Centrality, Positionality, Modality) Can computational character analysis stand alone?

## 2) Summary

Summarize the article in three sentences or less.

1) **Algree-Hewitt** uses network analysis to look at changes in character networks in English plays across time (from 1500-1920). The study finds that modern plays has a smaller periphery of characters but that the number of characters in the core has increased. This indicate, that modern plays are more personal and intimate but also use a larger number of sub-networks. 

2)  **Sinha, Piper & Ruths** addresses the question: "What is interaction?". The study explores reader agreement across different types of interactions - do person A and person B both understand this text passage as an interaction. The different interaction types are identified using unsupervised clustering methods. The results are not described in the reading. 

3) **Piper & Vala** has developed a computational toll to analyze different characters and their characteristics in a text. The tool evaluates characters on four parameters: 1) Distinctiveness (how different are the character from other characters in the novel) 2) Positionality (how often is the character the agent or object of a sentence or a possessor of some object?) 3) Centrality (how important is the character to other characters in the novel?) and 4) Modality (What behaviors and attributes identify the character). The method is not further elaborated in the reading. 

In the following questions I will focus on Algree-Hewitt's study as the results of the other studies are not described. 

## 3) Level of Engagement/Analysis

*At what level does the author of the article engage with the primary source? Does the author address the contemporary culture? The text itself? Specific characters? The life of the primary text's author? The meaning of the text? An allegory? Character relationships? Formal characteristics (rhyme, meter, etc.)? What is the unit of analysis?*

Algree-Hewitt is interested in the **character relationships of English plays and how they have developed over time**. The scope is very broad and general as he looks at the change in the social networks (Number of characters? The proportions of important characters? The number of bridging characters? etc.) over a 400-year period. The dataset contains 3439 plays. 

## 4) Argument/Stakes

*What is ultimately the author's argument? Why does it matter? What's at stake? What contribution does the article make? What would we be missing if the article wasn't written?*

Algree-Hewitt's study has three main findings:
1) Modern plays have **fewer "unimportant" characters**

2) Modern plays have **a larger amount of characters with importance to the storytelling**

3) Modern plays use bridging characters to smaller extent 

## 5) Method

Especially in the Digital Humanities, most papers will employ a specific (computational) method. Network analysis? Topic modeling? Clustering? Classification? Dictionary? Simply counting?

Algree-Hewitt use **network analysis** to examine the network structures of the plays. From the network analysis he extracts three summary statistics:

1) *Gini Coefficient of the eigenvector centrality*: Measuring the distribution of centrality across characters (= what is the distribution of significance among characters) 

2) *% of characters in the top 25 % of the eigenvector centrality distribution*: Measuring how many characters that are in the core of the social network.

3) *Betweenness centrality*: Measures the importance of bridging characters (characters that mediates other characters' interaction) in the social network.

## 6) Issues

*What are some issues with the author's argument? What do you see as a potential flaw or bias? Is the author's argument limited by anything (method, corpus, etc.)? Do you have any solutions?*

Some issues can be raised:

1) Network analysis has difficulties adjusting for the variation in importance of actions and dialogues. Some character maybe very important even if he/she is only mentioned in one sentence if this sentence is crucial to the entire plot. This require a subjective evaluation of sentences which is not possible in a network analysis. 

2) The network analysis relies on explicit mentioning of the characters. This means that the method canøt take implicit character references into account. I imagine this to be very relevant for critical plays with political content as the critique often will be implicit and hidden. 

3) Algree-Hewitt has to use a digitalized database of plays to conduct the network analysis. This sample is probably not identical to the entire population of British plays in that period and is therefore probably biased toward the plays that we today find "significant of the time".

## 7) Reproducibility/Transparency

*Having read the article, could you start from zero, go step-by-step and come to the same conclusion? Provided the data, could you write code to produce the same results? Are the code and data provided and easily accessible? Is the method described in detail? This applies more to the data analysis than the humanistic conclusion.*

Reproducibility is easy and the transparency is high due to the study's high emphasis on **objective measures and the usages of a public available database** (Chadwyck Healy drama corpus). 

## 8) Broader Application

*Think about broadening the stakes of the argument. How could this method be applied to other disciplines or in industry?*

The idea of using network analysis to analyze differences in character networks can be applied to many other fields. Both within the literary discipline the same method could be used on novels and to compare the usage of characters between different authors. Furthermore, the method can be used at other texts such as new articles, research papers, press releases, business documents etc.      

