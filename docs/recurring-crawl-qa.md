#Washington University Libraries
##Production Crawl QA

###Login into Archive-it

* Navigate to  Crawls  section at top of page.
* Select [Crawl Reports](https://partner.archive-it.org/786/crawls).
* Find the appropriate crawl (identify Date, Collection, Frequency)
* Select Crawl ID for that crawl.  *This will lead to the crawl report page.*

###Document

**Before QA, fill out the first 5 fields in the spreadsheet:**

* **Reviewer**: 	Reviewer’s initials
* QA_Date: 	Date crawl was reviewed
* Collection:  	Name of the collection
* Crawl_ID: 	6 digit crawl number (#908123)
* Crawl_Date: 	Date completed (dd/mm/yyyy)
* New_Data:	Total amount of new data
* New_Docs:	Total number of new documents*

###Review Crawl Reports

In the report review the following:
Finished: Did it finish, hit a data limit or reach a time limit? If the crawl didn’t finish, the crawl may be missing content.
Hosts report: Are there large quantities of blocked, queued, or out of scope content?
Review hosts report for each seed (if multiple seeds were crawled) to see if any content was blocked, queued, or out of scope.
Individual seed hosts reports can be viewed by navigating to the seeds tab and selecting the seed URL.    
Review Wayback Results
Under seeds tab, follow Wayback > link to visually inspect each seed.
In an adjacent tab, open a live version of site to compare.
The following items should be considered:
Missing documents?
Are they significant?
Can they be patched crawled?
Do scoping rules need to be adjusted to capture content?
Overall site design changes?
If so, is it significant enough to merit full QA?
Content changed or been updated much from the previous crawl?
If not, the seed may need to be crawled less frequently
If so, the seed may need to be crawled more frequently
URL Change
