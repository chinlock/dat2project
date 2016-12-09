# dat2project
Course Project for GA DAT2

## What should I do?

I am thinking of analysing the National Jobs Database of ICT jobs
to answer the following questions:

1.  What are the demand areas for ICT jobs in Singapore?
2.  Can we cluster them based on SKILLS required?
3.  Can we cluster them based on LOCATION?
4.  Can we cluster them based on PAY?
5.  Can we cluster them based on TYPES OF COMPANIES HIRING?
6.  Given a job and skills profile, can we predict the PAY?

Other miscellaneous questions which may not be readily answerable:

1.  Why are people not applying?
2.  Is there a skills mismatch?

## Approach

1.  Bag of Words with tf/idf

## Method

1.  Crawl
2.  Format into Big Table
3.  Perform tf/idf computation
4.  Build model

## Possible datasets

1. [jobs bank](http://www.jobsbank.gov.sg)
2. [indeed.com.sg](http://www.indeed.com.sg)

------------

Update 1:  Dec 2016

Files:

01Acquire.ipynb - acquires data from indeed.com and saves them on a database



------------

### Reminders for myself
##### To commit changes to github:-
git add -A . && 
git commit -m "<message here>" && 
git push origin master
