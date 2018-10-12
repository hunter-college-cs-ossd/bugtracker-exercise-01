# Bug Trackers

# Overview

The purpose of this assignment is to give you some experience 
with **bug trackers**, also known as **issue trackers**. Different source 
code hosting sites provide different issue trackers, and many 
large projects have their own custom trackers, so there is no 
standard describing what features a tracker might have or how it is used.
This assignment explores the *Bugzilla* bug tracker. 
It is predicated on your having completed the reading from Assignment 7.
If you have not read the section on bug trackers in the Karl Fogel book, 
please do so before you begin.

# Background

* Bug tracking systems are a tool for  change management and 
  organization used by open source projects in general.

* Bug trackers do far more than simply keep track of bugs. They are
  also used to manage and store new feature requests, patches, and 
  other tasks. 

* Bug trackers are also called *request trackers*, *issue trackers*, 
  and *ticket systems*.

# The Assignment Details

## Exploring Bug Reports

Open a browser and go to [GNOME Accessibility Bugs](https://bugzilla.gnome.org/buglist.cgi?quicksearch=GNOME%20Accessibility%20Bugs)

1. Define what each of the column names below indicate. For those 
   columns that have a discrete set of possible values, write what they are.
   This will require your rummaging around on the website to find the 
   documentation that describes this page.

	i. ID 

	* Product

	* Comp

	* Assignee

	* Status 

	* Resolution 

	* Summary 
	
	* Changed

2. Describe how you discovered the definitions and how you found 
  the information from above. 

3. Identify the order in which the bugs are initially displayed.

4. What is the meaning of the colors used when describing a bug 
  (red, gray, black)? (Hint: click on the Bug ID and examine the 
  fields)

5. Select a bug that you think that you might be able to fix and 
  look at it more closely (click on the bug number). 

	i. What is the bug ID?
	
	* Identify when the bug was submitted.

	* Identify if there has been recent discussion about the bug?

	* Is the bug current?

	* Is the bug assigned? To whom?

	* Describe what you would need to do to fix the bug. 

6. Repeat the previous step with a different kind of bug.

## Collective Reports

1. Click on the `Reports` link on the top of the page.

2. Click on the `Summary of Bug Activity for the last week`.

3. Of the top 15  Gnome modules, how many bug reports were opened 
   in the last week? How many were closed? 

4. What was the general trend last week? Were more bugs opened 
  than closed or vice versa? 

5. Who were the top three bug closers? Why is this important to 
  know? 

6. Who were the top three bug reporters? Are these the same as 
  the top three bug closes? What is the overlap in these two 
  lists? 

7. Who are the top three reviewers of patches? What is the 
  overlap between these lists and the bug closers and bug 
  reporters? What is the overlap between patch contributors and 
  patch reviewers? 

8. Click on the `Generate Graphical Reports` link.

9. Plot a bar graph of the severity of bugs by component for the 
  GIMP package, as follows:

	* Select `Severity` for the vertical axis

	* Select `Component` for the horizontal axis

	* Select `Bar Graph` for type of graph

	* Leave the `Multiple Images` as <none>

	* Scroll down and select `GIMP` from the `Product` menu. 
	
	* Select the following components from the `Component` menu: 
	   `Data, general, Gimp-Python, Help, Internationalization, User Interface`.
	   
	* Select all status values from the `Status` menu.

	* Click `Generate Report`. 
	
	* After the graph is generated, click the `Table` link below the graph to display the
	  data in tabular form.
	
	* Using a screenshot application, take a screenshot of your table and
	  save it to a file in this directory.

10. What class were the majority of the bugs for `braille`? 

11. What other reports can you generate?


## Deliverables

In this repository, create a file named `bugzilla_report.md` in 
which, using markdown, you provide answers to the above questions. 
Embed the image of your table into your markdown file.

