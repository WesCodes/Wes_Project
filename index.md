## Pyrenote Development

### What is Pyrenote
Pyrenote is a website used to collect manual annotations of bird audio clips. Users are given bird audio clips and are tasked with annotating segments in the audio in which the specified bird appears.

The importance of this manual labeling process and Pyrenote as a whole lies in the importance of birds themselves. Birds are a very good environmental health indicator. The linkage between certain bird species and their habitats make them useful in identifying the health of an ecosystem. With these annotations, machine learning researchers can build bird classifiers based on their sound which will makes it very easy to quickly identify how an ecosystem is doing without the tedious process of manually identifying birds.

### What I do

I'm one of the developers for Pyrenote. Currently, my main responsibility is to resolve Pyrenote's GitHub pull requests and to create new features when needed.

### What I have completed

_**Implemented a "No Revelant Audio" button**_

Until now, users would get stuck if an audio file was empty, and be unlikely to contribute further. By adding a "No Revelant Audio" button, the user experience for annotating audio recordings will be more streamlined. By clicking on the button, a “No Class of Classification” label will be created for the corresponding audio recording. This additional label will also allow easy filtering in the data preprocessing stage.

_**Before**_
![Image](https://user-images.githubusercontent.com/21050768/157359699-772fe8c7-e8b1-4bd8-92e6-24ad78ff3cdc.png)

_**After**_
![Image](https://user-images.githubusercontent.com/21050768/157359702-165e1ac3-da98-4602-800c-4d438990b1b7.png)

_**Demo**_
![Alt Text](https://user-images.githubusercontent.com/21050768/156822862-530b95e0-aa7b-4a7d-a856-cf3644be9369.gif)

_**Slight rework to improve sidemenu toggle**_

This was a quality of life fix. Added ability to turn sidemenu on or off without also turning off or on the reference tab. Before, the sidemenu must be turned on if you want the reference tab to be turned on. To test this feature, go into the admin panel of Pyrenote. Assuming you have a project created already (create one if not), click on the icon with three parallel bars accompanies by three dots. Hovering over the icon should give a text of, "Turn on or off annotation features". If you select the reference window option without also selecting the sidemenu option, the reference window should still show up in the annotation page.

![Image](https://user-images.githubusercontent.com/21050768/153685818-053752e4-0c50-4796-8f52-ee887e7bfe9a.png)
Same setting used in before and after the rework to the side menu

_**Before**_
![Image](https://user-images.githubusercontent.com/21050768/157359700-877001ab-87aa-4cda-8f3f-aa6d18ecdb42.png)

_**After**_
![Image](https://user-images.githubusercontent.com/21050768/157360095-2a78fe30-9838-4cc8-9ea1-45bb1ad967bb.png)

_**Demo**_
![Alt Text](https://user-images.githubusercontent.com/21050768/156822875-fa70850a-ac8e-4c0a-804c-f8b0732fe5c7.gif)

_**Implemented a feature for admin-role users to manage projects**_

If an admin wanted to declutter the created projects in the admin panel, there wasn't feature that allowed for that need. Also, if an admin wanted to hide projects from non-admin users, there wasn't a feature for that need. I resolved those two needs by implementing a removal and recover feature. The specific changes I made can be viewed [here](https://github.com/UCSD-E4E/Pyrenote/pull/266). Admins can now remove any projects they want to declutter their admin panel and/or hide projects from users. 

_**Before**_
![Image](https://user-images.githubusercontent.com/21050768/157359902-1eb844e8-773a-4812-ac87-09de8d01d2e2.png)

_**After**_
![Image](https://user-images.githubusercontent.com/21050768/156826182-45613cae-a573-4aac-8254-4aba7fded8f0.png)
![Image](https://user-images.githubusercontent.com/21050768/156822743-ec2542e1-2b75-4a65-85f0-357e47f46c31.png)

_**Demo**_
![Alt Text](https://user-images.githubusercontent.com/21050768/156822869-fca02ebe-714f-4d2c-814d-a41e9f287cb1.gif)


### Why am I doing the things I'm doing
The three features I have worked on will help boost the scalability of Pyrenote for future projects as we become more ambitious with the number of users we bring to the site. Aside from its scalability benefit, the "No Relevant Audio" will allow researchers to conveniently inspect and handle audio files with zero audio events which may help improve quality in the annotation data. This potential improvement of annotation data quality can lead to a more accurate machine learning classifier and help scientists more quickly identify potential ecosystem concerns and take action through the use of machine learning classifiers. 

### How to view what I have completed

[Pyrenote GitHub](https://github.com/UCSD-E4E/Pyrenote)

Go to the link above and follow the instructions in the readme.md to get Pyrenote set up on your computer.
