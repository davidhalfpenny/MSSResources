# How To Contribute
(This guide adapted from the home of the [Awesome](https://github.com/sindresorhus/awesome/blob/master/contributing.md) list)

## What information is needed?/How the information is organised

For the list of course providers and certification providers, the format of information is generally just a summary of important information. Look at a few entries and try to duplicate that information for any new entries. 

For the certification providers, a list of *relevant* certifications is required. 

The learning resources have and require the most information. While some effort has been made to obtain a complete set of information for each entry, sometimes the information doesn't exist, sometimes it doesn't apply, and sometimes it just wasn't easily obtainable (e.g. it may have been behind a paywall). If you have information that can complete an entry, or if you have a new entry to add, or if you find some information is incorrect, here's the information which you should include in your contribution:

* Technology - if the course relates to a specific technology (e.g. Splunk, AWS, Git) add it here. Separate technologies with a comma, for example `python, git`. If it's not specifically about a technology, leave this blank.

* Provider - who provides the training, e.g. Splunk, Coursera, Udemy

* CourseName - the name of the course

* URL - direct url for the course, not a generic url for the course provider unless no other URL is available.

* CourseMode - this should be `elearning` or `ILT` for instructor led training. Where both are available, put `elearning`.

* TimeToComplete - if possible, denote how long it takes to complete the course (or at least the instructional components). Format is `XdXhXmXs`, but not all components are necessary (e.g. `6h` is fine). For elearning courses it's typical to list time in hours, minutes, and seconds, while ILT courses are typically listed in days. For elearning courses that state something like 2 hours a week for 5 weeks, just leave it blank.

* Cost - if a cost is listed, please note it here along with the currency.

* CourseSummary - in most cases, a one or two paragraph description of the course can be lifted straight from the course website. Don't include everything listed on the site, just a summary. You can edit it down if you wish.

* Topics - where possible, copy the syllabus of the course here, one topic per line. If the course is composed of multiple sub-courses, just list the component courses here.

* Notes - if there's anything particular to note about the course, add it here.

The current format for the list of learning resources is:

 # Technology
 <details>
   <summary>View Details</summary>
  
 <details>
   <summary>Course Name</summary>
  
  
 URL
  
 Course provided by **Provider**
  
 CourseMode - TimeToComplete - Cost
  
  
 CourseSummary
  
 Notes
 </details>

## Steps for making a contribution

If you want to contribute a resource, update a resources, report an error/improvement etc., you'll need a [GitHub account](https://github.com/join)!

1. Access the [MSSResources list GitHub page.](https://github.com/davidhalfpenny/MSSResources)
2. [Click on the `README.md` file](https://github.com/davidhalfpenny/MSSResources/blob/master/README.md) and read it. Pay particular note to the reason this list exists and make sure your contribution is in that spirit.
3. Click on the whatever file you want to add to/subtract from/correct or whatever. Click on the edit icon. ![Click on the edit icon.](/images/editButton.png)
4. You can now start editing the text of the file with the in-browser editor. Use the guidelines above to add information, correct/improve it, or create a new entry. You can use [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown/).
5. When you've made the changes, go to the bottom of the page, explain the change you're proposing, then click on "Propose file change".![Propose file change](/images/proposeChanges.png)
6. Submit the [pull request](https://help.github.com/articles/using-pull-requests/)

## Updating your Pull Request

The maintainer of the list may ask you to update your Pull Request before it's included. This is normally due to spelling errors or because your submission didn't meet the guidelines. Sure, the list maintainer could just fix these things, but you should get the credit for your contributions, so the Pull Request will be sent back for you to fix.

[Here](https://github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md) is a write up on how to change a Pull Request, and the different ways you can do that.
