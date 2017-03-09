This is an example template with an example of how to set up recurring meeting
discussions with Rachel. The idea is that before we have our meeting each week
(in person or virtual), each student will update their meeting template. I will
check the template before our meetings. For each week, it is useful to include:
- updates on previous goals
- things you need from Rachel
- goals for the coming week
- links to any related materials

This should help us have more effective meetings. It will also create a record
of progress as well as one place to look for information. It is probably a good
idea to have a research repository, and this be one item in that repository. You
can even link to the repo from the GroupResources SlaybaughLab repo if you want
to.

Some of the below setup was inspired by [bullet
journaling](https://www.youtube.com/watch?v=fm15cmYU0IM), which you don't need
to do--but might be interested in. Also, that was an example of an external link
:).

### <a name="top">Updates

* [Update: 2016/07/27](#update-20160727)
* [Update: 2016/07/13](#update-20160713)
* [Update: 2016/06/29](#update-20160629)
* [Update: 2016/06/22](#update-20160622)

***

### Update 2016/07/27

Goals from last week:
* **Completed** Prepare for interviews 
* **Completed** Do a practice job talk w/ friends
* **Completed** Continue with rebuild w/Seth's e-mail advice
* **Started** Do a live build with Seth on Savio
* **Completed** Document savio installation information
* **Not Completed** Move method to new logical Denovo module (pending code review) 
* **Not Completed** Merge current versions of advantg and exnihilo into my dev branches
* **Not Completed** Remove python error from fwcadis and fwcadisangle

Goals for the upcoming week:
* Move method to new logical Denovo module (pending code review) 
* Merge current versions of advantg and exnihilo into my dev branches
* Remove python error from fwcadis and fwcadisangle
* Get working version of Exnihilo on Savio
* Get fully working version of Exnihilo on Rasputin
* Continue documenting build process on both machines
* Plan out writing schedule for the semester

Postponed goals: 
* Figure out why the python error is showing up with fwcadis method options 
but not fwcadisangle method options.

[Index](#top)

***

### Update 2016/07/13

Goals for the trip:
* **Not Completed** Work on writing some of my thesis 
  * Note: I did actually work on writing, but I didn't get even close to the amount I was 
  expecting to, so I don't consider this completed. To make up for the work I've missed, I plan 
  on working on the weekend this coming weekend. 
* **Attempted** Try and debug the rebuild, if possible. 

Goals for the upcoming week:
* Prepare for interviews 
* Do a practice job talk w/ friends
* Continue with rebuild w/Seth's e-mail advice
* Move method to new logical Denovo module (pending code review) 
* Merge current versions of advantg and exnihilo into my dev branches
* Remove python error from fwcadis and fwcadisangle

Postponed goals: 
* Figure out why the python error is showing up with fwcadis method options 
but not fwcadisangle method options.

[Index](#top)

***

### Update 2016/06/29

Goals from last week:
* [**Started Code review**]Move method to new logical Denovo module (pending code review) 
* [**Not Completed**]Merge current versions of advantg and exnihilo into my dev branches
* [**Not Completed**] Remove python error from fwcadis and fwcadisangle
* [**Not Completed**] Figure out why the python error is showing up with fwcadis method options 
but not fwcadisangle method options.
* [**Completed**]Prep for interviews

Goals for Work in India
* Work on writing up more of background of thesis
* Continue debugging the rebuild, if resources are available (I am not brining my RSA key, so
any new pulls won't be possible while I'm on the trip)

Postponed Goals 
* Move method to new logical Denovo module (pending code review) 
* Merge current versions of advantg and exnihilo into my dev branches
* Remove python error from fwcadis and fwcadisangle
* Figure out why the python error is showing up with fwcadis method options 
but not fwcadisangle method options.

[Index](#top)

***

### Update 2016/06/22

Goals from last week:
* **Completed** Rebuild Exnihilo with no errors (and rerun all tests)
* **Completed** Figure out why Exnihilo build errors are occuring
* **Completed** Rebuild advantg with updated TPLs and python
  * **Completed** See if carryover python errors from last week are related
* [**Carry Over**] Remove python error from fwcadis and fwcadisangle
* [**Carry Over**] Figure out why the python error is showing up with fwcadis method options 

General updates: 
* Friday I successfully built Exnihilo and advantg
  * One of the advantg unittests failed, but I believe it is due to my own changes
* Monday I discovered that advantg couldn't run the example problems due to lack of lava support
  * Lava build / debug process is documented in my [Rasputin Lab
  * Notebook](https://github.com/munkm/Madicken-Research/blob/master/Lab-Notebook-Rasputin.md)
  * Spent some time getting lava support in Exnihilo (now not necessary)
  * Talked to Tara this morning and determined lava is NOT required for Exnihilo, but does
  need to be built for advantg. Remedied problem by making variant .cmake file for advantg 
  on Rasputin. 
* Python error occurs in both "moments" and my method branch, so this means that the 
error I was seeing a few weeks ago is related to incompatible Exnihilo and advantg stuff
  * I've updated the exnihilo and advantg master branches and am pending merging master into 
  my local branches (after I review and understand the code). 
  
* my method needs to be moved from pykba to a different module. 
* Reschedule meeting for 7/6 and 7/13
  * Seminar talk templates from Rachel? 
    * 2014 france talk 
    * 2015 davis talk
    * 2015 mines
    * 2015 UF
    * 2015 ORNL 
    * 2016 CoDA
    * 2015 INL

Goals for the next week:
* Move method to new logical Denovo module (pending code review) 
* Merge current versions of advantg and exnihilo into my dev branches
* [**Postponed**] Remove python error from fwcadis and fwcadisangle
* [**Postponed**] Figure out why the python error is showing up with fwcadis method options 
but not fwcadisangle method options.
* Prep for interviews

[Index](#top)
