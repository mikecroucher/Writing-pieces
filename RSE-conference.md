# RSE Sheffield in the 2nd RSE conference

The second RSE conference took place on the 7th and 8th of September 2017 at the
Museum of Science and Industry [MOSI](https://www.msimanchester.org.uk/).
There were over 200 attendees, 40 talks, and 15 discussion and hands-on workshops,
3 keynote talks, one of which was given by our very own head honcho Mike Croucher
(slides [here](https://mikecroucher.github.io/RSE_2017_keynote_presentation/)), and geeky chats galore.

RSE team members Mozghan and Tania were involved in the organising committee as talks co-chairs and diversity chair (disclose: they had nothing to do with Mike's keynote). Also, all of the RSE Sheffield team members made it to the conference, which seems to be a first due to the diverse commitments and projects involvement of all of us

## Conference highlights

With so many parallel sessions, workshops, and chats happening all at the same time it is quite complicated to keep a track of every single thing going on. And it seems rather unlikely that this will change over time as it was **evident** that the RSE community has outgrown the current conference size... in just 2 years!
So we decided to highlight our favorites of the event:

 - The talk on 'Imposter syndrome' [need to insert speaker]. Who in the scientific community has not ever experienced this? Exactly! So when given the chance everyone jumped into this talk full of relatable stories, and handy tips on how to get over it?

- Another talk that seemed to have gathered loads of interest was that of
[Toby Hodges](https://twitter.com/tbyhdgs) from  EMBL on community building. This came as no surprise to me as RSEs are often in charge of building communities or acting as a bridge between collaborating communities. Opposed to _just_ develop code and sitting in front of a computer.

- During the first day the RSEs had the chance to have a go at interacting with the [Microsoft Hololens](https://www.microsoft.com/en-gb/hololens). Everyone seemed to be having a great time doing so... unfortunately we did not have the chance to try it ourselves

- My hands-on workshop on 'Jupyter notebooks for reproducible research'. I was ecstatic to know the community found this workshop interesting and had to run this twice!!!

- [any others?]

## Our workshop on reproducible research
Being a RSE means that I serve as an advocate of sustainable software development. In addition, I am greatly concerned about reproducibility and replicability in science.
Thankfully, there are loads of tools and practices that we can adopt as part of our workflows to ensure that the code we develop is done by following the best practices possible.

Naturally, as members of the community come up with more refined and powerful tools in the realm of scientific computing we (the users and other developers) adopt some of those tools and, as a consequence, we often end up modifying our workflows.

Such is the case of Jupyter notebooks. They brought up to life a whole new era of literate programming: where scientist, students, data scientist, and aficionados can share their scripts in a human readable format. They transform scripts into a conveying scientific narrative where functions and loops are followed by their graphical outputs or allow the user to interact via widgets. The notebooks are a step closer to reproducibility in science.

However, the adoption of this tool means that our traditional version control (including diff and merge tools) are not completely compatible. What is more if we are pushing towards reproducibility we **have to test** the code.

Hence, I presented nbdime and nbval, tools developed as part of the [European funded project OpenDreamKit](www.opendreamkit.org). 
