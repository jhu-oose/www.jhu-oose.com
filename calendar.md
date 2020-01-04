---
# http://colorbrewer2.org/#type=qualitative&scheme=Paired&n=12
fullCalendar:
  eventSources:
    - color: "#1f78b4"
      events:
        - title: Lecture 0
          url: /lectures/0
          start: 2020-01-18
    - color: "#33a02c"
      events:
        - title: Assignment 0
          url: /assignments/0
          start: 2020-01-09
          end: 2020-01-15
    - color: "#e31a1c"
      events:
        - title: Assignment 0 Grace Period
          url: /policies#late-submissions
          start: 2020-01-05
          end: 2020-01-13
    - color: "#6a3d9a"
      events:
        - title: Lab 1
          url: /group-projects#laboratory-sessions
          start: 2020-01-08
    - color: "#b15928"
      events:
        - title: Iteration 0
          url: /iterations/0
          start: 2020-01-02
          end: 2020-01-19
    - color: "#ff7f00"
      events:
        - title: Labor Day
          start: 2020-09-03
  plugins:
    - dayGrid
  fixedWeekCount: false
  showNonCurrentDates: false
  validRange:
    start: 2020-01-01
    end: 2020-01-21
  aspectRatio: 0.8
---

# Calendar

**<small>⚠️</small>  Deadlines are at 11:45, which is 15 minutes before the class starts. This applies both to individual assignments and to group project iterations.**

For how to use the Grace Periods, see the [policy on Late Submissions](/policies#late-submissions).

For administrative matters, for example, for the last day to drop courses, refer to the [university’s academic calendar](https://studentaffairs.jhu.edu/registrar/wp-content/uploads/sites/23/2017/03/FINAL.academic-calendar-2019-2020.REVISED_4.29.2019.pdf).

# Spring 2020

<div data-calendar="2020-01-01"></div>

<script src="/fullcalendar-4.2.0/packages/core/main.min.js"></script>
<script src="/fullcalendar-4.2.0/packages/daygrid/main.min.js"></script>
<link rel="stylesheet" type="text/css" href="/fullcalendar-4.2.0/packages/core/main.min.css">
<link rel="stylesheet" type="text/css" href="/fullcalendar-4.2.0/packages/daygrid/main.min.css">
<script>
  document.querySelectorAll("[data-calendar]").forEach(element => {
    new FullCalendar.Calendar(element, {
      defaultDate: element.dataset.calendar,
      ...{{ page.fullCalendar | jsonify }}
    }).render();
  });
</script>
<style>
  [data-calendar] {
    border-radius: 3px;
    overflow: hidden;
  }
</style>
