---
wrapper_template: _layouts/docs.html
context:
  title: Slider | Implementation
  status: braindump
---
<!-----

You have some errors, warnings, or alerts. If you are using reckless mode, turn it off to see inline alerts.
\* ERRORs: 0
\* WARNINGs: 0
\* ALERTS: 3

Conversion time: 1.499 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

\* Docs to Markdown version 1.0β36
\* Tue May 14 2024 00:39:51 GMT-0700 (PDT)
\* Source doc: Slider spec
* This document has images: check for >>>>>  gd2md-html alert:  inline image link in generated source and store images to your server. NOTE: Images in exported zip file from Google Docs may not appear in  the same order as they do in your doc. Please check the images!


WARNING:
You have 3 H1 headings. You may want to use the "H1 -> H2" option to demote all headings by one level.

----->

# Slider (Component)

# Overview

A slider provides visual interaction for the user to make a selection from a specified range of values. The user can move the handle to select a value or enter it in the input field.

# Anatomy

![alt_text](/vanilla/templates/static/images/image3.png "image_tooltip")

# Usage

### When to use

* To let users select a value from a fixed range
* To let the user adjust settings or filters
* When an exac

  t value is not needed, but rather an approximate value.
* As a visual aid on infographics and/or graphics. 

### When not to use

* Avoid using a slider if an exact value is necessary, or if using, make the numeric input available.
* If the range is very wide it will be hard to select a specific value. Again, if using a slider, consider making the 

  numeric input available.
* Avoid using a slider for ranges that are very small.

## The look (Live demo box) \[Do not include on discourse post]

* Modifiers:

  * Label - yes/no
  * Range - ye

    s/no
  * Input - yes/no
* State:

  * Default
  * Disabled

## Behaviour

### Interaction

The user can interact with the slider by dragging the handle along the track or by clicking on a specific point in the track. When a numeric input is present, the user can interact with the slider by writing a specific value.

### Disabled

When the slider is disabled it will have a transparency of 50% and will not be interactable.

## Examples

#### Ubuntu.com

![alt_text](/vanilla/templates/static/images/image1.png "image_tooltip")

![alt_text](/vanilla/templates/static/images/image2.png "image_tooltip")
