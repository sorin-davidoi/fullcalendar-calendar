# fullcalendar-calendar

Web Component wrapper for [FullCalendar](http://fullcalendar.io/).

Documentation and demo available [here](http://sorin-davidoi.github.io/fullcalendar-calendar/components/fullcalendar-calendar/).

# Install

```
bower install --save fullcalendar-calendar
```

Since `fullcalendar-calendar` is just a wrapper, you will also need to install FullCalendar and its dependencies:

```
bower install --save fullcalendar jquery moment
```

# Usage

Make sure you load all the required dependencies:

```html
<!-- The order is important, jquery and moment must come before fullcalendar -->
<script src='jquery/dist/jquery.min.js'></script>
<script src='moment/min/moment.min.js'></script>
<script src='fullcalendar/dist/fullcalendar.min.js'></script>

<!-- Optional -->
<link rel='stylesheet' href='fullcalendar/dist/fullcalendar.min.css'/>

<link rel="import" href="fullcalendar-calendar.html">
```

You can now use it:

```html
<fullcalendar-calendar></fullcalendar-calendar>
```

For all the options please consult the [documentation](http://sorin-davidoi.github.io/fullcalendar-calendar/components/fullcalendar-calendar/).
