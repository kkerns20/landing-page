# Planning Document #
for The Odin Project's Landing Page

*This should showcase a working understanding of creating a page in HTML and styling with CSS*

## Sections ##
I'll attempt to name every flexbox container and basic outlines from what I see from the full design and colors &fonts pics as an outline


### body ###
Initialize 1st flexbox

### Global-content-wrapper ###
I need a container for the entire page. ID named
  - `flex: 1`

### Nav Bar ###
**Goals**
> I want the header bar stationary and atop the webpage throughout the scroll.
1. Need a container for the header
  - Name its class navbar
  - for the navbar, it looks like I need two more containers
    - One for the logo -> navbar-brand
    - One for the links -> navbar-nav
      - unorderlist for links
        - `<li>` as `class="nav-item"`
        - `<a>` as `class="nav-links"`
