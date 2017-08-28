# BriteCore-UX-Demo
Demo project for BriteCore to show a short sprint working methodology and general design flow.
## Unpack

#### Interviews
Interviewed two friends about their experiences with management software. 

##### _Insights_
For R. De La Hoz major pain point were: 
* **load time** 
  The software tended to load everything at once and it was a bunch of data. This meant a lot of waiting around for him.
* **contact limitations**
  The software was built in such a way that users could access the information but not necessarily act on it directly. This meant that if Mr. De La Hoz needed to connect an available asset to a project he would need to leave the application to make the request via email and to set things up outside of the application, only to then return to the application to update that asset's state.

For N. Conceição major pain point were: 
* **elements can only be asscociated to each other in a top down fashion** 
  In order for assets within the software to be managed they need to be created into specific entities and saved within a top down structure. To make a new group for example all elements of that group need to exist within the system individually. It is not possible for her to just add new elements from the grouping interface or from any other point within the flow. Considering that asset states are very flexible it is very time consuming to keep everything in order.
* **the interface makes it a bit hard to know what different actions, buttons, etc. do**
  There are many bells & whistles in the sofware she uses but it is so dense that at times it is very hard to know what actions can be taken from where. There is also quite a bit of seemingly random redundancies that require a long time to get used to.

#### Industry Reading
Sought a variety of articles on the day to day workflow of insurance managers

