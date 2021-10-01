# mips-project-corbenha

**Project Overview**

In this project, we address an issue that technology has presented with regards to the integrity and accuracy of election results. In a very specific case, a random occurrence of 
solar interference changed a single bit stored within a machine that counted votes. The result was an inaccuracy that could have changed the actual results of the election. Though
this occurred on a minor scale and was eventually detected, on a larger scale this could have had great consequences to a democracy or the fate of a nation as the livelihood of
millions of people may have been affected by the outcome. In an extreme case on a larger scale, this could have had social, economic, and political consequences for millions or
billions of people around the world. Luckily the error was caught after a forensic analysis of the machinery and a recount of the vote exposed a technological vulnerability.

The goal of this project is to ensure the integrity and accuracy of election results by guaranteeing that the technology is not disrupted by outside forces, natural or man-made. 
We will discover a method for preserving the vote counts by updating the bits that store them regularly so that if a minor change is made, it must be accounted for and verified 
against a secondary mechanism. 

**Hamming Code**

We will use a method of Hamming code which uses a specific encoding  mechanism on a string of bits that represent a vote to verify that the original input matches what 
is decoded. This method is used vastly in technology to verify a variety of information and maintain its original value. In our case, this error detecting and correcting ability
is invaluable for ensuring accuracy of votes--whether it be a total vote count, or an individual vote itself.

