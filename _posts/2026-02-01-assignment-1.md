---
title: "Assignment 1"
date: 2026-02-28
categories: assignments
layout: single
---
---
title: "Creating a Static Site in GitHub Pages S26"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - lab
  - S26
  - Markdown
  - Github Pages
  - VSCode
---

## Introduction

Before beginning this analysis, I was familiar with books that fell under either science fiction or fantasy, yet I could not recall reading a book that occupied both categories at once. More importantly, I could not imagine myself reading dozens of book descriptions in order to determine which texts would be most suitable for comparative analysis. This initial hesitation highlights precisely the challenge that distant reading seeks to address.  As Ama explains in “Distant Reading: A Discussion with Ama Bemma Adwetewa-Badu”, this method enables scholars to visualize and analyze patterns that otherwise would have been too vast to see by close reading alone [ ]. With this in mind, I approached this corpus with the hypothesis that a strong conceptual and thematic connection between fantasy and science fiction books would emerge.
After doing an in-depth analysis from the research material gathered about my books, I noticed that some shared a few things in common. For example, all five works were published around the late 19th to early 20th century. Thus, the authors of the books were exposed to major historical events and developments such as:
Rapid industrialization
New scientific discoveries
Mass magazine publication culture
All five books also shared themes of similar genres:
Science
Adventure
Myth
Despite these similarities, they differed in other aspects, such as the ideas and “concepts” they explored:
Cthulhu:  Ancient cosmic entities 
Oz: Magical alternate dimension
War of the Worlds: Alien Invasion from Mars
Princess of Mars: Mars (Alien) Civilization
20,000 Leagues: Deep ocean mysteries


> This course site is created in GitHub Pages by forking the **Minimal Mistakes** starter theme. I have used this theme to model how you can go about learning for yourself. When you gain more confidence you will be able to change to other themes (or even go with the full version of the Minimal Mistakes theme) and customize them to your own liking. 

## Conducting Analysis 
 
Drawing from these research-based deductions, I sketched a practical list of words for the use of Voyant. As Johanna Drucker pointed out in Chapter 7 “Data Mining and Analysis” in An Introduction to Digital Methods for Research and Scholarship, Voyant is particularly effective for distant reading because it makes statistical text analysis accessible without requiring programming expertise. As a dashboard-based platform, it allows researchers to upload texts and immediately generate visualizations such as word clouds, trend graphs, topic clusters, and keyword-in-context displays[1]. With this information, one can pick up patterns not easily visible through close reading. In other words, this tool’s strength lies in correlation, since clicking on a term dynamically reshapes data visualizations, encouraging comparative analysis across a corpus.

 Keywords to Search
Unknown
Exploration
Science
Technology
discovery
Man
Journey 
Martian 
This led me to discover a few interesting points. On the trend graphs, it can be seen that, despite all books appearing under the category of “science fiction” in Project Gutenberg, only a brief mention of the words “technology” and “science”  are found in the books, these being Twenty Thousand Leagues Under the Seas: An Underwater Tour of the World by Verne (pg2488), A princess of Mars by Edgar Rice Burroughs, (pg62), and The call of Cthulhu by H. P. Lovecraft (pg68283). This, nonetheless, makes sense, when taking into account the historical context behind the three books. Edgar Rice Burroughs, most known for his adventure narratives such as Tarzan, brought A Princess of Mars to life in 1912, during a period of widespread “Mars mania,” A Princess of Mars drew heavily on contemporary astronomical theories about a dying Red Planet advanced by Giovanni Schiaparelli and Percival Lowell (CITATION). 
Lovecraft, on his side, wrote in the aftermath of World War I, amidst rapid scientific advancements, where he articulated a philosophy known as“cosmicism”: the idea that humanity is insignificant in an indifferent universe. These ideas were clearly reflected in  “The Call of Cthulhu” (1928). Drawing on contemporary developments in astronomy, evolutionary theory, and archaeology, Lovecraft crafted a story in which ancient extraterrestrial beings predate human civilizations. (CITATION)
Meanwhile, as part of his “Voyages Extraordinaires” series, Jules Verne’s Twenty Thousand Leagues Under the Sea: An Underwater Tour of the World (1870) reflects the belief that science and exploration could lead a path to the unknown. Published in the nineteenth century,  an era considered to be of technological innovation, particularly in naval engineering and marine biology, the novel fused contemporary fascination with submarines and oceanography. While Verne incorporated scientific details, he also interrogated the moral implications of progress.  Moreover, it could be argued the ocean functioned as a frontier, paralleling the period’s terrestrial colonial expansion with ideas of discovery leading to an uncharted, submerged world. 

STEP 3 IMAGE OF TRENDS ON VOYANT TOOLS

1.   "Cloning" this repository to Github Desktop

More intriguing similarities and differences could be found with the Bubblelines tool, in which the corpus is “represented as a horizontal line and divided into segments of equal length”.  This data allowed me to confirm my hypothesis that the mentions of “martians” would be aligned with the books of The War of the Worlds by H. G. Wells(pg36) and A Princess of Mars (pg62), given that both stories revolved around martian life. One of the greatest differences with one of the keywords I had chosen was “journey”, which was mostly present in The Wonderful Wizard of Oz by L. Frank Baum. L (pg55). 

Baum began his career in journalism before achieving success with children’s literature at the turn of the twentieth century. Published in 1900, The Wonderful Wizard of Oz emerged during a period of rapid American industrialization and cultural transformation. While European fairy tales by the Brothers Grimm and Hans Christian Andersen had gained popularity in Victorian England, the United States lacked a distinctly national fantasy tradition. Thus, Baum sought to create a modern American fairy tale. The novel reflects late nineteenth-century fascination with fantasy as both escape from and response to industrial modernity, which sets it closest to fall under the category of “fantasy” compared to the other books. 

One word, however, caught my attention. It is not a word that I could have thought to be associated with fantasy or science fiction, but it defined its presence for having one of the highest frequencies among all books: the word “man”. It is important to notice that, although books like The Wonderful Wizard of Oz  and The Call of Cthulhu have lower frequencies, this data led me to discover how male-dominated these books are. 


<img src="/assets/images/clonerepo1.png" style="zoom:40%;" />

There are several ways of finding the repository you want to clone. When you install Github Desktop for the first time it may ask you if you want to clone. It may also suggest that repo once you have selected `clone repository`. Another sure way of selecting the right place is to copy the URL of your repository where you forked the `minimal-mistakes`template. You can paste that URL in the URL tab and click clone. 

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