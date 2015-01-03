snabbswitch-dashboard
=====================
_Experimental dashboard for snabbswitch project_

- Copyright (c) 2014-2015, LogicEditor <info@logiceditor.com>
- Copyright (c) 2014-2015, Alexander Gladysh <ag@logiceditor.com>
- Copyright (c) 2014-2015, Dmitry Potapov <dp@logiceditor.com>

See file `COPYRIGHT` for the license.

### Project structure

* *src/index.html* -- dashboard page, that shows:
    * snabbswitch network overview d3 graph,
    * snabbswitch app status tables,
    * processor utilization charts and
    * traffic charts,
* *src/js/app.js* -- main dashboard script:
    * defines paths and constants,
    * loads data from csvs defined,
    * updates data every N seconds,
    * extracts data for tables,
    * groups data for charts and
    * draws all that stuff,
* *src/js/d3.app.js* -- network overview d3 graph script,
* *src/data/app.csv* -- sample snabbswitch application data,
* *src/data/link.csv* -- sample snabbswitch link data,
* *src/css/style.css* -- various dashboard page styles,
* *src/css/d3.app.css* -- d3 graph styles.

Other scripts are third-party software, see `COPYRIGHT` for the licenses.
