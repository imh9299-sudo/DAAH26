---
title: "Assignment 1. Working with a Corpus S26"
date: 2026-02-28
categories: assignments
layout: single
---
---
# Corpus Selection "Science Fiction and Fantasy
excerpt_separator: "<!--more-->"


## Introduction

Before beginning this analysis, I was familiar with books that fell under either science fiction or fantasy, yet I could not recall reading a book that occupied both categories at once. More importantly, I could not imagine myself reading dozens of book descriptions in order to determine which texts would be most suitable for comparative analysis. This initial hesitation highlights precisely the challenge that distant reading seeks to address.  As Ama explains in “Distant Reading: A Discussion with Ama Bemma Adwetewa-Badu”, this method enables scholars to visualize and analyze patterns that otherwise would have been too vast to see by close reading alone [1]. With this in mind, I approached this corpus with the hypothesis that a strong conceptual and thematic connection between fantasy and science fiction books would emerge.
After doing an in-depth analysis from the research material gathered about my books, I noticed that some shared a few things in common. For example, all five works were published around the late 19th to early 20th century. Thus, the authors of the books were exposed to major historical events and developments such as:

  - Rapid industrialization
  - New scientific discoveries
  - Mass magazine publication culture


All five books also shared themes of similar genres:

  - Science
  - Adventure
  - Myth


Despite these similarities, they differed in other aspects, such as the ideas and “concepts” they explored:

- Cthulhu:  Ancient cosmic entities 
- Oz: Magical alternate dimension
- War of the Worlds: Alien Invasion from Mars
- Princess of Mars: Martian/Alien Civilization
- 20,000 Leagues: Deep ocean mysteries


> This course site is created in GitHub Pages by forking the **Minimal Mistakes** starter theme. I have used this theme to model how you can go about learning for yourself. When you gain more confidence you will be able to change to other themes (or even go with the full version of the Minimal Mistakes theme) and customize them to your own liking. 

## Conducting Analysis 
 
Drawing from these research-based deductions, I sketched a practical list of words for the use of Voyant. As Johanna Drucker pointed out in Chapter 7 “Data Mining and Analysis” in An Introduction to Digital Methods for Research and Scholarship, Voyant is particularly effective for distant reading because it makes statistical text analysis accessible without requiring programming expertise. As a dashboard-based platform, it allows researchers to upload texts and immediately generate visualizations such as word clouds, trend graphs, topic clusters, and keyword-in-context displays [2]. 

With this information, one can pick up patterns not easily visible through close reading. In other words, this tool’s strength lies in correlation, since clicking on a term dynamically reshapes data visualizations, encouraging comparative analysis across a corpus.


** Keywords to Search**
- Unknown
- Exploration
- Science
- Technology
- discovery
- Man
- Journey 
- Martian 

  
*Voyant Tools*


This led me to discover a few interesting points. On the trend graphs, it can be seen that, despite all books appearing under the category of “science fiction” in Project Gutenberg, only a brief mention of the words “technology” and “science”  are found in the books, these being Twenty Thousand Leagues Under the Seas: An Underwater Tour of the World by Verne (pg2488), A princess of Mars by Edgar Rice Burroughs, (pg62), and The call of Cthulhu by H. P. Lovecraft (pg68283).

Nonetheless, this makes sense, when taking into account the historical context behind the three books. Edgar Rice Burroughs, most known for his adventure narratives such as Tarzan, brought A Princess of Mars to life in 1912, during a period of widespread “Mars mania,” A Princess of Mars drew heavily on contemporary astronomical theories about a dying Red Planet advanced by Giovanni Schiaparelli and Percival Lowell [3]. 

Lovecraft, on his side, wrote in the aftermath of World War I, amidst rapid scientific advancements, where he articulated a philosophy known as“cosmicism”: the idea that humanity is insignificant in an indifferent universe. These ideas were clearly reflected in  “The Call of Cthulhu” (1928). Drawing on contemporary developments in astronomy, evolutionary theory, and archaeology, Lovecraft crafted a story in which ancient extraterrestrial beings predate human civilizations [4].

Meanwhile, as part of his “Voyages Extraordinaires” series, Jules Verne’s Twenty Thousand Leagues Under the Sea: An Underwater Tour of the World (1870) reflects the belief that science and exploration could lead a path to the unknown. Published in the nineteenth century,  an era considered to be of technological innovation, particularly in naval engineering and marine biology, the novel fused contemporary fascination with submarines and oceanography. While Verne incorporated scientific details, he also interrogated the moral implications of progress [5]