##### _Articles_
1. [A Day in the Life of an Insurance Agent](http://www.wealthmanagement.com/blog/day-life-insurance-agent)

2. [What's a typical day like for a life insurance agent?](https://www.quora.com/Whats-a-typical-day-like-for-a-life-insurance-agent)

3. [A Day in the Life of an Insurance Marketing Manager](https://www.google.com/amp/s/blog.central-insurance.com/2015/09/14/a-day-in-the-life-of-an-insurance-marketing-manager/amp/)

4. [7 Habits of Highly Effective Insurance Agents](https://www.agencynation.com/highly-effective-insurance-agents/)

5. [Overview of the Independent Insurance Agency System](http://www.iiat.org/docs/default-source/new-agency/am_ams_overview.pdf?sfvrsn=0)

##### _Insights_
* **a bit behind on their tech**
  Agents spend most of their time dealing with paperwork. Finding wasys to make their workflow less error prone is paramount..
* **accessing updated paperwork is really important and could save time**
  Because of the importance of paperwork agents need to have easy access to the most updated paperwork the carrier has to offer as well as easy access to a wide variety of forms, perhaps even input paths.
* **email seems to be their primary tool**
  Since a lot of their work is contact based, agents reaching out to clients, agencies to MCAs and to carriers, carriers back to agencies and angents, etc., it behooves us to integrate email into the workflow. It's the first place they seem to look at.

#### Mapping things out
##### _Notes_
* User needs the interface to be light, smart, flexible, clear. From my perspective they seem to be looking for managing accessibility.
* IF a table is displayed to the user THEN sorting by columns should be activated.
* IF a carrier assigns a state or policy to an asset (Agent/ Agency) THEN that asset would have a certain amount of time to furnish the required documentation and would be notified about their timeline. Assets could potentially issue requests for states or policies as well. 
* Should carrier's have the ability to manually deactivate assets (Agent/Agency) state activity?
* IF viewing a list carriers (could) THEN have the otpion to add new assets, or assign capabilities to the asset or even the entire list.
* The assignment of policy and state activity should be available from multiple access points.

![Unpack notes page 1](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Unpack-Notes-01.png)
![Unpack notes page 2](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Unpack-Notes-02.png)
![Unpack notes page 3](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Unpack-Notes-03.png)
![Unpack notes page 4](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Unpack-Notes-04.png)

## Sketch

#### Mobile
##### _Notes_
Started out in mobile to re-process my thinking through the task flows, with the intent to push up from there to table and to make a small adjustment from tablet to desktop if time allows.
* Noticed that it would be pretty sweet if agents and agencies could have access to the system so that they could stay on top of their licenses and carriers could then delegate that upkeep to them. I've included a note on this at the end of the mobile sketches section.
![Sketches page 1](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Sketch-Mobile-Notes-05.png)
![Sketches page 2](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Sketch-Mobile-Notes-06.png)
![Sketches page 3](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Sketch-Mobile-Notes-07.png)
![Sketches page 4](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Sketch-Mobile-Notes-08.png)
![Sketches page 5](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Sketch-Mobile-Notes-09.png)
![Sketches page 6](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Sketch-Mobile-Notes-10.png)

Thought on how asset (agency/ agent) self-management could be beneficial for carrier manager:
![Thoughts page 1](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Thought-Notes-11.png)

#### Tablet
##### _Notes_
Some examples to guide how elements move up from the mobile state to the more spacious tablet stage.
* Decided that for the asset profile it would be beneficial to split the screen to easily show licences and policies.
![Sketches page 7](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Sketch-Mobile-Notes-12.png)
![Sketches page 8](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Sketch-Mobile-Notes-13.png)
![Sketches page 9](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Sketch-Mobile-Notes-14.png)
![Sketches page 10](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Sketch-Mobile-Notes-15.png)
![Sketches page 11](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Sketch-Mobile-Notes-16.png)
![Sketches page 12](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Sketch-Mobile-Notes-17.png)
![Sketches page 13](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Sketch-Mobile-Notes-18.png)


## Decide
Having worked out most of the kinks in the sketches {considering the time available for completion :)} I set out to complete the next phase and in the process to refine my thinking about the solutions. 

##### _Insights_
Again I enlisted the help of Ms. Conceição and Mr. De La Hoz to get a sense if I was straying too far from users. They were soundly confused with the first task of adding an agent to an agency.
* **Where do I find the agencies?** It was not apparent that Agents would both include _individual agents_ **AND** _agencies_ . Surmising that an _agency_ is essentially a grouping of _agents_ In my defense I did find at least one source online where they were treated as the same thing. But in the end let the user prevail. 
* **Wait but which is more important?** There was a wee bit of confusion when I asked them if they could choose the most urgent task from the _home tab_ and it dawned on me that I really did need labels there.  So Critical, Pending and Normal were born. (You'll see later on what I mean.)

###### Some other decision points as part of the logic in no particular order:
* **TABLET:** the Asset screen will need to be split. Need to decide if I will use cards on the second column or not. (Could be useful.)

* **TABLET:** if doing Material-esque like Nav then may need to forget about crumbs. May still be doable but need to take a look at the interface.

* **GENERAL:** when managing a state under the policies tab a user would only need to manage Authorized agents for that policy in those states. Documents would be in the Documents tab and Forms as well. Or could it be useful to have the docs there as well?

* **IF** a screen is equal in depth to two and half of more full screens on the device it is shown **THEN** include a _To Top_ flat button bellow last element.

* **IF** a user scrolls **THEN** any action button would hide until the user either scrolls up or executes an action that contextualizes the button’s re-emergence. Such as scrolling back up or selecting something that offers new actions.

* **IF** the keyboard is pulled up by a field **THEN** the keyboard must match the field’s input modality: Alphanumeric, numeric, email input, etc. We can keep the user on task from field to field until it is done unless they choose hide the keyboard.

* **IF** the keyboard is pulled up **THEN** action buttons will hide until the keyboard is down and resume their normal behavior.

* **IF** a user taps outside of the keyboard **THEN** said action will hide it. (Fields below it will not be active for tap until the keyboard is down.)

* **Form entries** should be auto saved so that we can offer pending tasks to users.

* **IF** suggestions can be made for an input field **THEN** they should be made. Expl. By entering the State for the license we can reduce the  possible amount of licenses classes and that may help pre-populate the LOA.

* **IF** a screen does not have a specific location, like a form for example which is pulled out contextually, **THEN** it will have a close action associated with it on the top bar. It would behave as if it were a floating sheet.

* **IF** a screen has a specific location, like the agent profile, **THEN** it will have a back arrow to return to the previous screen.

* **IF** a user selects a policy from the policies list **THEN** they will be offered the option to assign it to an agent. IF the user decides to ‘assign agent’ THEN the assignment form’s name field match suggestions should be filtered by agents with applicable licenses.

* **IF** a form is contains required fields **THEN** the ‘done’ action button will not be available until they are completed.

* **IF** a user has valid licenses for more than ten states **THEN** the state selection interface will utilize a search tool to improve completion speed.

* **By requiring that a policy is linked to a state at the addition stage** we can ensure that when a state needs to be added it is added in the context of a policy. So, no need to add states independently of active policies.

* **IF** the search bar is engaged **THEN** the alphabet jumper will be hidden until the search flow is completed.

* **When search is engaged** elements below it should be lightened to aid the user to stay on task.

* **IF** a search is completed by selecting a single suggested match THEN the user is taken to that match’s profile. IF the user steps back from the profile **THEN** they will be placed back in the screen where they engaged the search from and on the initial letter section of the list.

#### Mobile
I decided to focus most of my efforts to fleshing out the solution for mobile as I imagined this would be the hardest part of the process and perhaps the most relevant solution to the managers. Imagining them waking up and being able to pull up elements on their commute, perhaps on the train or while waiting for their coffee gave me a sense that these managers (Carrier Managers) would benefit from having this module fully functional on their smartphone.

##### _Wires & Notes_
All screens designed here were designed and mirrored on an iPhone6 + and a Sony Xperia to ensure that all elements were up to real world measures. Aside from adhering to the mobile general guidelines for usability. I usually like to make touch areas a bit bigger just to make sure that there will be less likelihood of tapping errors. Here are some of the screens with a couple of notes although everything will be explained in detail on the demo video. But still some screens:

_Navigation Tabs_
![Decide Wires and Notes 1](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Notes01-Edited.jpg)
_Agencies Tab_
![Decide Wires and Notes 2](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Notes02-Edited.jpg)
_Agents Tab_ 
![Decide Wires and Notes 3](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Notes03-Edited.jpg)
_Policies Tab_
![Decide Wires and Notes 4](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Notes04-Edited.jpg)
_Agency Profile_
![Decide Wires and Notes 5](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Notes05-Edited.jpg)
_Assigning A Policy_
![Decide Wires and Notes 6](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Notes06-Edited.jpg)
![Decide Wires and Notes 7](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Notes07-Edited.jpg)

#### Tablet
All screens designed here were designed and mirrored on an iPad Air to ensure that all elements were up to real world measures. Here are the scaled up solutions for the main screens on table. The assumption here is that the implementation on Desktop would closely follow the Tablet solution perhaps scaling up if needed, considering the resolution of an average tablet.(iPad Pro viewport alone is 1024 x 1366 which is already at a desktop starting size.)
##### _Insights_
In the case of the tablet solutions it was mainly an exercise in translating the ease of the mobile solution to a two thumb universe, the tablet zone, while maintaining consistency in the design and capitalizing on the assumptions a user might have on tablet. Usually that they can handle any emergency on the couch.

##### _Wires & Notes_
Here are the screens with some notes. 

_Home Tab_
![Decide Wires and Notes 8](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Notes08-Edited.jpg)
_Agencies Tab_
![Decide Wires and Notes 9](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Notes09-Edited.jpg)
_Agents Tab_ 
![Decide Wires and Notes 10](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Notes10-Edited.jpg)
_Policies Tab_
![Decide Wires and Notes 11](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Notes11-Edited.jpg)
_Agent Profile Opt 1_
![Decide Wires and Notes 12](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Notes12-Edited.jpg)
_Agent Profile Opt 2_
![Decide Wires and Notes 13](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Notes13-Edited.jpg)


_Agency Profile_
![Decide Wires and Notes 5](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Notes05-Edited.jpg)

## Prototype
For the prototype I used Craft from Invision. 

##### _Notes_
* **First step** write out all the links for all the different tasks on my Omnilog.
_My Omnilog on OmniOutliner_
![Protoyping 1](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Screen%20Shot%202017-08-28%20at%2001.27.54.png)

* **Second step** link all of the screen elements as using Craft. It pays off to keep tidy files, layers, names, etc.
_A little section of the web of connections_
![Prototyping 2](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Screen%20Shot%202017-08-26%20at%2019.36.37.png)

* **Third step** after reviewing all the screens for errors, typos, etc. Start to test the protype on the phone. 
_Cooking it up in Invision_
![Prototyping 3](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Screen%20Shot%202017-08-28%20at%2001.26.21.png)

* **Fourth step** after ensuring that all the links were good and a couple of rounds of reworking the touchzones, it was time to record. 
_Fired up the screenrecorder_
![Prototyping 4](https://github.com/octovisual/BriteCore-UX-Demo/blob/master/Screen%20Shot%202017-08-27%20at%2018.57.23.png)

##### _Demo Video_
Unfortunately I could not add the demo video to the README.MD file so that one could just scroll down to it. It has audio as I go through all the screens and various tasks explaining some of the thinking behind it and how it could work. It is some 30 mins long.
