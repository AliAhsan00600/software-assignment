# software-assignment

TOPIC:


OWNERSHIP AT LARGE

(OPEN PROBLEMS AND CHALLENGES IN OWNERSHIP MANAGEMENT)


AUTHERS:   JohnAhlgren,MariaEugeniaBerezin,KingaBojarczuk,ElenaDulskyte,InnaDvortsova,Johann George,NatalijaGucevska,MarkHarman,ShanHe,RalfLämmel,ErikMeijer,SilviaSapora,and JustinSpahr-Summers* 


INTRODUCTION:
                    Ownership refer to right of processing something, Management refers to the process of dealing with  or controlling things or people.
any organization is going to be BEST if it was manage in a effective way management is consider to a key to make any organization the best .suppose there is a organization but there is no one to manage this organization  what happen then? the organization not work properly and then it will going to in a LOSS.
Ownership management is all about sound finding accountable owners for these ssets this is very important for many pressing such as integrity, privacy and security depend on well define ownership  so that secure responsibility when it comes to maintenance count view incident response and so on .
the term assets refers to any sort of entity that is a part of a system in a company example of assets could be source code files or table in a data warehouse such as hive table or it could be software configurations it is not enough to find alone and just once for these assets the owners change of a time did you come to new yoke reorganization people leaving changing teams and so on so it just become an ownership health program really you don’t want to an own that you want the best possible on at a given time and recommendation system basically is an automatic way proposes the most suitable owner in a paper we talk about an honesty style recommendation system and it indeed has lots of logs for different assets we extract those logs  and we turn  them into features and features vectors we also use these logs to create labeled data on assets and illness we use this data to train our models  we even input data on assets and illness we use this data to train our models we even input all of the assets and feature vectors to make predictions we even tired those predictions in your explainable recommendation now is important for recommendation to be explainable as the owner need to understand .
challenges and problems in ownership management

1 = ASSETS SUBSCALLING:
=an assets can be split istinto subclassess.
=some asssets can be easily assigned using heuristics.

2 = TEAM LEVEL OWNERSHIP:
=aggregate  employee level  interaction at the team level.
=rely on  team membership.

3 = OWNERSHIP DECAY:
=hard -coded owners
=revelent with latest diff.
=employee to team mapping.

4 = RANKING OWNER CANDIDATE :
=model perfomance based on rank 1 accuracy.
=performance compared with random owner as base line.

5 = WHOLE PART ASSETS RELATIONSHIOP:

6 = MONOTONIC OWNERSHIP FEATURES :
=features capture strength of ownership signals.



In this paper, when we refer to (software) ‘asset’ we include entities as diverse as source code files, tables in the data ware house, and soft ware configurations. When were for to the ‘owner’ of an asset, we mean this term in a broad sense :a set of people who take responsibility for the asset. The set can be singleton, but may also be a group or sub organization. The  owner can also vary depending on purpose – such as code review versus incident response. If the set was ever empty, the asset is un owned. Standard processes, e.g., based on  escalation, are typically in place to rule out unwonted assets, as they would clearly because for concern. A more nuanced question is the one of ‘ownership health’ ,i.e., whether each asset is attributed to the ‘most suitable’ owner .Who is the most suitable owner of a given asset changes overtime ,e.g., due to reorganization  and individual function changes. Ownership health give rises to interesting research problems and challenges.

RESULT:

managing software assets ownership in any organization is important, many pressing industrial concern such as security, reliability, and integrity depend on well define ownership ,ownership management requires wide verity of topics including program comprehensive and more genially software engineering, programming language and machine learning.
there is many problems and challenges faced by ownership management including heterogeneity of owned assets, dependency alertness, workflow and organizational aspect, understandable recommendation.






JTeC: ALarge Collection of Java Test Classes for Test Code Analysis and Processing

Authors:

* FedericoCorò∗ SapienzaUniversityofRome Roma,Italy federico.coro@uniroma1.it
* RobertoVerdecchia∗ VrijeUniversiteitAmsterdam Amsterdam,TheNetherlands roberto.verdecchia@gssi.it
*EmilioCruciani∗Inria,I3SLab,UCA,CNRS SophiaAntipolis,France emilio.cruciani@inria.fr
* BrenoMiranda† FederalUniversityofPernambuco Recife,Brazil bafm@cin.ufpe.br
* AntoniaBertolinoConsiglioNazionaledelleRicerchePisa,Italyantonia.bertolino@isti.cnr.it


DATE: October 5–6, 2020, Seoul, Republic of Korea

