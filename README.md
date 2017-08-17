# Verbos
```
An Open Source project for automated video translator system.
This project is **a personal idea** I wrote as a thesis project which should allow to create an automated 
video translation system using Machine Learning, Deep Learning and related. The input should be a Video in 
a given language (for example 'English'), and the output should be in another different language 
(for example 'French'). 
The output should keep the images in the original video, but automatically translate the speech.
```
	


#``Proposal for the project``
----------------------------

### Domain Background
Dozen of years ago, with the coming of internet the use of video for information change generalized. Videos are present in several various domain : academic, professional, but also for the public. But this is not hasardous. Indeed, several keen studies showed that using of video allows a cognitive worth for their users, unlike a simple reading. 

"The using of video as an illustration item, for instance, leads to bring to learning a dimension more close to reality because a situation which is complex to describe could be more understandable using a presentation of fix images or animated sequences" (De Lièvre et al., 2000)[See Here](https://www.usherbrooke.ca/ssf/veille/perspectives-ssf/numeros-precedents/septembre-2012/le-ssf-veille/pourquoi-utiliser-la-video-en-formation/).

The fact that information shared via this method are universal lead to invention of subtitle allowing to a huge number of abroad internet users to follow videos that are broadcast in foreign languages. Obviously this allow to reach a more wide range of stakeholders including those who accept to read subtitles. But we must acknowledge that this methode is annoying, specifically for long hours of video.

So to increase the chances for a user to understand a video displayed in a foreign language, why do not invent an automated video translation system which would translate instantly (or almost instantly) the displayed video, in its desired language. 
As consequence, this could lead to an immediate clear enhancement of the cognitive abilities of the subtitle video readers.
A such system should also take into account the different possibilities of interaction with human cognition, with the intention to increase people learning abilities according to the final result.



### Project Objectives
The main objective for this project is to create a system which ensures an automated voice translation of a video from a given language to another one, different from the input video.
Then, this should be useful to several subojectives to define.

So the system would be very useful for information change in these domain :

	- Academic (Students, Researchers, etc.)
	- Online courses (MOOC)
	- Public information (publy the video in one language, and anyone could watch it in its desired language, 
	through the system)
	- Etc.


### Project Functionalities
- import or select the video to display
- select the output language (set a default output language)
- take into account online videos
- Keep the original voice tempo
- Keep the original video picture
- The translated voice should replace the orginal one
- Etc (to be continue).


### Project Architectures 
Here I will propose some of my actual architectures (or vision) of the system, and open it for discussion.
Could be an architecture based on open source system and/or through proprietary but very low cost APIs and discuss the what and why cases.

So anyone interested in could contribute with a more clear explanation.

I just give below a list of idea I will detail later:
- Online (Work on subtitle direct translation ?)
- Immersive solution : get into video and tranform features through "Advanced Video Coding Systems"
- Apply Advanced translation APIs to the video sound (without any transformation inside the video)
- Use AENet to perform the job
- Etc.

![alt tag](https://github.com/Kjeanclaude/Verbos/blob/master/Verbos_System_Final.png)


### Project Contribution to Knowledge
This project brings a contribution in the field of Human Machine Interaction (HMI). Until nowadays translate systems mostly propose simple subtitles for their contents. This work should be an open proposition for another possibility which aims to be on one hand more efficient concerning people learning capacity (cognitive value), and on the other hand concerning the increasing of the number of learners (as stakeholders don't need to understand the language in which the video is originally published).

This will make the video accessible, a priori, to anyone no matter his language. And moreover, this technique would be continually improved next.

### Some References

-	**Advanced Video Coding Systems**, Wen Gao & Siwei Ma, ISBN 978-3-319-14243-2 (eBook).
-	**AENet: Learning Deep Audio Features for Video Analysis** | Naoya Takahashi, Michael Gygli, Luc Van Gool
[Download here](https://arxiv.org/pdf/1701.00599)
-	**Google’s Multilingual Neural Machine Translation System: Enabling Zero-Shot Translation** | Melvin Johnson, Mike Schuster, Quoc V. Le, Maxim Krikun, Yonghui Wu, Zhifeng Chen, Nikhil Thorat, Fernanda Viégas, Martin Wattenberg, Greg Corrado, Macduff Hughes, Jeffrey Dean
[Download here](https://arxiv.org/pdf/1611.04558v1.pdf)
