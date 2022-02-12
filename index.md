## Pyrenote Development

### What is Pyrenote
Pyrenote is a website used to collect manual annotations of bird audio clips. Users are given bird audio clips and are tasked with annotating segments in the audio in which the specified bird appears.

The importance of this manual labeling process and Pyrenote as a whole lies in the importance of birds themselves. Birds are a very good environmental health indicator. The linkage between certain bird species and their habitats make them useful in identifying the health of an ecosystem. With these annotations, machine learning researchers can build bird classifiers based on their sound which will makes it very easy to quickly identify how an ecosystem is doing without the tedious process of manually identifying birds.

### What I do

I'm one of the developers for Pyrenote. Currently, my main responsibility is to resolve Pyrenote's GitHub pull requests.

### What I have completed

_**Implemented a "No Revelant Audio" button**_

Until now, users would get stuck if an audio file was empty, and be unlikely to contribute further. By adding a "No Revelant Audio" button, the user experience for annotating audio recordings will be more streamlined. By clicking on the button, a “No Class of Classification” label will be created for the corresponding audio recording. This additional label will also allow easy filtering in the data preprocessing stage.

![Image](https://user-images.githubusercontent.com/21050768/153685821-882a2a51-3522-4483-a5ce-69ad27a6c51c.png)

_**Slight rework to improve sidemenu toggle**_

This was a quality of life fix. Added ability to turn sidemenu on or off without also turning off or on the reference tab. Before, the sidemenu must be turned on if you want the reference tab to be turned on. To test this feature, go into the admin panel of Pyrenote. Assuming you have a project created already (create one if not), click on the icon with three parallel bars accompanies by three dots. Hovering over the icon should give a text of, "Turn on or off annotation features". If you select the reference window option without also selecting the sidemenu option, the reference window should still show up in the annotation page.

![Image](https://user-images.githubusercontent.com/21050768/153685818-053752e4-0c50-4796-8f52-ee887e7bfe9a.png)
![Image](https://user-images.githubusercontent.com/21050768/153685823-3d827cef-b577-4ea7-ae11-ff811a7fc5f5.png)


### How to view what I have completed

[Pyrenote GitHub](https://github.com/UCSD-E4E/Pyrenote)

Go to the link above and follow the instructions in the readme.md to get Pyrenote set up on your computer.