STEP 3 IMAGE OF TRENDS ON VOYANT TOOLS
<img src="images/Voyant_Trends_Part1.png" style="zoom:40%;" />

1.   "Cloning" this repository to Github Desktop

More intriguing similarities and differences could be found with the Bubblelines tool, in which the corpus is “represented as a horizontal line and divided into segments of equal length”.  This data allowed me to confirm my hypothesis that the mentions of “martians” would be aligned with the books of The War of the Worlds by H. G. Wells(pg36) and A Princess of Mars (pg62), given that both stories revolved around martian life. One of the greatest differences with one of the keywords I had chosen was “journey”, which was mostly present in The Wonderful Wizard of Oz by L. Frank Baum. L (pg55). 

Baum began his career in journalism before achieving success with children’s literature at the turn of the twentieth century. Published in 1900, The Wonderful Wizard of Oz emerged during a period of rapid American industrialization and cultural transformation. While European fairy tales by the Brothers Grimm and Hans Christian Andersen had gained popularity in Victorian England, the United States lacked a distinctly national fantasy tradition. Thus, Baum sought to create a modern American fairy tale. The novel reflects late nineteenth-century fascination with fantasy as both escape from and response to industrial modernity, which sets it closest to fall under the category of “fantasy” compared to the other books. 


<img src="images/Voyant_Trends_Part2.png" style="zoom:40%;" />


More intriguing similarities and differences could be found with the Bubblelines tool, in which the corpus is “represented as a horizontal line and divided into segments of equal length”.  This data allowed me to confirm my hypothesis that the mentions of “martians” would be aligned with the books of The War of the Worlds by H. G. Wells (pg36) and A Princess of Mars (pg62), given that both stories revolved around martian life. One of the greatest differences with one of the keywords I had chosen was “journey”, which was mostly present in The Wonderful Wizard of Oz by L. Frank Baum. L (pg55). 

Baum began his career in journalism before achieving success with children’s literature at the turn of the twentieth century. Published in 1900, The Wonderful Wizard of Oz emerged during a period of rapid American industrialization and cultural transformation. While European fairy tales by the Brothers Grimm and Hans Christian Andersen had gained popularity in Victorian England, the United States lacked a distinctly national fantasy tradition. Thus, Baum sought to create a modern American fairy tale. [6] The novel reflects late nineteenth-century fascination with fantasy as both escape from and response to industrial modernity, which sets it closest to fall under the category of “fantasy” compared to the other books. 

One word, however, caught my attention. It is not a word that I could have thought to be associated with fantasy or science fiction, but it defined its presence for having one of the highest frequencies among all books: the word “man”. It is important to notice that, although books like The Wonderful Wizard of Oz  and The Call of Cthulhu have lower frequencies, this data led me to discover how male-dominated these books are.


<iframe style='width: 371px; height: 188px;' src='https://voyant-tools.org/tool/Loom/?view=Loom&corpus=53cf498d83f95832778d4c982ae96bc9'></iframe>




*RMarkdown Notebook*


While Voyant is extremely efficient to explore this kind  of quantitative information, I was also curious on what the posit Cloud had to offer. 

