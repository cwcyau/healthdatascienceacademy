# HDR003 Experimental methods for health data science

## Basic Information

Code: HDR003

Title: Experimental methods for health data science

Leader: -

Duration: 4 days

## Description

### Overview 

Experimental methods are concerned with the approach to designing an experiment to support or refute a hypothesis. An appropriate experimental design will therefore allow an experiment to be carried out and answer the question of interest. In contrast the data collected but an unsuitable experimental design can confuse analysis and introduce error into results. However, experimental methods can be an alien concept to many 

This course aims to provide a rapid introduction to important experimental methods and its applications in health data science. The delivery will centred on a series of real-world case studies across a range of health areas to provide participants with a breadth of knowledge on how experimental methods are used in practice. Activities will support experimentation with example problems to understand the need for formal experimental design approaches. 

It is suitable for those with (post-)doctoral level in the mathematical or computational sciences. No prior health data science experience is required. 

### Intended Learning Outcomes

### Teaching methods

## Pre-requisites

## Example Timetable

| Day | AM | PM |
| --- | -- | -- | 
| 1 | Arrival | Welcome & Introductions |
| 2 | What is the ideal experiment? | Practical: Simulating a randomised control trial |
| 3 | Nature's experiment | Practical: Mendelian randomisation |
| 4 | What you see is not what you get? | Practical: Adjustments for observation bias |
| 5 | Group Exercise | Return home |

## Course Outline 

### Day 1: Introduction

This first afternoon will give a brief overview of key concepts in: 

- The theory-prediction-intervention cycle; 
- the hierarchy of medical evidence; 
- analysis and interpretation; 
- experimenter bias; 
- association vs. causation; 
- biological mechanism; 
- measurement under experimental vs. observational conditions; 
- internal vs. external validity; 
- transportability

The purpose is to get participants up to speed (from whatever discipline they come from) on the key topics in **the scientific method in health sciences** and the motivation for this course.

There will be a short group exercise to design an experiment based on a breast screening scenario.

*Possible guest speaker(s):*

- [Marta Milo, AstraZeneca](https://scholar.google.co.uk/citations?hl=en&user=K3Y2Mu8AAAAJ&view_op=list_works&sortby=pubdate) ("How do we do experiments in drug discovery?")
- [Peter Bannister, Ada Health/University of Birmingham](https://www.linkedin.com/in/prbannister?originalSubdomain=uk) ("How do we assess the effectiveness of digital clinical support systems?")
- [Richard Riley, University of Birmingham](https://scholar.google.co.uk/citations?user=didzOp8AAAAJ&hl=en) 
- [Christopher Yau, University of Oxford](https://www.bdi.ox.ac.uk/Team/christoper-yau) ("How should we go about using Artificial Intelligence in Medicine?")

### Day 2: What is the ideal experiment? 

The second day will introduce the *randomised control trial* (RCT):

- Causal interpretation of RCTs: confounding, mediation, latent causes, graphical models; 
- pre-registration; 
- blinding; 
- double-blinding; 
- complex RCTs: wedges, steps, crossover, multi-step, N-of-1, adaptive, Bayesian

The morning will introduce the basic theory and methods and, in the afternoon, participants will be asked to work in groups to produce a simulation of an RCT under different scenarios. Examples might include showing the optimality of a stepped wedge design or the compromises of using clustered RCTs. There will be particular interest in groups simulating scenarios that can be inspired from their own areas of science.

*Possible guest speaker(s):*

- [David Wong, University of Manchester](https://personalpages.manchester.ac.uk/staff/david.wong/) ("How to put together an RCT in practice")
- [Sarah Elison-Davies, Breaking Free Online](https://www.breakingfreegroup.com/research) ("How are we using RCTs to prove the effectiveness of digital interventions?")
- [Karla Hemming, University of Birmingham](https://www.birmingham.ac.uk/staff/profiles/applied-health/hemming-karla.aspx) ("The stepped wedege trial")
- [Elin Haf-Davis, Aparito Health](http://www.elinhafdavies.co.uk/)  ("How are we using RCTs to prove the effectiveness of digital interventions?")

### Day 3: Nature's experiment

The third day will introduce the concept of *Mendelian Randomisation* (MR):

- basics of genetics: single nucleotide polymorphisms, linkage disequilibrium, heritability;
- instrument variables in causal inference;
- causal interpretation of genetic association studies.

The morning will introduce the basic theory and methods and, in the afternoon, participants will be asked to work in groups to produce a simulation of MR under different scenarios within a genetic association study (including those which break the MR assumptions) to understand the utility of genetic variants as instrumental variables. 

*Possible guest speaker(s):*

- [Alex Cornish, Benevolent AI](https://scholar.google.com/citations?hl=en&user=viBK5DMAAAAJ&view_op=list_works&sortby=pubdate) ("How do we use Mendelian Randomisation to tell us about what causes human diseases")
- [Derrick Bennett, University of Oxford](https://www.ndph.ox.ac.uk/team/derrick-bennett) ("How do we use Mendelian Randomisation to understand the health of a population?")

### Day 4: What you see is not what you get?

The fourth day will introduce the concept of *observational studies*:

- rationale for using observational data;
- the advantages and pitfalls;
- the risk of bias and possible solutions;

The morning will introduce the basic theory and methods and, in the afternoon, participants will be asked to work in groups to compare the performance of a classification algorithm train and applied to data acquired from a simulation of an RCT and an observational data set. Groups will be asked to consider common challenges when using health data such as structured missingness, diagnostic delay, misdiagnosis, etc.

*Possible guest speaker(s):*

- [Max Little, University of Birmingham](http://www.maxlittle.net/home/index.php) ("Remote monitoring in neurodegenerative diseases")
- [Robin Evans, University of Oxford](https://www.stats.ox.ac.uk/~evans/) ("Causal methods for observational data")
- [Liz Sapey, University of Birmingham](https://www.birmingham.ac.uk/staff/profiles/inflammation-ageing/sapey-elizabeth.aspx) ("How do we get the data to do observational studies?")

### Day 5: Group Exercise

The final morning will involve a group exercise where participants are given a scenario and asked to design an experiment. Each group will present findings and the course will end with a keynote speaker.

## Related courses

## Recommended Reading


**Block 2: Experiments in health research** 

Medical: retrospective vs. prospective; interventional vs. observational; case-control vs. cohort; longitudinal vs. cross-sectional; protocol; inclusion/exclusion; recruitment; attrition; compliance and adherence; follow-up. Behavioural: sampling strategies; self-report vs. expert assessment; manual vs. automated coding

**Block 4: Experimental design** 

Protocol design and implementation; comparison under constraints and unit allocation; combinatorial block designs: BIBD, SBIBD, Latin squares, resolvable designs
