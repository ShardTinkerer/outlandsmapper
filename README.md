# Outlands Mapper

Download at Ultimamapper.com

go C:\Users\USER\Documents\Ultima Mapper

DELETE the marker folder, replace them with the one included

OVERWRITE the maps & icons folder


---------------------------------------------------------

EXAMPLE MARKER FILE:

```
<?xml version="1.0" encoding="UTF-8"?><Pack Name="Bodies of Water" Revision="0">

<Marker Name="Example Body Of Water" X="2500" Y="42" Icon="TERRAIN" Facet="0"/>

</Pack>
```

The easiest way I have found to edit them and keep the formating as well as making it easier to collaborate would be to edit the marker file itself rather than adding it using mapper, for example if i wanted to add an additional marker it would then look like this

```
<?xml version="1.0" encoding="UTF-8"?><Pack Name="Bodies of Water" Revision="0">

<Marker Name="Example Body Of Water" X="2500" Y="42" Icon="TERRAIN" Facet="0"/>
<Marker Name="Example Body Of Water 2" X="2500" Y="42" Icon="TERRAIN" Facet="0"/>

</Pack>
```
