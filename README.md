LibGuides Customizations
========================

Customizations for the Harvard Library implementation of LibGuides CMS. 

Base styles
-----------

Most customizations are applied to the system-wide Look & Feel. 

- **js-css.html**: Contains links to basic Harvard Library styles and custom CSS. This file is copied & pasted into the *Custom JS/CSS Code* section. 
- **header.html**: Contains HTML for the Harvard Library navbar in the Header. This file is copied & pasted into the *Custom Header Code* section.
- **footer.html**: Contains javascript code that moves a few elements around on the page, implements the subject menus, and enables some custom Google Analytics tracking. This file is copied & pasted into the *Custom Footer Code* section. 

Home Page
---------

The Harvard Library Research Guides home page uses a [custom guide](http://guides.library.harvard.edu/aecontent.php?pid=488882&sid=4009347). 

- **guidesbysubject.html**: Contains HTML for the top level subjects and API calls for the guides assigned to each subject.
- **guidesbycourse.html**: Contains a single API call to retrieve guides tagged with *course_guides*. 	
- **howtoguides.html**: Contains a single API call to retrieve guides tagged with *how_to*.
- **guidesbylibrary.html**: Contains HTML for each Library and API calls for the guides owned by each library. 

Other
-----

- **libguides.xml**: Contains configuration details for the Feedback form
- **README.md**: this file