Introduction:

Test automation has been actively pursued since the 90’s [17] as a solution to reduce the high costs of software testing and improve product quality [12]. A recent study by Zion Market Research [18] estimates that the software test automation market will grow from the 16 Billion Dollar sof 2016 upto 55 Billion Dollars bend of 2022.However, this insurgence of test automation also comes with challenges and risks, which several researchers have been prompt to identify and face.However, this insurgence of test automation also comes with challenges and risks, which several researcher shave been prompt to identify and face. All the above research efforts demand availability of a large data set of test code, to which the proposed methods and tools can be applied.






ABSTRACT:

There cent push towards test automation and test-driven development continues to scale up the dimensions of test code that needs to be maintained, analyzed, and processed side-by-side with production code. As a consequence, on the one side egression testing techniques, e.g., for test suite prioritization or test case selection.

CCS CONCEPTS •

Software and its engineering → Software testing and debugging.

KEYWORDS:  GitHub, Java, LargeScale, Software Testing, Test Suite

ACM Reference Format:

METHODOLOGY:

In this section we report the method logy we use together to the dada o four data set. The process, illustrated in Figure1,consistsof six main steps:(i) GitHub repository filtering,(ii) Java repository identification, (iii) test classes identification, (iv) repository selection,(v) local storage of test classes, and (vi) preliminary quality filtering.
Step1: GitHub repository filtering. The first step of our process consists of indexing the public GitHub repositories, and is carried out in order to execute efficiently the subsequent phases of our process. In this step we first retrieve the name of the public repositories and the user name of their creators.
Step2: Java repository identification. Once obtained a local copy of the indexed repositories mapped to their programming languages, we can effort less ly retrieve the URL soft here postures developed in a specific language.
Beyond our own motivation, we consider JTeC could be used to the benefits of researchers in several areas, including: • Static analysis: static analysis of test code has been applied for many purposes, including, for example, the identification of test smells 


CONCLUSIONS AND FUTURE WORK 

We have presented the JTeC data set that makes ready available to the community of software testing researcher silage collection of Java test classes useful for several potential purposes related to test code analysis and processing. Our aim goes beyond the current version of the dataset: we strive towards the establishment of a continuously updated data set, collecting together rain single source the test code belonging to the vast majority of test cases publicly.




2k18 – csm -11  Ali ahsan

Log Chunks: A Data Set for Build Log Analysis

AUTHORS:
CarolinE . Brandt, Anni bale Panichella, Andy Zaidman, Moritz Beller
DATE: MSR ’20, October 5–6, 2020, Seoul, Republic of Korea

ABSTRACT: 
Build logs are textual by-products that a software build process creates, often as part of its Continuous Integration (CI) pipeline. Build logs are paramount source of information for developers when debugging into and understanding a build developers who caused the original build failure. The width and depth of the Log Chunks data set are intended to make it the default benchmark for automated build log analysis techniques.failure. Recently, attempt stop partly automate this time-consuming, purely manual activity have come up, such as rule-or information-retrieval-based techniques. Log Chunks contain seminally labeled log part (chunk) describing why the build failed. We externally validated the data set with the chunk.

1 INTRODUCTION :

Continuous Integration (CI) has become a common practice in softwareengineering[10]. Manys of software projects use CI[2,10,17] to detect bug searly [8,18], improve developer productivity[10,13] and communication[7].CI builds produce logs which are port results of various sub-steps within the build. For Log Chunks, we queried GH Torrent from 2018-04-01 for the three most popular repositories of each of the 30 most popular languages to cover abroad range of development languages. Among there sulting repositorie sare, for example, Microsoft/Type Script, git/git and jwilm/alacrity
Log Sampling. Travis CI builds comprise number of jobs that actualize a build process in different environments. Hence, the out come from different jobs might be different. For each building Log Chunks , we download the logo fthe first job that has the same state as the overall build. We inspected the collected build log sanddis carded logs from three repositories. One had only one failed build, two others had empty build logon Travis CI. In total, we collected 797 logs from 80 repositories spanning 29 languages.

importance

In this paper, we introduce Log Chunks, across-validate dataset encompassing 797 build logs from 80 projects using Travis CI. For each log, we annotated the log chunk describing why the build fail eland provided keyword sad eveloper would use to search for the log chunks well as categorization of the log chunks according to the informant within the log. Log Chunks advances the research fie l do build log analysis by introducing benchmark rigorously examine research contributions[15]and opening various research possibilities that previously required tedious manual classification.


