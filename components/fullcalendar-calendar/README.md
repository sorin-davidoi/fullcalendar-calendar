# fullcalendar-calendar

Web Component wrapper for [FullCalendar](http://fullcalendar.io/).

Documentation and demo available [here](http://sorin-davidoi.github.io/fullcalendar-calendar/components/fullcalendar-calendar/).

**Note**: This is a work-in-progress.

# Install

```
bower install --save fullcalendar-calendar
```

# Usage

```html
<link rel="import" href="fullcalendar-theme.html">
<link rel="import" href="fullcalendar-calendar.html">

<fullcalendar-calendar></fullcalendar-calendar>
```

`fullcalendar-calendar.html` includes all the required dependencies (jQuery, moment and FullCalendar). However, since these libraries do not provide HTML import files, the Javascript files are loaded directly. This may prove problematic if you use any of the libraries in other part of your project, since you will load them twice. If this is the case, use `fullcalendar-calendar-no-deps.html`, which includes just the WebComponent wrapper, without the dependencies. However, you must now load the dependencies yourself:

```html
<!-- The order is important, jquery and moment must come before fullcalendar -->
<script src='jquery/dist/jquery.min.js'></script>
<script src='moment/min/moment.min.js'></script>
<script src='fullcalendar/dist/fullcalendar.min.js'></script>

<link rel="import" href="fullcalendar-theme.html">
<link rel="import" href="fullcalendar-calendar-no-deps.html">
```

For all the options please consult the [documentation](http://sorin-davidoi.github.io/fullcalendar-calendar/components/fullcalendar-calendar/).
