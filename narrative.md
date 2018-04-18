# 2018 / Annual report / Narrative / C. Titus Brown / Moore DDD Investigator

## Progress

*Describe your project's progress in the last year. Please reference your initial project objectives when possible.*

Award purpose:

>In support of demonstrating the high level of scientific impact
>that data scientists deliver through their focus on
>interdisciplinary data-driven research; funds from this award will
>be used to better understand gene function in non-model organisms
>through the development of new workflows and better data sharing
>technology for large-scale data analysis.

Essentially, our project is to explore discovery and semi-automated
analyses of sequencing data, with the goal of eventually supporting
large scale mining of correlations across All the Data. The challenge
is that these are all underdeveloped technologies in non-model
organism genomics.

The third year of my award saw substantial progress towards
implementing a strategy towards these ends, and developing specific
foundational technologies and software. Some updates from last year:

* the transcriptomics team working on reanalysis of 700 transcriptomes
  (MMETSP project, Lisa Cohen and Harriet Alexander) is nearing
  publication.  The associated technology developed by Camille Scott,
  dammit and shmlast, has been adopted by many (est ~500) users.
  
* we received separate funding from the DHS to pursue workflows in
  metagenomics, which has allowed me to support Phil Brooks on that
  project instaed of Moore money.
  
* our distributed/scalability tiger team (Luiz Irber) has been
  building out a massively scalable distributed architecture that
  closely resembles a botnet.  This has proceeded well, with acquisition
  of large scale data sets, contact with other similar projects, and
  integration of some of our software into KBase.
  
* our core software development efforts continue, with Daniel Standage
  leading khmer development. Daniel has also developed a piece of
  software called Kevlar for reference independent variant calling that
  is based on khmer.
  
* Camille Scott has implemented a streaming assembler in a new project
  called boink (a Calvin and Hobbes reference). This is still far from
  publication but is a radically different approach to large scale
  data analysis in this field.

* while doing all of this, we continue to explore the landscape of
  tools and resources around notions of openness, repeatability,
  decentralization and distribution, and community engagement.  In
  addition to my continuing social media postings, an analysis of
  challenges in doing large scale data reanalysis in a small lab
  will be submitted along with the primary MMETSP reanalysis
  paper in the next month.

* an important component of all our work is our teaching and training
  effort, aimed at building a local community of practice around
  data-driven discovery while engaging with the global community being
  nucleated by the Data Science Environments and Data Carpentry.
  
  Towards this end, we ran a 150-person 5 week Summer Institute that
  included Carpentry instructor training, materials development,
  our ongoing two week ANGUS workshop, and a series of seven one-week
  workshops on various topics.
  
  We also brought in 4 underrepresented minority undergraduate students to
  do a summer internship; this went quite well.  We are exploring how to
  do this again, but it was very expensive.
  
As always, it's hard to predict where we will end up but I'm enjoying
the ride, and in the meantime we are producing useful software
products and doing interesting analyses.

## Awareness and recognition

*Describe evidence of awareness/recognition of you, your projects, and/or your lab members.*

Since my last report, I have now served as an external letter writer
for two tenure cases at other universities, which I think is fairly
early for my career stage.  I am also increasingly in demand for grant
review panels and keynote talks - I served on two NIH grant panels, a
Chan-Zuckerberg panel, two Canadian grant panels, and a few others.  I
also gave the JGI User Meeting Closing Keynote (~300 attendees) and
the CSUPERB (Cal State Biotechnology meetup) data science session
keynote this year. I reviewed the Czech national infrastructure ELIXIR
grant as well. And, finally, I was invited to speak at the National
Academies as part of a BioWatch (bioterror detection) panel.

## Expenditures

The major variances were on supplies (which went to supporting our
training) and our MSU subcontract (which was all paid in the first
year, and not spread out).

## Help requested

This is actually the same as last year... Help!

### Compute infrastructure

There is a general confusion and lack of clarity around the
computational infrastructure needs of Data Driven Discovery, and where
and how to meet them.  This includes just-in-time resources for
training, long term storage of large datasets, "scale out" technology
options, good-enough practice in making use of the options, and
funding/support for large scale compute and storage.  (This is also
alluded to in Casey Greene's report.)  

We are working on a local (UC Davis School of Vet Med) solution to
container hosting, and also starting to interact more closely with
NSF's JetStream, as two possible solutions for our lab.

But, more generally, I don't know what a sustainable option is here.
It seems like a good opportunity for some brainstorming.

### Learning about deep learning

I need to know more about deep learning, and gain some hands on
experience.  More, I would like to be able to engage closely with
experts in order to figure out what will and won't work. People in my
lab are also interested in this. Where do we go?
