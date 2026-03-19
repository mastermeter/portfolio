# Portfolio

The portfolio has the objective to show what are our contribution to the project and why our chief should "keep" us. It will be structured around differents points :

- Computer science engineer
    - Analyse a complexe informatic problem
    - Design a theoretical, modeled solution
    - Implementing a modeled theoretical approach
    - Evaluate an informatic system
    
- Data engineer
    - Leveraging heterogeneous and multimodal datasets
    - Orchestrating a process and a data processing infrastructure
    - Applying computer engineering skills to the data domain

-  Professionalism (soft skills)
    - Communicate clearly and efficiently
    - Adopting a professional and facilitative approach to the situations encountered
    - To argue one's opinions and choices during decision-making and strategic processes
    - To critique the process of a production in a self-reflective manner

For each point, Additionnal content will be add during the project concerning my contributions.

## Analyser un problème informatique complexe

## Concevoir une solution théorique modélisée

My first three weeks of this project get my focus of every point concerning 3D modeling. It could be considered not as *computer science* engineer and I unerstand the point but the reflexion around my production has some similarities.

I decided to take this role because I have experiences on 3D modeling and so I can spare time discovering applications.

My first productions that can be found here [Support Sketch](https://github.com/Toys-R-Us-Rex/Duckify/commit/b0e30719beff070b21331087e49fd69d1de168e8). The objectives of these sketches were :

- To give me time to discover again Inventor. Take the habit of the different available tools.
- To show to the team how I would imagine a duck support in the concept.
- Create some complexe shape in the sence they require some deeper knowledge to design them.

The next step is to design the pen-related pieces. It involves a substitution of a classic pen in two formats because at this points we choosed two different models of pen. Theses substitutions have the purpose to replace pen to avoid some critical incident. The next design is a support for pen, its objective is to provide a stable and viable piece so the pen can have a fixed position.

The commit that added the files and their structure is here : [Pen-related model](https://github.com/Toys-R-Us-Rex/Duckify/commit/343e6cbbd831bb5ca98af4b043ff2c8a33d482d6)

In parallel of my common thread. My team asked me to produce some specific piece for test purpose. The idea was to print a piece with differente slopes and orientation for testing drawing on these slopes. As a basic shape, I produced a sort of truncated pyramid with non-uniform side. All the related documentation were provided in [The test slope](https://github.com/Toys-R-Us-Rex/Duckify/commit/99d94a4e07718d70484d219bf683ba410575c68d).

For presentation purpose, I took the initiative to reproduce the environment of the robot in an assembly in Inventor. It also has the objective to discuss with the team about the disposition and design of support to place element around the robot. This initiative involved the production of :

- A [metal plate](https://github.com/Toys-R-Us-Rex/Duckify/commit/60afaa97607ae36a96b1a6e3f52b57007e52b891) that represent the large plate under the robot
- A [support plate](https://github.com/Toys-R-Us-Rex/Duckify/commit/fecb2f54f8cad5a4a98d4de9e4413720ea7972cb) that was design around the idea that the piece will fit hole in the support like puzzle pieces

After discussion with expert, I change the approach of interlocking support. The system that will maintain the pieces together will be pins that are commanded directly to an expert.

And so I redesign the supports that have the purpose of being in wood (involving laser cutting) and also being 2 different piece, one that will contain the duck support and the other all the pen supports.

- [The redesign of wooden support](https://github.com/Toys-R-Us-Rex/Duckify/commit/1009e153e927d299d40bac70b55392cf1c785faa) : As I said, two pieces designed to be fit together with pins' holes.

The question of positionning the support relatively to themself and the robot was a subject of discussion with the robot team and the conclusion was that fixed position was not an important point as calibrating the robot to give the relative position of the pieces was enough. This conclusion implies that I design another version of the wooden support, more basic. They are the [first wooden support cut](https://github.com/Toys-R-Us-Rex/Duckify/commit/2744d063d57a45c51c4c008668a7f58b87bfd6de) that was sent to an expert (This kind of discussion will be shown in another part)

In the other hand, I printed the final version of [a support to elevate the duck](https://github.com/Toys-R-Us-Rex/Duckify/commit/87fb7a223b44f528bbda29b1b75b226d3845930e) so the robot could have more space and angle to paint the duck. A specific element that can be seen in the picture of the commit is some specific point that are waypoints used for calibration by the robot team.

During our tests we discover that the pen support I printed had some friction issue with the pen and sometimes the support move with the pen. I tried two differents fixed : the first was to reduce the surface of contact with the pen but it happened that it was not a good idea because by removing this surface we remove the rigidity of the support and it can more block the pen. The second was to remove the slope and to only use horizontal and vertical shape. Every document relative to this issue are in this PR : [Fix of friction](https://github.com/Toys-R-Us-Rex/Duckify/pull/75)

## Implémenter une approche théorique modélisée

My first task as a new member of the robot team is to implement a program to have our robot to manipilaute different pens and be able to change it if needed : [the first version](https://github.com/Toys-R-Us-Rex/ur3e-control/commit/9df83da26b9467acfad9b6ffba3667ac34f35a2b#diff-19813992aad65f851cae5517226b46faafc23bc4bad4bb8edd93affceb40f1e5) will be adjusted to deal with the global strucutre of the robot program structure.

## Evaluer un système informatique

## Valoriser des ensembles de données hétérogènes et multimodales

Considering I deal with specific files format I decided to structre my commit and my production in a specific way that you can find in the [25th pull request](https://github.com/Toys-R-Us-Rex/Duckify/pull/25)

Concerning the duck support, the robot team asked me to provide specific files concerning the disposition of the waypoint on the duck. So I give them [a plan of the piece and a small json files](https://github.com/Toys-R-Us-Rex/Duckify/commit/bbf75ee5c383c9d5a7572445edfacafa14d3a301)

A problem appeared for the tracing team and robot team concerning the axis and orientation of model I give. I haven't personnaly taken care of this point because I couldn't imagine the orientaion of the design I did could have any importance. I was wrong and after discussions with the concerned group I provide [oriented pieces](https://github.com/Toys-R-Us-Rex/Duckify/commit/02be7384ea0f5d1c3b25ee3d7182638ddd4411b0) with the choosen orientation for the duck and the [duck support](https://github.com/Toys-R-Us-Rex/Duckify/commit/60b868903d585489b0eca09b0ea36b5205b98de7)

## Orchestrer un processus et une infrastructure de traitement de données

## Appliquer les compétences de l’ingénierie en informatique au domaine des données

## Communiquer clairement et efficacement

After many daily meetings, I take some time to talk to the team about their delay. The problem is not the loss of time we have but more about the discipline. It was during [the 12.03 meeting](https://github.com/Toys-R-Us-Rex/Duckify/commit/ac4eab87cd10c1e3047467b2d744239b19e6f6f3)

During a meeting I tell my team that I am free to move to another teams to give help if needed as my role as 3D Designer is more or less done [Meeting minute](https://github.com/Toys-R-Us-Rex/Duckify/blob/main/docs/meetings/daily/2026-03-05.typ)

## Adopter une posture professionnelle facilitante face aux situations rencontrées

During the first weeks, I took contact with experts to ask for information, ask for material and help to produce pieces (more specifically the wood support). The first meeting was with Pr. Darbellay related to the [usage of the 3D printer](https://github.com/Toys-R-Us-Rex/Duckify/commit/1c0e737268ec25757b5ae182a80c1e7aa0a9c6c6) and so I wrote a guide to use the printer. To organise this meeting I send an e-mail to him [Mail to Pr. Darbellay](assets/mail-3dprinter-formation.png)

To use the printer we have to provide specific file format that can be generated from a 3D modeling application. I asked Pr. Darbellay the necessary elements to have a licence. [Mail for licence](assets/mail_inventor_licence.png)

After an small discussion with Pr. Darbellay, I learn that I could ask him to cut wooden pieces that could help us to fix the support to a place because PLA can't really deal with the pressure of screw. Then I sent a mail to PR. Darbellay to take some information about this option [Mail about wooden pieces](assets/mail_wood_piece_information.png)

This discussion was followed by two spaced commands the first : [Wood command](assets/mail_wood_piece_command.png) and the second [Wood command 2](assets/mail_wood_piece_command_2.png)

Concerning the 3D design I booked an appointment with Mrs. Richard to talk about my sketch, the global idea about the placement, the support that will fix the duck support and pen supports [Mail for support sketch](assets/mail_support_discussion.png). An important point that was noted by this meeting is that I don't have to fix the support directly to an plate but I could use pins to align both elements and so I followed this meeting with two commands of pins directly to Mrs Richard. [Mail for pins](assets/mail_pins.png) [Mail for pins](assets/mail_pins_2.png)

## Argumenter ses opinions et ses choix lors de processus décisionnels et stratégiques

## Critiquer le déroulement d’une production de manière auto-réflexive
