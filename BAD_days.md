# BAD (Bioinformatics Awareness Day) at The University of Sheffield

The Bioinformatics Awareness Days are days devoted to Bioinformatics, each day consisted of a 2 hours in person
tutorial session covering a range of topics.
As a Marie S. Curie postdoctoral fellow @ SITRaN and Computer Science Departments
at the University of Sheffield, Luisa Cutillo **insert info** started such events
with the overall aim to democratize Bioinformatics, first at the Telethon Institute
of Genomics in Naples, and later, at Sheffield.

These BAD days (1 & 2) were first run in 2016 focused on basic data science and familiarization with Bioconductor, statistics and multiple hypotheses testing. The core materials developed for such courses were R scripts that could be run/modified on the attendees laptops.

Earlier this year Luisa Cutillo and the Research Software Engineering team at TUoS started working together to improve the existing content for the BAD days and generate new materials for a third event, which will focus on RNA-sequencing analysis.

During the early planning stages it became evident that one of the main limitations of the original setting for the BAD days was in fact, the use of R scripts. This setup required that all the assistants had previously installed R, Rstudio, and a range of packages available both, through CRAN and Bioconductor. Even though this sounds like a common setup for an experienced R users most of the attendees were not experienced R programmers. The more experienced ones had their own setups, with a number of R and Rpackages veMrsions.. leading to the "install + run + replicate" problem.

We then decided that the best way to move forward was to provide the attendees with an ecosystem that would reduce the number of libraries/packaged needed to install while focusing on the actual bioinformatics content.
As a consequence, it was decided to use Jupyter Notebooks with the R kernel. In addition a static website using the notebooks as main content source was created. Such a combination of technologies ensured on one side ease of use of the content as well as rich content that not only the participants could follow over the sessions but could be available for future access on the web. 
