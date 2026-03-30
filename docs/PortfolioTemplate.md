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

- Professionalism (soft skills)
  - Communicate clearly and efficiently
  - Adopting a professional and facilitative approach to the situations encountered
  - To argue one's opinions and choices during decision-making and strategic processes
  - To critique the process of a production in a self-reflective manner

For each point, Additionnal content will be add during the project concerning my contributions.

## Analyser un problème informatique complexe

After discussion with an expert (Ms Richard) I provide a [new design of wood supports](https://github.com/Toys-R-Us-Rex/Duckify/commit/1009e153e927d299d40bac70b55392cf1c785faa) because the precision required for 3d printed element to fit with other pieces can't be really determined in advance because of the potential printing error that could occur. Theses new wood support doesn't have hole for pieces but have hole for pins that will make the link between wood support and printed support.

Because of the capacity of the wood-cutting laser machine to provide limited size, the [new design of wood support](https://github.com/Toys-R-Us-Rex/Duckify/commit/1009e153e927d299d40bac70b55392cf1c785faa)

During our tests we discover that the pen support I printed had some friction issue with the pen and sometimes the support move with the pen. I tried two differents fixed : the first was to reduce the surface of contact with the pen but it happened that it was not a good idea because by removing this surface we remove the rigidity of the support and it can more block the pen. The second was to remove the slope and to only use horizontal and vertical shape. Every document relative to this issue are in this PR : [Fix of friction](https://github.com/Toys-R-Us-Rex/Duckify/pull/75)

A problem appeared for the tracing team and robot team concerning the axis and orientation of model I give. I haven't personnaly taken care of this point because I couldn't imagine the orientaion of the design I did could have any importance. I was wrong and after discussions with the concerned group I provide [oriented pieces](https://github.com/Toys-R-Us-Rex/Duckify/commit/02be7384ea0f5d1c3b25ee3d7182638ddd4411b0) with the choosen orientation for the duck and the [duck support](https://github.com/Toys-R-Us-Rex/Duckify/commit/60b868903d585489b0eca09b0ea36b5205b98de7)

## Concevoir une solution théorique modélisée

My first productions that can be found here [Support Sketch](https://github.com/Toys-R-Us-Rex/Duckify/commit/b0e30719beff070b21331087e49fd69d1de168e8). The objectives of these sketches were :

- To give me time to discover again Inventor. Take the habit of the different available tools.
- To show to the team how I would imagine a duck support in the concept.
- Create some complexe shape in the sence they require some deeper knowledge to design them.

I design a first version of pen support  [Pen-related model](https://github.com/Toys-R-Us-Rex/Duckify/commit/343e6cbbd831bb5ca98af4b043ff2c8a33d482d6)

I produce for the robot team [a test slope](https://github.com/Toys-R-Us-Rex/Duckify/commit/99d94a4e07718d70484d219bf683ba410575c68d) to provide a shape that is not a plate but not rounded to give a medium difficulty challenge.

I design a  [metal plate](https://github.com/Toys-R-Us-Rex/Duckify/commit/60afaa97607ae36a96b1a6e3f52b57007e52b891) that represent the large plate under the robot for presentation purpose and to help my teammate to visualize easily how my pieces assemble together

I design a first [support plate](https://github.com/Toys-R-Us-Rex/Duckify/commit/fecb2f54f8cad5a4a98d4de9e4413720ea7972cb) that has the objective to stick all the pieces together like a puzzle.

I design a new version of [wood suport in two pieces]([new design of wood supports](https://github.com/Toys-R-Us-Rex/Duckify/commit/1009e153e927d299d40bac70b55392cf1c785faa))

After discussion with the team : the design of wooden support with part that can assemble is not a must-have so I design the actual version of [wooden support](https://github.com/Toys-R-Us-Rex/Duckify/commit/2744d063d57a45c51c4c008668a7f58b87bfd6de) which is the first version which was cut that was sent to an expert (This kind of discussion will be shown in another part)

I printed the final version of [a support to elevate the duck](https://github.com/Toys-R-Us-Rex/Duckify/commit/87fb7a223b44f528bbda29b1b75b226d3845930e) so the robot could have more space and angle to paint the duck. A specific element that can be seen in the picture of the commit is some specific point that are waypoints used for calibration by the robot team.

## Implémenter une approche théorique modélisée

My first task as a new member of the robot team is to implement a program to have our robot to manipilaute different pens and be able to change it if needed : [the first version](https://github.com/Toys-R-Us-Rex/ur3e-control/commit/9df83da26b9467acfad9b6ffba3667ac34f35a2b#diff-19813992aad65f851cae5517226b46faafc23bc4bad4bb8edd93affceb40f1e5) will be adjusted to deal with the global strucutre of the robot program structure.

## Evaluer un système informatique

I tested the pen transition pipeline program I provided during a laboratory session and added in [the laboratory report its success]("documents/robot_labo_report.pdf")

I took time for the team GenAI to generate new types of duck texture with a new type of prompt content : I wrote [a report](https://github.com/Toys-R-Us-Rex/Duckify/pull/104) resuming my conclusion,

## Valoriser des ensembles de données hétérogènes et multimodales

Concerning the duck support, the robot team asked me to provide specific files concerning the disposition of the waypoint on the duck. So I give them [a plan of the piece and a small json files](https://github.com/Toys-R-Us-Rex/Duckify/commit/bbf75ee5c383c9d5a7572445edfacafa14d3a301)

## Orchestrer un processus et une infrastructure de traitement de données

Considering I deal with specific files format I decided to structre my commit and my production in a specific way that you can find in the [25th pull request](https://github.com/Toys-R-Us-Rex/Duckify/pull/25)

## Appliquer les compétences de l’ingénierie en informatique au domaine des données

I modify the code of the [pen transition programm to make it more adaptable to the pipeline](https://github.com/Toys-R-Us-Rex/ur3e-control/commit/852d50a1af87d1c2265d3a06e9b03f1dd0d77d01). This code was then improved by Mr. Antonietti.

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

I produce [assembly examples](https://github.com/Toys-R-Us-Rex/Duckify/pull/111) as illustration for my teammate to discuss element position and to show how we can use the different design of wood support I produced

## Critiquer le déroulement d’une production de manière auto-réflexive

# Questions

We were asked to provide questions concerning each week and so you can find in the following line theses questions

## Week 1

Q1
> Do you consider your role in the team can be considered as an "engineer" role ?
> I do, employer can need many various skills in their company.

Q2
> Depsite being a relatively "solo" role. How will you manage to be usefull for the team ?
> I can imagine that I will need to produce some specific tasks at specific moment depending on the needs of my mates.

Q3
> What do you find challenging in your role ?
> The most difficult aspect of my job will be to have precise result from relatively vague needs and measurements. I must adapt to the situation of the robot team and take care of their needs.

## Week 2

Q1
> Was it easy to adapt to your teammate demands ?
> Not really, in one side their needs were not precise and in the other part, I appreciate precision in tasks, having define objectives.

Q2
> Is the lack of precision in the objectives disturbing ?
> In my position, I have the capacity and the time to explore many solution. It lets me adapt to the result we observe.

Q3
> How do you deal with the tasks you planned to do and the asks of your team ? Do you have time to deal with both ?
> Of course it depends on the needs but I manage to complete the most of the tasks (except some validation point) even when my team asked me specific productions that weren't planned.

## Week 3

Q1
>
>

Q2
>
>

Q3
>
>

## Week 4



## Week 5



## Week 6

Q1
> Are you satisfied of your result concerning the prompt engineering session ?
> Yes. In fact, I don't think I discover nothing specially new but wrong result doesn't mean theses result are bad. I can learn from inconclusive result
Q2
> Do you consider that LLM must not be used during a project ?
> I wouldn't say it must not be used instead be used in an appropriate way. In my case, I used a LLM specialized in React website to generate a empty website with its template and almost all stylistic element because this kind of task is not a key element to our project.
Q3
>
>