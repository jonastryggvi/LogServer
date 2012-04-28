This was an effort to create a more lightweight web interface to Graylog2, that would preferable not need any server side logic as everything should really be accerssible via ElasticSearch's RESTful API

It is based on Twitters boostrap, and works if you have elasticsearch on your box.. else you have to change the ES url configured in index.html

# My TODO list.
* Sidebar for every host that has logged last hour
 * Add buttons to toggle logs from specific hosts
* Autoupdate log table
 * Pause the autoupdate, to allow analysis
 * Pagination
 * Endless page
* Remove log filters like tags on http://dan.doezema.com/wp-content/uploads/2012/03/tbrbf2.png
* popover formatting
 * Adding link to codefiles see (https://gist.github.com/2034192)
* Permalinks

# Exploration 
* See if we can harvest some of the exception aggrigation from https://github.com/dcramer/sentry

