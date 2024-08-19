---
layout: page
title: Schedule
permalink: /schedule/
included: true
order: 2
---

**General pattern**

Each meeting, **we will begin at 9 to allow for childcare, commuting, and other arrangements**. You are welcome to arrive at 8.30 as per the official schedule, but I will not begin until 9. Consequently, I will also not be stopping for the remainder of the scheduled time. Feel free to bring croissants, coffee, toast, etc. Scrambled eggs are to be avoided as they are messy.

In certain weeks, a designated person will take us through their engagement with a particular Programming Historian tutorial, as indicated below. There will be readings to support this engagement; I will discuss these individually with you once we divy up the work. Some will highlight uses of the approach, or perhaps issues with the approach, or could've usefully been improved by the approach... or... or... or. I will expect you to also clearly articulate connections in other research you've done, read, or courses you're taking/have taken (this alone is an important habit to cultivate.) You can also bring digital history projects in the wild into the discussion.

(**nb** Even if it's not your week to present, it will be a richer experience if you've given the tutorial a shot as well.)

The remaining time will run along the lines of a mini unconference. That is, I expect you to have a sense before class of things you want to work on/discuss/collaborate on. As [thatcamp.org](https://thatcamp.org) says:

> at an unconference, the program isn’t set beforehand: it’s created on the first day with the help of all the participants rather than beforehand by a program committee. Second, at an unconference, there are no presentations — all participants in an unconference are expected to talk and work with fellow participants in every session. An unconference is to a conference what a seminar is to a lecture; going to an unconference is like being a member of an improv troupe whereas going to a conference is (mostly) like being a member of an audience.

I've had far too many seminars that felt like dreadful dreadful conferences. So, let's give this a try. One thing that I think I would like you to discuss every session: how does this particular tutorial move us closer to the final project goal? What could we do with this? How can we open this thing up even mmore?

These sessions will be opportunities for the more techy to help the less, for the more theoretically inclined to help the more methodologically inclined. I will say this though:

> doing embodies theories of knowing and how you do things reveals what you know. So know what you're doing.

The sequence of lessons we will go through mirrors the progression of a digital history research project - setting up your environment/project/workflow; data capture; data munging; analysis; visualizations; public consumption.

## Meeting 1: Getting Started

**To install:**

[Obsidian](https://obsidian.md) OR [Tangent](https://www.tangentnotes.com/); if in doubt, the learning curve for Tangent is much gentler. If this is your first exposure to these kinds of note-taking applications, I'd suggest Tangent

[Zotero](https://zotero.org) for research management (bibliograpies, citations, pdf annotations, and note making)

[Tropy](https://tropy.org) for research management of photographic materials (whether your own photos or other kinds of things)

We will spend a bit of time setting up your own personal research management environment and talking about this in general; this isn't so much a part of 'digital history' as 'strategies to keep you sane.'

> Ask yourself: has your research to date been _sustainable_ or _reproducible_ or _replicable_? Why should historians care about this sort of thing?

**To do:**

- Some command line shennanigans: 

	[Terminus](https://web.mit.edu/mprat/Public/web/Terminus/Web/main.html); [Command Line Murders](https://github.com/veltman/clmystery).

	Simpkin, Sarah. ‘Getting Started with Markdown’. Programming Historian, Nov. 2015. programminghistorian.org, [https://programminghistorian.org/en/lessons/getting-started-with-markdown](https://programminghistorian.org/en/lessons/getting-started-with-markdown).

	Tenen, Dennis, and Grant Wythoff. ‘Sustainable Authorship in Plain Text Using Pandoc and Markdown’. Programming Historian, Mar. 2014. programminghistorian.org, https://programminghistorian.org/en/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown.

Then we'll divy out some of the other Programming Historian tutorials in the subsequent weeks.

**To mull:**

Baker, James. ‘Preserving Your Research Data’. Programming Historian, Apr. 2014. programminghistorian.org, https://programminghistorian.org/en/lessons/preserving-your-research-data.

Heppler, Jason A. ‘How I Use Obsidian | Jason A. Heppler’. Jason Heppler Weblog, July 2024. jasonheppler.org, https://jasonheppler.org.


## Meeting 2: Digital History in the Wild

**Before coming to class read:**

Catherine D’Ignazio and Lauren F. Klein, “What Gets Counted Counts” and “The Numbers Don’t Speak for Themselves,” Data Feminism (2020), [https://data-feminism.mitpress.mit.edu/](https://data-feminism.mitpress.mit.edu/).

Ryan Cordell, ‘Q i-jtb the Raven’: Taking Dirty OCR Seriously' [_Book History_ 20 (2017), 188-225](https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/1ortgfo/cdi_proquest_journals_2008107951) (see also https://ryancordell.org/research/qijtb-the-raven/)

Then, select two pieces from [_Current Research in Digital History_](https://crdh.rrchnm.org/). Read the piece. See if you can find the underlying data. Does the project make the data available? Is there a public facing website for the larger project? Is there an intersection with Public History? Be prepared to talk about how the underlying data for these projects are presented, discussed, curated, and explored. List any tools/techniques that are new to you. What can you find out about _how_ to use such a tool? Part of the challenge of _doing_ digital history lies in what might be called 'Dependency Hell' - to use this, you need _that_; to do _that_ you need _this other thing_... and so on. But we can start to map this out...

- To do:

Take a look at your assigned Programming Historian tutorial. Pay attention to the requirements, and try to work out what assumptions the tutorial's author has made about your previous experience and what you need to know to be successful with the tutorial. What are the known unknowns (as it were) for the method?


## Meeting 3. Quick Static Websites 


We'll build a website using [Pelican](https://getpelican.com/#quickstart), which is a python package that will read a folder of text files (in the markdown format), pass them through a template, and spit out the necessary html files that make a website. We'll then put these files online using Github Pages. (See my notes on using Obsidian - or other noteaking app using wikilinks - to write the markdown [here](https://electricarchaeology.ca/2024/07/25/obsidian-for-writing-pelican-for-publishing/)).

**Going further** Put your research photos online using a static website via Tropy [(instructions here)](https://electricarchaeology.ca/2024/07/25/make-your-tropy-collection-and-annotations-available-with-canopy/)

Please read the following tutorials about building static websites, especially the _why_ of it all. I'm not a fan of Jekyll - I find it frustrating to use - but I want you to know these things. Don't worry about trying to put together a Jekyll powered site unless you really want to.

	Visconti, Amanda. ‘Building a Static Website with Jekyll and GitHub Pages’. Programming Historian, Apr. 2016. programminghistorian.org, https://programminghistorian.org/en/lessons/building-static-sites-with-jekyll-github-pages.

	Visconti, Amanda, et al. ‘Running a Collaborative Research Website and Blog with Jekyll and GitHub’. Programming Historian, Nov. 2020. programminghistorian.org, https://programminghistorian.org/en/lessons/collaborative-blog-with-jekyll-github.


## Meeting 4. Networks

- Read:

Ahnert, Ruth, Sebastian E. Ahnert, Catherine Nicole Coleman, and Scott B. Weingart. 2020. The Network Turn: Changing Perspectives in the Humanities. Cambridge: Cambridge University Press. https://doi.org/10.1017/9781108866804. (Our library, direct link: https://www-cambridge-org.proxy.library.carleton.ca/core/services/aop-cambridge-core/content/view/CC38F2EA9F51A6D1AFCB7E005218BBE5/9781108791908AR.pdf/the-network-turn.pdf). This is a short work, read the intro and part 1, dip into anything else that strikes your fancy.

For examples of network analysis in the wild, [this issue of the Journal of Historical Network Research](https://jhnr.uni.lu/index.php/jhnr/issue/view/8) is great - see in particular [Ruffini's conclusion](https://jhnr.uni.lu/index.php/jhnr/article/view/82/44) to the issue, which addresses the 'so what' and the 'we knew this already' and 'what if we're wrong'. **This is important**. On a similar note, see Lincoln 2015 on 'confabulation in the humanities' [here](https://matthewlincoln.net/2015/03/21/confabulation-in-the-humanities.html).

- To do: 

A handy tool for quick network visualizations: [https://networknavigator.jrladd.com/](https://networknavigator.jrladd.com/). Here is a [dataset](http://www.themacroscope.org/1.0/datafiles/source-texas-correspondence.txt) of the index of correspondence for the Republic of Texas; knowing nothing else about the Republic of Texas, how might visualizing this correspondence network provoke new insights or questions?

	Düring, Marten. ‘From Hermeneutics to Data to Networks: Data Extraction and Network Visualization of Historical Sources’. Programming Historian, Feb. 2015. programminghistorian.org, https://programminghistorian.org/en/lessons/creating-network-diagrams-from-historical-sources.

	Ladd, John R., et al. ‘Exploring and Analyzing Network Data with Python’. Programming Historian, Aug. 2017. programminghistorian.org, https://programminghistorian.org/en/lessons/exploring-and-analyzing-network-data-with-python.

	Brey, Alex. ‘Temporal Network Analysis with R’. Programming Historian, Nov. 2018. programminghistorian.org, https://programminghistorian.org/en/lessons/temporal-network-analysis-with-r. (You can install RStudio on your machine to run R, or you can change the runtime for Google Colab from Python to R like [so](https://archive.ph/Eqe57).)


## Meeting 5. Topic Models and Text Analysis

I love the Data Sitters Club. Read about [their misadventures with topic modeling here](https://datasittersclub.github.io/site/dsc20.html).

Here's a Google Notebook I made that uses something called 'paddleOCR' to identify text in an image and then OCR it [link](https://colab.research.google.com/drive/1TYhLsOYW4nVfX5NP8Fi-O1QU0_ndj_ik). There are many other options. The lesson below suggests another approach, and then uses Dariah Topics Explorer.

	Mähr, Moritz. ‘Working with Batches of PDF Files’. Programming Historian, Jan. 2020. programminghistorian.org, https://programminghistorian.org/en/lessons/working-with-batches-of-pdf-files.

If your documents are in a folder of text files, give [this a try instead](https://senderle.github.io/topic-modeling-tool/documentation/2017/01/06/quickstart.html). The topic modeling tool uses MALLET under the hood (and you can learn more about how _that_ works and why, [here](https://programminghistorian.org/en/lessons/topic-modeling-and-mallet).)

Let's also play with [Voyant](https://voyant-tools.org). 

## Meeting 6. examining images at scale

	Strien, Daniel van, et al. ‘Computer Vision for the Humanities: An Introduction to Deep Learning for Image Classification (Part 1)’. Programming Historian, Aug. 2022. programminghistorian.org, https://programminghistorian.org/en/lessons/computer-vision-deep-learning-pt1.

	Strien, Daniel van, et al. ‘Computer Vision for the Humanities: An Introduction to Deep Learning for Image Classification (Part 2)’. Programming Historian, Aug. 2022. programminghistorian.org, https://programminghistorian.org/en/lessons/computer-vision-deep-learning-pt2.

## Meeting 7. Research Management: Tropy

## Meeting 8. Research Management: Reference Managers and Personal Knowledge Management Apps

What if we made our research data itself available? See [what this could look like here](https://datapages.github.io/datapage/) and here's the template for [doing this for ourselves](https://github.com/datapages/datapage). Other options exist (including things like [datasette.io](https://datasette.io)). And it's over 10 years old now, but Caleb McDaniel's [Open Notebook History](http://wcaleb.org/blog/open-notebook-history) still is posing questions that historians largely avoid. Let's talk about this.

## Meeting 9. Mallory's papers: scraping & apis

## Meeting 10. Mallory's papers: LLMs for NLP

Graham, Shawn et al. Investigating antiquities trafficking with generative pre-trained transformer (GPT)-3 enabled knowledge graphs: A case study. Open Research Europe. 2023 3:100. [link](https://traffickingculture.org/app/uploads/2023/06/Graham-Yates-El-Roby-2023.pdf)

	Brousseau, Chantal. ‘Interrogating a National Narrative with GPT-2’. Programming Historian, Oct. 2022. programminghistorian.org, https://programminghistorian.org/en/lessons/interrogating-national-narrative-gpt


## Meeting 11. Mallory's papers: knowledge graphs, maybe LOD

## Meeting 12. Wrapping it all up




