# Choosing a Project

Choosing a project can be frustrating at worst. There's often a lot of ideas to choose from, and it's difficult to tell which will be the "best" to move forward with. Here's a few criteria I've found most helpful in selecting a project idea.

## 1. What's the problem?
In most cases you will be starting an iGEM project with the intention of solving an existing problem, creating something that does not already exist, and/or improving upon previous work. This question could be rephrased as, "Why is your idea important?"

Starting by thinking about things that are interesting to you, taking a look at the [competition tracks](https://competition.igem.org/participation/tracks), or talking with friends. Generally, *avoid* thinking about solutions to the problems just yet. Often, saying "I want to use NGS (Next-Generation Sequencing) in this project" is less useful than "We should make directed evolution easier". The former locks you in to a particular scope for your project that may be less feasible and could lead you to not finishing your project. The latter is a better start. Jeremy Fielding has an excellent video on his YouTube channel that touches on this specifically:<br>[https://www.youtube.com/watch?v=FHhXbz1K0k0](https://www.youtube.com/watch?v=FHhXbz1K0k0)

Another reason you may want to start with a clear problem definition is specific to the medal requirements (Human Practices and Integrated Human Practices). To satisfy these requirements, you need to demonstrate how "your work is responsible and good for the world" - in other words, what problem it solves. Having a clear need for your project will help you find experts who care about the same problem or are interested in the same topic. *Don't* be tempted to push Human Practices goals towards the end of your project or you risk not getting a medal!

## 2. Homework.
Once you have an idea of which issue you are going to tackle, search everywhere you can for information about how others have solved this problem (or similar problems). It's really tempting to think of a really complex and technically advanced solution where one may not be necessary. Instead, looking at previous and ongoing work can help you decide what is worth your (and your team's!) time. Reach out to people! Many people will be willing to talk to you, including PIs at your university, civil servants, citizen scientists, people affected by the problem, etc..

Admittedly, our (Hopkins) [2021 project](https://2021.igem.org/Team:Hopkins) fell short here. We found an interesting problem - coral aspergillosis - but failed to realize that Aspergillosis specifically was less of a problem than it was in the 1990s and 2000s. Reason? Most of the susceptible corals had *died as a result of the infection*, and the remainder had a reduced incidence of aspergillosis. Only after discussing with researchers from NOAA did we realize that the current focus had shifted to other infections such as Stony Coral Tissue Loss Disease (SCTLD).

## 3. More Homework.
Synthetic biology at its core is a very targeted approach. If you intend to modify the behavior of some existing biological system, you need to understand how it works.

In most cases this will involve laying out the entire **pathway diagram**. Yes, they are useful!

It's also high time for you to think:<br>
**Is this a synthetic biology problem?**

While I really enjoy working on synthetic biology projects, I think it's important for me to say this:<br>
Not many problems are worth the additional complexity, cost, and development time of a synthetic biology solution. Most often, ideas can be readily solved using some combination of:<br>
1. Organic Chemistry<br>
2. Materials Science<br>
3. Electrical Engineering

I'm serious. If the central idea of your project is the production of some molecule, synthetic biology is likely not a great solution for that problem. If the idea is to produce a novel material with some properties, do check if there are synthetic materials that provide the desired functionality (because they likely will at a lower cost). If the objective is to detect and respond to some stimulus, do check if there is some electrical component (transducer, sensor, etc.) that can already detect that. 

If some prior work exists that suggests that the problem isn't a synthetic biology problem, do consider whether a synthetic biology solution could add some additional functionality or improve existing solutions. If the answer would not satisfy you and your team in a season's worth of work, do not be afraid to move on and consider other problems you could address.

For our (Hopkins) 2022 project, we were trying to enable plants to grow in microgravity. We had identified a problem, that astronauts need food for long-term space missions, and that plants grew uniformly smaller in space. We then searched on Google Scholar for any papers regarding plant gravitropism. A lot of searching later we identified that gravitropism relied on the motion of large organelles (statoliths), which change the intracellular distribution of auxin carriers (PINs), and cause a change in the root circulation of auxin hormones. The concentration of auxins in a cell is related to its elongation, so roots in particular will steer towards the direction of gravity as a result. We researched existing solutions and realized that they are focused on improving aeration and air/water mixing in the root to avoid salt stress, hypoxia, and dehydration. We thought that the gravitropism problem wasn't properly addressed by these growth chambers.  his understanding of the pathway was useful when we . . .

## 4. Now, Start Designing.

Now that you understand the problem, the possible scope of your solution, and the biological pathways involved you are ready to start thinking about how your project can alter their function.

It's important to choose a **chassis** (the organism you are going to engineer). **Do** choose commonly available organisms that are safe to use. Generally, **avoid** organisms that are hazardous to humans or the enviroment. The iGEM [Safety](https://old.igem.org/Safety) and [Engineering](https://technology.igem.org/engineering/introduction) committees can be of great help here, do reach out to them. iGEM Safety also does have specific policies for working with organisms by biosafety level. Also check with your institutional biosafety office and your team advisors about safety concerns before beginning work. It should go without saying, but BSL3 or above organisms are off the table.

Here is a very brief list of good chassis to use:<br>
Bacterial<br>
 * Escherichia coli (K12 derivatives in particular)<br>
Plant (try to avoid monocot plants):<br>
 * Arabidopsis thalania<br>
 * Nicotiana benthamiana<br>

Many teams will not have the resources available to work with mammalian cell lines, so do consider whether the concept could be demonstrated in an alternative chassis.

As a general principle,<br>
**The simplest mechanism will work the best.**

This is usually true! You have less than a year to work on your iGEM project. Avoid falling into the following traps:<br>
1. De novo (from scratch) design of some protein (antibodies in particular). As of writing, this is more in the scope of a PhD project!<br>
2. Egregiously complex genetic circuits. You will need to assemble the DNA, and that takes time. Sometimes, your entire project timeline can dissapear from cloning and ambitious expectations (*speaking from experience . . .*).<br>
3. Again, egregiously complex genetic circuits. Even if the cloning is relatively simple, your genetic circuit should not look like a Rube Goldberg machine. State the circuit you are trying to make out loud. If it goes along the lines of "This thing pokes that, which turns off that, which enables this, which causes that, . . ." yikes. [K. I. S. S.](https://en.wikipedia.org/wiki/KISS_principle)!<br>
4. Generally, doing complicated things because you want to and not because they are needed. Ask a friend for feedback! Ask officers, alums, and advisors for feedback.

![](https://upload.wikimedia.org/wikipedia/commons/a/a9/Rube_Goldberg%27s_%22Self-Operating_Napkin%22_%28cropped%29.gif)<br>
*A bad mechanism.*

Also, a specific note regarding projects that have environmental release as an endpoint. As of writing, environmental release of any engineered nucleic acid or any organism containing engineered nucleic acids is outside the scope of an iGEM project (and perhaps even a bad idea). Gene drives in particular are forbidden. Consider whether your project could instead be used in some controlled environment (labs, wastewater treatment facilities, spaceflight, etc.).

For our (Hopkins) 2022 project, we debated modifying the gravitropism pathway with magnetic proteins a number of different ways. Some suggested mechanisms included magnetosensitive auxin carriers or magnetic field sensitive protein expression. Instead, we revisited the biological mechanism and realized that if we pulled down on the statoliths in the presence of a magnetic field, all the remaining steps of the innate pathway would follow. We decided to form our project around filling the statoliths with magnetoferritin, so they could be pulled down in the presence of a gradient magnetic field. A much simpler mechanism!