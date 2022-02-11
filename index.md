## Pyrenote Development

### What is Pyrenote
Pyrenote is a website used to collect manual annotations of bird audio clips. Users are given bird audio clips and are tasked with annotating segments in the audio in which the specified bird appears.

The importance of this manual labeling process and Pyrenote as a whole lies in the importance of birds themselves. Birds are a very good environmental health indicator. The linkage between certain bird species and their habitats make them useful in identifying the health of an ecosystem. With these annotations, machine learning researchers can build bird classifiers based on their sound which will makes it very easy to quickly identify how an ecosystem is doing without the tedious process of manually identifying birds.

### What I do

I'm one of the developers for Pyrenote. Currently, my main responsibility is to resolve Pyrenote's GitHub pull requests.

### What I have completed

_**Implemented a "No Revelant Audio" button**_

Until now, users would get stuck if an audio file was empty, and be unlikely to contribute further. By adding a "No Revelant Audio" button, the user experience for annotating audio recordings will be more streamlined. By clicking on the button, a “No Class of Classification” label will be created for the corresponding audio recording. This additional label will also allow easy filtering in the data preprocessing stage.

![Image](![image](https://user-images.githubusercontent.com/21050768/153686202-16dbaf30-03a8-4b37-9fc5-503917421bf3.png))

_**Slight rework to improve sidemenu toggle**_

This was a quality of life fix. Added ability to turn sidemenu on or off without also turning off or on the reference tab. Before, the sidemenu must be turned on if you want the reference tab to be turned on. To test this feature, go into the admin panel of Pyrenote. Assuming you have a project created already (create one if not), click on the icon with three parallel bars accompanies by three dots. Hovering over the icon should give a text of, "Turn on or off annotation features". If you select the reference window option without also selecting the sidemenu option, the reference window should still show up in the annotation page.

![Image](![image](https://user-images.githubusercontent.com/21050768/153686162-6a54e82d-851b-412a-b4dd-b8f2f972da3a.png))
![Image](![image](https://user-images.githubusercontent.com/21050768/153686194-2163f83b-0eae-40ca-89eb-2645e4652a99.png))


### How to view what I have completed

![Link](https://github.com/UCSD-E4E/Pyrenote)

Go to the link above and follow the instructions in the readme.md to get Pyrenote set up on your computer.
