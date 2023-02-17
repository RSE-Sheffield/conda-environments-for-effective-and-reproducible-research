---
name: Scheduling courses with Eventbrite
about: Instructions for setting up materials ready for next session. To be completed by lead instructor
title: Scheduling courses with Eventbrite on [DATE-OR-SESSION-DESCRIPTION] for [INSTRUCTOR-NAME]
labels: session-setup
assignees: ''

---

The lead instructor needs to schedule events on [Eventbrite](https://www.eventbrite.com) using the [RSE
Sheffield](https://www.eventbrite.co.uk/o/rse-sheffield-29660305889) organisation. If you have not already been setup as
an administrator for this you should request to be included by another team member (see [RSEs
Handbook](https://github.com/RSE-Sheffield/rses-handbook/blob/master/pages/eventbrite.Rmd) for further details).

**NB** - The easiest approach is to copy an existing event. From the page listing events select **Past** and click on
the three dots to the right of a past event and select `Copy Event`. Edit the title to remove `Copy of` and update the
dates and times.


## Basic Info

The following fields should be entered into each field on the **Basic Info** page.

| Field               | Value                                                                     |
|:--------------------|---------------------------------------------------------------------------|
| Event Title         | Introduction to Conda for (Data) Scientists                               |
| Organiser           | RSE Sheffield                                                             |
| Type                | Class, Training, or Workshop                                              |
| Category            | Science & Technology                                                      |
| Tags                | conda, python, research, computing, virtual_environments, reproducibility |
| Location            | Online Event (unless otherwise)                                           |
| Date and Time       | Single Event if running over one day, otherwise Recurring                 |
| Event Starts        | Start Date/Time (always Single Event), start is usually 09:30             |
| Event Ends          | End Date/Time if one day finish is usually 13:30.                         |
| Time Zone           | United Kingdom Time                                                       |
| Event Page Language | English (UK)                                                              |



## Schedule

If the course is split over two days then you should still have selected **Single Event** as selecting repeating events
results in people being able to register for individual sessions rather than signing up once for both. This is a current
short-coming of Eventbrite.

## Details

A banner can be added to the event, some sample images are under the `resources/` directory of this repository, but if
you have copied a past event this will already be in place.

The following fields should be entered into each field on the **Details** page (they can be copy and pasted from a past
event).


### Summary


> This is an intermediate course, teaching the use of Conda virtual environments for reproducible research environments.

### Description

> How can we undertake research work in a consistent and reproducible computing environment?
> This is an intermediate course, teaching the use of Conda virtual environments for reproducible research envuironments
> when using Python for research and data analysis. These skills are essential for collaborative research teams.
> This event is for University of Sheffield researchers and research students only. Please register with an @shef.ac.uk
> or @sheffield.ac.uk email address to ensure your ticket request is accepted.
>
> **Prerequisite skills**:
> - Basic shell commands (bash/zsh (Linux/MacOS); Powershell (Windows)).
> - Some Python programming experience.
>
> ### Learning Objectives
> - Understand what Conda is and why it is useful for managing packages and environments in research workflows.
> - How to create, activate and delete Conda environments.
> - How to install and manage packages in Conda environments.
> - What Conda channels and packages are and how to use them.
> - How to use pip in Conda environments.
> - How to share your Conda environment.
> - How to manage packages that have GPU dependencies.
>
>
> ### Attendance to our Courses
>
> We are delighted to be able to make free at point of use training available to the research community, to enable
> better software and more open, reproducible research. However, free at point of use training is not free. The cost of
> a course can easily run to thousands of pounds, if preparation costs are taken into account.

>
> If you sign up for a course, please make sure you either attend or cancel your booking. Bookings can usually be
> cancelled using eventbrite.com or, failing that, by emailing rse@sheffield.ac.uk.
>
> Running courses that are not fully attended wastes our funding (which is provided by taxpayers, charities and
> students, amongst others) and reduces our collective capacity to improve research outputs and researcher experiences.
>
> Persistent failure to attend booked courses might result in you being excluded from future training opportunities.
>
> If we can do anything to make our courses more accessible for you to attend, please send suggestions to
> rse@sheffield.ac.uk; the Sheffield RSE Team are committed to making our training as accessible to a wide range of
> researchers as possible.


## Online Event Page

We do not use this section as events are setup via Blackboard. You should click on **Page Settings** and toggle the
**Atendee Event Page** to disable.

## Tickets

Set the following fields under the **Tickets** section

| Field                     | Value                      |
|:--------------------------|----------------------------|
|                           | Free                       |
| Name                      | General Admission          |
| Available Quantity        | 20                         |
| Ticket Sales End          | 1 Hour Before Event Starts |
| Description               | Not Required               |
| Visibility                | Visible                    |
| Tickets Per Order Minimum | 1                          |
| Tickets Per Order Maximum | 1                          |
| Sales Channel             | Online Only                |

## Publish

The event can be published immediately or scheduled for publishing at a specific date/time.
