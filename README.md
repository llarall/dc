# GenderMag Design Catalog

The purpose of the design catalog (http://gendermag.org/dc/) is to provide ideas for making software user interfaces inclusive to more cognitive styles.

## About this Repository

*dcdev* is the repository for the GenderMag Design Catalog dev site: http://gendermag.org/dcdev/. 

## How to Modify Existing Catalog Files
1. Clone this repository to your local machine.
2. Modify files as needed, commit, push to origin.
3. See "Deploying Changes to Live Site", below.

## How to Add to the Catalog
1. Create a new folder. The name of the folder is the name that will appear on the website.
2. Add these files to the folder:
	- cats.txt (the non-facet categories the design goes in, one per line. options: survey, opensource, website)
	- problem.txt (why the design isn't inclusive to some cognitive styles)
	- solution.txt (how the design tries to solve the problem)
	- facets.txt (one facet per line, use these abbreviations: m, cse, atr, ips, ls)
	- zoom_before.png (what the design looked like before it was changed; png or jpg; other image formats might also work)
	- zoom_after.png (what the design looked like after it was changed; png or jpg; other image formats might also work)
3. See rubric below for more guidance

### Facets Cheat Sheet
* m - Motivation
* cse - Computer Self-Efficacy
* atr - Attitude Toward Risk 
* ips - Information Processing Style
* ls - Learning Style

### Rubric for adding a new design
- Title: put solution first followed by verbage used in the facet description (e.g., helps with confidence, navigating, etc.)
- Problem Column:
  * Problem statement about which items specifically in the UI are problematic (**past tense**)
  * A single facet is chosen as the “prominent” facet and used to describe why a user would run into issues (**present tense**)
  * "Also affects users with:" other facets that are implicated but said with an Abi or Tim trait (i.e., low computer self efficacy, selective information processing style, etc.)
- Solution Column:
  * Solution statement about which items specifically in the UI were fixed (**past tense**)
  * Reference a single “prominent” facet to describe how the fix helps that type of user. Also, include how it doesn’t hinder a persona with the opposite end of the spectrum facet. (i.e., help risk aversion but doesn’t hurt risk tolerant) (**present tense**)
  * Use wording that applies to the fix (e.g., Better organization also helps users with:) and list the facets that were implicated with the problem column
  * Add a validation (e.g., user study) or a location where the changes were made (e.g., OSU curriculum proposal form) (**past tense**)

## Deploying Changes to Live Site
* Commit and push your changes to origin.
* On _guille_, copy your changes from gendermag\dcdev to gendermag\dc