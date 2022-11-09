# Hosting a Resume on GitHub Pages

## Purpose
This README will guide you to host your resume on GitHub Pages by following the instructions below, using the tools described in _Andrew Etter's book Modern Technical Writing_ .

## Prerequisites
 * A personal resume formatted in Markdown.
> If you do not know how to use Markdown, down in the section [More resources](https://github.com/AbdelrahmanAljamal/AbdelrahmanAljamal.github.io#more-resources) you will find a good link for Markdown tutorial.
 * A GitHub account.
> if you do not have one please visit link provided in [More resources](https://github.com/AbdelrahmanAljamal/AbdelrahmanAljamal.github.io#more-resources) at the bottom, to create a new GitHub account.
## Instructions

1.  Log in to the GitHub account
 
   * GitHub is one of the best Distributed version control 
     >  Andrew  Etter already mention in his book why using DVCS have some advantges over centralized systems such as, better performance and allows offline work.  
   * For that we will use the GitHub to have the abillty to change or edit your resume later.
  
2. Create a New Repository  

   * Create a new Repository and naming it ``` userName.github.io ```  
    
 ![createRepo](https://github.com/AbdelrahmanAljamal/AbdelrahmanAljamal.github.io/blob/main/createRepo.gif)
3. Add a file ``` index.md ```

   * Add the file ``` index.md ``` to the repository, and add your resume in it .  
   ![newFile](https://github.com/AbdelrahmanAljamal/AbdelrahmanAljamal.github.io/blob/main/newFile.gif)
4. Choose a Theame for your resume

   * Visit this [link](https://pages.github.com/themes/) and choose your preferable theme. 
   * Click on your preferable theme and search for _config.yml file. 
   * Open the _config.yml file and copy the line of ``` theme: jekyll-theme-_nameOfTheTheme_ ```   
   
 ![chooseTheme]( https://github.com/AbdelrahmanAljamal/AbdelrahmanAljamal.github.io/blob/main/chooseTheTheme.gif)
 
5. Add the file ``` _config.yml ```

   * Write in the first line ``` title: _yourName Resume_ ```
   * Paste the line you copied from the previous step.
  
   ![confiFile](https://github.com/AbdelrahmanAljamal/AbdelrahmanAljamal.github.io/blob/main/create_config.ymlFile.gif)
6. We are done !

	* you can check your resume by visiting ``` userName.github.io ```  
	
  ![theResume]( https://github.com/AbdelrahmanAljamal/AbdelrahmanAljamal.github.io/blob/main/theResume.gif)
## More Resources
  * To learn MarkDown visit this [Link](https://www.markdowntutorial.com) 
  * To create a new GitHub account visit this [Link](https://github.com/join)
  * To buy Andrew Etter's book visit this [Link](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

## Authors and Acknowledgments
##### Author : Abdelrahman Aljamal 

## FAQs
  * Why is my resume not showing up?
    * it takes a while to show up.
  * Can I add a description to my resume ?
    * you can do that by adding ``` description: _yourDescription_ ``` to  _config.yml.
