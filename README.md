# Organisation of African Unity/African Union Security Analysis
This is the repository for the data collection and analysis code used in my thesis, which was written for the Master of Letters (International Political Theory) at the University of St Andrews. 

## Analysing OAU/AU Security
Among the many ways to view security, Foucauldian security analysis is a promising one (for original concepts see Foucault 1969 and 1977; for adaptations see Huysmans 2002, Stritzel 2011, Neal 2020). The main take-aways from Foucauldian security are that security as a concept is a set of rules for relating policy fields, threats, things to protect, and actors who do the protecting. These rules are chosen by actors during an ongoing process of negotiations, and different sets of actors will define their own rules for relating security objects. When something is called a security problem by someone in a group, it is simultaneously added to the concept of security held by that group (though of course this can be challenged by other members of the group!)

My thesis analyses the archival documents stored on the African Union Common Repository website using a combination of qualitative and quantitative analysis. The code provided here is for the quantitative analysis, which included web-scraping, downloading and reading pdfs to get a score for how often selected security terms were mentioned, and statistical analysis. My aim was to understand, based on the discourse in documents that mentioned my security terms, what the underlying concept of security was at different points in time. A very brief overview of results will be added to this repository after my thesis is submitted. 

## Sections of this repository
The web-scraping code may prove useful for anyone looking to use the AU Common Repository documents for other data analysis, since it addresses several inconsistencies in the html on this site. The code constructing the dataset and the dataset itself are the most interesting contribution, since these allow for large-n discourse analysis of the OAU/AU, with the option to use different discourse-tracking techniques in the pdf-reading section. The statistical analysis code is only interesting for replicating my thesis results. 