When I first began using the RMarkdown notebook in posit.Cloud, Project Gutenberg Explorer,  to acquire additional visualizations, I struggled to replicate the exercise we had done in class with previous books. Nevertheless, after receiving assistance from Professor Wrisley, I understood that I had not replaced the number of the pages as they are defined in Project Gutenberg (e.g. The call of Cthulhu by H. P. Lovecraft is 68283.txt, thus, I had to introduce this number so posit.Cloud could find and extract the book from Project Gutenberg (the website). Another significant step I overlooked was downloading the libraries inside the RMarkdown notebook. This part of the process was essential, given that the following steps inside the notebook would not work and indicate an error. After downloading all the libraries, and applying diligent focus to each step, eventually the system managed to produce a Scaled Word Frequency HeatMap. 

<img src="/assets/images/Heatmap_PositCloud.png" style="zoom:40%;" />


As previously mentioned, the Voyant tools revealed that the word “man” was used across all five books. So I decided to deepen my understanding with the RMarkdown notebook. According to the HeatMap, in which the higher the frequency, the more vibrant a color inside a box would be, the word “man” was most frequent in Twenty Thousand Leagues Under the Sea, with up to 164 mentions, while the smaller frequency could be found in The call of Cthulhu. More importantly, these numbers are relatively higher than the rest in other categories, such as the use of “discovery”, “unknown”, “magic”, “myth”, or “real”, all words that are often associated with science fiction or fantasy. 





The distant reading of this corpus revealed that the defining ideas, concepts, and thematic structures associated with fantasy and science fiction are rarely stated explicitly; rather, they are most likely implied through worldbuilding and symbolic language. This subtlety could reflect the authors’ storytelling skills, as the genres in this examination are constructed through suggestion, atmosphere and setting descriptions, rather than overt declaration. The data gathered though Voyant tools and posit.Cloud supports this patter: while certain genre markers appear consistently, much of what sets these texts within fantasy or science fiction emerges contextually rather than through direct labeling. 


At the same time, one of the most striking patterns across the corpus is the dominance of the male presence within the narratives. The frequency of male-centered language not only could reflect the literary conventions of the late nineteenth and early twentieth centuries, but also opens space for broader questions about gender representation within fictional narratives during these times. 


Despite the shared classification of all five works under “fantasy and science fiction” in Project Gutenberg, the contextual research and computational findings demonstrate important distinctions, slightly disproving my initial hypothesis.  The call of Cthulhu, The war of the worlds, A Princess of Mars, and Twenty Thousand Leagues Under the Seas align more closely with science fiction due to their emphasis on technological speculation, extraterrestrial or cosmic encounters, and scientific framing. In contrast,  The Wonderful Wizard of Oz harmonized more strongly with fantasy, relying on magical systems, fantastical journeys, and mythic-like structures rather than scientific projections. Thus, the distant reading approach allowed me to access a broader comparative perspective, revealing patterns through quantitative data that might have been less immediately visible through close reading alone. 


However, there are clear limitations to the tools and methods used. While Voyant Tools and posit.Cloud effectively highlight patterns in vocabulary or frequencies, one can not ignore other methods of comprehension. As Ted Underwood comments in Chapter 5 of Distant Horizons: Digital Evidence and Literary Change, “The Risks of Distant Reading”, an overemphasis on quantitative data can take away the “literary pleasure” and the emotional impact that define the reading experience [7].


Ultimately, this project demonstrates that distant reading can be an extremely powerful and efficient tool if used correctly, with both understanding and balance. It expands the scale of analysis for a corpus and allows for interesting genre comparison across multiple texts.


<img src="/assets/images/clonerepo.png" style="zoom:60%;" />

If successful, you should be able to see the repository in the current repository tab at top left in Github Desktop. 

6.  Editing the repository on your own machine. 

Now that you have a copy of the repository on your laptop you can edit it there (even offline and with no internet connection) and then later "push" the changes to the web. 

When you edit, save in VSCode (and sometime enter a commit message in Github Desktop), you then clock `commit to master` and you will see a blue button at right `push origin`. Click it to transfer these changes to the web. That is three clicks to push something to the web!

<img src="/assets/images/pushing.png" style="zoom:25%;" />

> Remember that every time you push to the web, the compiler works to make your page's updates.  Be patient and look for the green arrow which indicates that your site has been rebuilt with the changes you made. If you see a brown dot next to the last commit message in the repository holding the site, the compiler has not finished. Go have some tea or a quick walk--it will be done soon. 

> NB: You can do some editing in the GitHub web interface itself, but I recommend editing in Github Desktop with your text editor, and certainly not mixing the web-based interface and the text editor, since you end up with a versioning nightmare. If you do make a change in the GitHub web interface, make sure that you fetch the origin. 

7. If you use the button in Github Desktop to open in external editor (choosing Visual Studio Code), we can now move on to editing any of the pages. 

Let's make some changes in VSCode and push them. 

<img src="/assets/images/pushing.png" style="zoom:25%;" />
 
Pages that have editable material to change your site: 

- navigation.yml
- _config.yml

So that you can have the landing page be a page and not a post, try this: 




Follow up posts:

- [Connecting your VSCode to CoPilot and Customizing your GitHub page](https://daahnyuad.github.io/blog/GitHub-Education-VSCode-S26/)
- Committing directly in VSCode -- coming soon

Enjoy!
