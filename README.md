## XML World-Countries XPath Exercises

In these exercises, you will be working with a small XML data set about world countries. This data is adapted from the Mondial 3.0 database as hosted by the [University of Washington](https://www.cs.washington.edu/research/xmldatasets/www/repository.html#mondial), and was originally compiled by the [Georg-August University of Goettingen Institute for Informatics](https://www.dbis.informatik.uni-goettingen.de/Mondial/) Links to an external site.. Each country has a name, population, and area (in sq. km). Some countries also list languages (with percentages of the population that speaks each language) and/or cities (with names and populations). The XML data is in `countries.xml`.

**Note:** Your solution will need to reference doc("countries.xml") to access the data.

For each problem, you are to write an XPath query.  Your query must be contained in the file `countries_xpath_p?.xpath` where `?` is the problem number, so for example, the query for problem 1 must be contained in the file `countries_xpath_p1.xpath`.

### Codespaces setup

You can get an cloud environment to do these exercises using Codespaces so that you do not need to install any software or set up your own environment.  To use Codespaces, open the GitHub repository in your web browser, click on the **Code** button and select the **Codespaces** tab, then click the **Create codespace on main** button.  This will set up a cloud environment that you can interact with using the VS Code Integrated Development Environment (IDE) .  If you have already created a Codespace previously for this assignment, you can simply click on the name of the Codespace under "On current branch".

### Problem 1

Return the area of Mongolia.  

### Problem 2

Return the names of all cities that have the same name as the country in which they are located.  

### Problem 3

Return the names of all countries that have at least three cities with population greater than 3 million.  

### Problem 4

Return the average number of languages spoken in countries where Russian is spoken. 

### Submission

Run the following commands in the Terminal in VS Code to submit your code:

```
git add .
git commit -m "Submission"
git push
```

**Do not forget to submit your code!**  After submission, you can see your grade by opening the GitHub repository in your web browser and clicking on the **Actions** tab. You may resubmit as many times as you like before the deadline.
