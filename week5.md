# Reflection 3/8/21

My reflection this week is on a [soil visualization](https://soilgrids.org/)
from the Data is Plural email. It's a map of the world which
allows the user to zoom in and out, pan, and select attributes
to be displayed using color and luminance. 

[soil map](img/soil%20chart.JPG)

The data is tabular data with a lot of attributes sampled
discretely across the continuous space of the earth's surface. 
The task abstraction is mainly exploring: the user can
locate, browse, and explore the patterns of different soil characteristics across
the globe. The user selects which characteristic to look at using
the menus on the left of the vis. The data is encoded using color. In
the case above with soil classes color hue is used; most of the other
characteristics are encoded using luminance across a single hue. 
This is easy to understand, but some of the color choices could be
more visually appealing - for example, the greens are more interesting
to look at and discern shades than the browns. The data is
shown on the provided spatial positions of the globe, which 
makes sense because the goal is to see how soil looks across the
world and in specific parts of the world. Zoom and pan work well
and a label tells you how far zoomed in you are. There's a limit to 
how far in and out you can zoom, and you can't pan away from the 
map up or down, but you can pan into blackness to the right and left.
Adding a border on the sides or allowing the world to scroll in a 
circular fashion would prevent users getting lost off the edge
of the earth. The left menu could also be shrunk slightly so that
all menu options are visible next to the map (instead of having a
few menu options off the bottom of the screen, where the viewer doesn't
know they exist unless they go looking). The vis has a nice
collapsible legend whose title changes to show which characteristic
the viewer is currently looking at. One attribute the user can view
is the actual soil profiles that were taken. It's cool to see
these lcoations and the actual data, but currently the user
can only 'explore' the data from one selected soil sample at once
in the detail pane. Adding any kind of linked view that allows
the user to see the data for multiple points or in a different vis
for a given characteristic (like a historgram) would be fun. 
