# ReadMe

I created this module so that I could have a comprehensive but simple breadcrumbs block to place on the front-side of a Drupal site I'm working on. I needed something that worked on the term pages I created with views, as well as nodes and top-level section pages without fracturing the data into several different blocks, views or otherwise.

This Drupal module checks the path and builds breadcrumbs based on the path and the page title. The path checking most likely could be optimized but I'm still a PHP newb and am unsure how to do it.

If you wish to use this code, make sure that you update the path variables to what your site's needs. However, the bigger the Drupal site (re: more pages/deeper hierarchy), the more unwieldy this module will become.

Also included are two sample view pages that I used to build the term listing pages for Blog terms and Portfolio terms. I haven't finished yet with the display so there might be some iffy things there. However, the important parts are the contextual filters and how I passed the argument into the page title. These views were created so that I could leverage taxonomy menu's custom paths. You can view the tutorial I wrote up on how to do that at https://www.drupal.org/node/2488874.