# Frontend for dashboard v01
## Changes:
- Removed script from single user HEAD! feedback page and icons change
    * ```<script src="https://kit.fontawesome.com/e9f50f9a1c.js" crossorigin="anonymous"></script>```
    * ```<i class="fas fa-star"></i>``` changed to ```<i class="icon-star"></i>```
- Javascript in this version:
    * In public/js/main.js is small javascript code for opening and closing sidenav menu, as well code to automaticly close or open menu depwnding on viewport width.
    * In teams-average-charts & single-user pages there is similar javascript code at bottom in script tag:
        * teams-average-charts - on load event progress bar fill animation, numberOfChartBars is function that calculates number of charts for graph on resize it also should fire oon open/close menu.
        * In single-user same scripts as above but also script for graph slider/carousel on smaller viewports.
- Html comented code removed
- CSS code cleaned. Unececery code removed
***
## Changes 04.08.2020
- Pages added:
    * company-members, company-teams, company-admin
    * user-settings-general, user-setting-teams, user-settings-advanced
    * not everything properly linked to each other
- Modals added:
    * on index & average-charts page (should be added to other pages with same functionality):
        * follow new team modal - on follow a new team btn
        * new invitation modal - on get the mobile app TEMPORARY
        * create new team modal - on plus-circle icon, there is also second modal that is part 2 of create team dialog (its in html)
    * on teams-settings-general page:
        * link team to company modal - on last row link btn
    * on teams-settings-feedback page:
        * request feedback modal - on add new btn
    * on teams-settings-rights page:
        * new viewing rights modal - on upper add rights btn
        * new admin rights modal - on lower add rights btn
    * on teams-members page:
        * invite new members modal - on invite new member btn
    * on company-members company-teams company-admin pages:
        * register new company modal - on register a new company btn

### NOTES:
Sidenav menu is different on company pages, 1 more icon added in sidebar for company pages!
### TO DO! 
Link second create new team modal or integrate in first. FIND SOLUTION!
Link all pages and make modals work on all pages with that functionality.
 
***