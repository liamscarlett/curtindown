See the original README file in the ulyngs/oxforddown repository instructions. This fork contains only minor edits to adhere to the Curtin University PhD thesis style. The introduction chapter included here is the same as the one from oxforddown.

### Main changes from original oxforddown: 
* Default title page now follows Curtin Univertsity PhD thesis guidelines
* Front-and-back-matter directory replaced with frontmatter directory which now only contains the frontmatter in various .tex files
* Default frontmatter files follow Curtin University guidelines. The paths to these files are defined in the FRONTMATTER section of the index.Rmd file, and can be commented out to remove them from the thesis
* The 98-appendices.Rmd file is now in the main directory along with the other chapters (if, god forbid, you have more than 98 chapter then rename this file with a larger number)
* Default format for chapter names has been restored. To include chapter quotes and use the chapter format used by oxforddown, uncomment the `\usepackage[grey,utopia]{quotchap}` in templates/curtinthesis.cls
