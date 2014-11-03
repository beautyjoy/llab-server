# llab-server

This is a repo for a llab-server idea I've been throwing around.

This server will be based on Express and nodeJS.
* Matches the current llab feature set and setup
* easy deployment to Heroku
* URL scheme:
      *  /  - main page
      * /courses - course listing page
      * /courses/[COURSE]/ - list the topics in a course
      * /courses/[course]/[topic-name]/ - the 'topic' page with a list of activities
      * /courses/[course]/[topic]/[page] - an individual curriculum page

* The [course], [topic], [page] should be readable "slugs" or optionally ids.
    * (Numeric IDs are particularly nice for saying 'page X' within a lab.)