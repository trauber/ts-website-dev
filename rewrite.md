# Web Site Rewrite Project

We're kicking this off at the end of May, beginning of June. We'll assign each page to its appropriate group/person and Rich will update the site pages with the contributed content.

2020-05-27T11-04:00 - Sent e-mail to Jo for assignment suggestions. Sent my list.

## Menu Assignments Plantuml Wireframe

![](https://www.plantuml.com/plantuml/svg/dLLDRzim3BttLmWOi1rssJaOaWPkWA9TLY1EKUmeoqnCH9OoYlBW3Vlle_CnnEtKsjE1Dc2-H_BHfAu3Q-AWBLyfERyELfxhqukSZv-DjvucdhJRmdHU-CZgCLmud3ss1E2cImm1lLCvQuOQ7AlJvy96WTUjUgzMFa2I8FEEjUbYZ4K-LVv3K6B7XwnhP0OO4B8lHnQ9kXeNZTYqA9csu4fDP_ftcyqdETEEUw9-0Enig-A-5CcI729egqGS1uQXx2MwfdzaU4JTnLAZqJttsMoMSb_ZRXUTUh2wVWNoic64HMHf--YUBP5_Dfu71xlnJaHwkvnJVvuyXGhtQL616ZIW5epV8_0pvXLor5Rz_JqcwaOtMBx55aQIz5DUbD7eJijac1LOtAB765HkAkzjBzvIaq6T17-D583Q_q1AdpT8zI4tbLaTmXZql8nMvkHSN5yYNHIOH7x1WhHaV8d8Ax0MshH4Hz4l8PtgwK6U6yO66I4zn3a61XBLocVz3UcgxtM9zMlJrtT_pByDzbs2assNsLZqq_554lB05T014eOkXCoYsQbR850RJsfTeMnOsLSI-bRlz-3GRSFmjVRxwcYlPHrsryuV)


## Mermaid Gantt



[![](https://mermaid.ink/img/eyJjb2RlIjoiZ2FudHRcbiAgICB0aXRsZSBBIEdhbnR0IERpYWdyYW1cbiAgICBkYXRlRm9ybWF0ICBZWVlZLU1NLUREXG4gICAgc2VjdGlvbiBTZWN0aW9uXG4gICAgQSB0YXNrICAgICAgICAgICA6YTEsIDIwMTQtMDEtMDEsIDMwZFxuICAgIEFub3RoZXIgdGFzayAgICAgOmFmdGVyIGExICAsIDIwZFxuICAgIHNlY3Rpb24gQW5vdGhlclxuICAgIFRhc2sgaW4gc2VjICAgICAgOjIwMTQtMDEtMTIgICwgMTJkXG4gICAgYW5vdGhlciB0YXNrICAgICAgOiAyNGQiLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOmZhbHNlfQ)](https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiZ2FudHRcbiAgICB0aXRsZSBBIEdhbnR0IERpYWdyYW1cbiAgICBkYXRlRm9ybWF0ICBZWVlZLU1NLUREXG4gICAgc2VjdGlvbiBTZWN0aW9uXG4gICAgQSB0YXNrICAgICAgICAgICA6YTEsIDIwMTQtMDEtMDEsIDMwZFxuICAgIEFub3RoZXIgdGFzayAgICAgOmFmdGVyIGExICAsIDIwZFxuICAgIHNlY3Rpb24gQW5vdGhlclxuICAgIFRhc2sgaW4gc2VjICAgICAgOjIwMTQtMDEtMTIgICwgMTJkXG4gICAgYW5vdGhlciB0YXNrICAgICAgOiAyNGQiLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOmZhbHNlfQ)


## Sources

### Plantuml Menu

```plantuml

@startsalt
    {
      {T
         +<color:orange>About Us
         ++<color:green>Mission Statement <color:blue>Amy & Rose
         ++<color:green>Contact Us <color:blue>Amy & Rose
         ++<color:green>Who's Who <color:blue>Amy & Rose
         ++<color:green>Committees <color:blue>Amy & Rose
         +<color:orange>Current Events
         ++<color:green>Calendar <color:#ff0000>Rose: weekly update
         ++<color:green>Stay Connected <color:blue>Tre
         +<color:green>Judaica <color:blue>???
         +<color:green>Tikkun Olam <color:blue>???
         ++<color:green>Contributions <color:blue>Amy & Rose
         ++<color:green>Mitzvot <color:blue>???
         ++<color:green>Donate <color:blue>???
         +<color:orange>Worship
         ++<color:green>Service Etiquette <color:blue>Ritual Committee: David
         ++<color:green>Services <color:blue>Ritual Committee: David
         +<color:orange>Education
         ++<color:green>Religioius School <color:blue>Marcia
         ++<color:green>Nursery School <color:blue>Marcia
         ++<color:green>Confirmation Class <color:blue>Marcia
         ++<color:green>Adult Education <color:blue>Rabbi
         ++<color:green>Library <color:blue>Shelley
         ++<color:green>Ritual <color:blue>Davie
         +<color:orange>Activities
         ++<color:green>Sisterhood <color:blue>Risa
         ++<color:green>Kadima <color:blue>???
         ++<color:green>USY <color:blue>???
         ++<color:green>Men's Club <color:blue>Rob
         ++<color:green>Other Clubs <color:blue>???
         +<color:green>Click Here for This Week's Happenings <color:#ff0000>Rose: weekly update
      }
    }
@endsalt

```
### Mermaid Gantt

```mermaid
gantt
    title A Gantt Diagram
    dateFormat  YYYY-MM-DD
    section Section
    A task           :a1, 2014-01-01, 30d
    Another task     :after a1  , 20d
    section Another
    Task in sec      :2014-01-12  , 12d
    another task      : 24d
```

## Resources

* [PlantText UML Editor](https://www.planttext.com/)
* [Mermaid live editor](https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiZ2FudHRcbiAgICB0aXRsZSBBIEdhbnR0IERpYWdyYW1cbiAgICBkYXRlRm9ybWF0ICBZWVlZLU1NLUREXG4gICAgc2VjdGlvbiBTZWN0aW9uXG4gICAgQSB0YXNrICAgICAgICAgICA6YTEsIDIwMTQtMDEtMDEsIDMwZFxuICAgIEFub3RoZXIgdGFzayAgICAgOmFmdGVyIGExICAsIDIwZFxuICAgIHNlY3Rpb24gQW5vdGhlclxuICAgIFRhc2sgaW4gc2VjICAgICAgOjIwMTQtMDEtMTIgICwgMTJkXG4gICAgYW5vdGhlciB0YXNrICAgICAgOiAyNGQiLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9fQ)