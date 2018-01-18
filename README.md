# Small-multiples

## Definition and utility :
Small multiples go by many names, including Trellis Chart, Lattice Chart, Grid Chart, and Panel Chart.
Small multiples are sets of charts of the same type, with the same scale, presented together at a small size and with minimal detail, usually in a grid of some kind.
They are a visualization concept introduced by Edward Tufte. He described them as:
"Illustrations of postage-stamp size are indexed by category or a label, sequenced over time like the frames of a movie, or ordered by a quantitative variable not used in the single image itself."
In other words, small multiples use the same basic graphic or chart to display difference slices of a data set. Small multiples can show rich, multi-dimensional data without trying to cram all that information into a single, overly-complex chart. 
Here is a simple example showing the use of small multiples. The following animated chart shows the evolution of populations in some selected countries : [1]
<table border="0">
  <tr>
    <td>
      <img src="img/img1.gif" style="width: 100px;">
    </td>
  </tr>
  <tr>
    <td align="center" bgcolor="EFEFEF">
      Animated representation for population growth [1]
    </td>
  </tr>
</table>

This GIF image has 54 separate frames. It's not particularly practical to create a small multiple graphic with 54 separate charts, but we can still get a good idea of the changes taking place by "sampling" the data every six years:
<table border="0">
  <tr>
    <td>
      <img src="img/img2.png" style="width: 100px;">
    </td>
  </tr>
  <tr>
    <td align="center" bgcolor="EFEFEF">
      Small multiple chart of population growth on each 6 years[2]
    </td>
  </tr>
</table>

This way, you can actually browse the small multiple layout at your leisure. You can clearly see the rapid rise in the population of Mexico, for instance. You can see that the population roughly doubled from just over 50 million in 1972 to a little over 100 million by 2002. To get his kind of information from the GIF you have to keep details in working memory while you wait for the frames to progress.
This show the utility of **small multiple charts**.


##Historical examples 

### 1886 : Horse in motion 

Some of the earliest known examples of this type of visualization include the photographic series Horse In Motion by Eadweard Muybridge, around 1886, and Francis Amasa Walker's chart of citizen's occupations in census year 1870 appearing in the Statistical Atlas of the United States. 
<table border="0">
  <tr>
    <td>
      <img src="img/img3.jpg" style="width: 100px;">
    </td>
  </tr>
  <tr>
    <td align="center" bgcolor="EFEFEF">
      Small multiple chart of a horse's motion[3]
    </td>
  </tr>
</table>
Muybridge's work not only proved for the first time that all four of a horse's hooves left the ground during gallop (see upper central plates), but it also broke new ground in terms of artistic expression and became foundational to the development of the motion picture. Muybridge went on to produce many more examples of small multiples showing animal locomotion through the medium of stop-motion photography, including boys playing leapfrog and a bison cantering. [2]

### 1874 : Statistical Atlas of the United States

This graphic is innovative in its use of both a treemap display and a latticed layout of small multiples. Additional examples appearing in the [Atlas](https://fraser.stlouisfed.org/scribd/?title_id=64&filepath=/docs/publications/stat1870/Stat_Atlas1870.pdf) include side-by-side geographic maps showing the changes in population over time, as well as tiled mosaic charts showing population demographic breakdowns, and diverging bar graphs showing deaths broken down by age and gender, tiled by state. [2]



<table border="0">
  <tr>
    <td>
      <img src="img/img4.jpg" style="width: 100px;">
    </td>
  </tr>
  <tr>
    <td align="center" bgcolor="EFEFEF">
      Persons with gainful occupations and attending school, Walker (1874)[4]
    </td>
  </tr>
</table>

## Recent examples : NASA 

The graphic below from NASA's Scientific Visualization Studio showing the variation in ice extent at the North Pole encodes the year in the horizontal direction (from 1979 to 2014) and the month in the vertical direction. Each column shows how the ice extent changed over the course of the year while each row shows the long term changes for a particular month. [3]

<table border="0">
  <tr>
    <td>
      <img src="img/img5.jpg" style="width: 100px;">
    </td>
  </tr>
  <tr>
    <td align="center" bgcolor="EFEFEF">
      the variation in ice extent at the North Pole 1979-2014[4]
    </td>
  </tr>
</table>

You can see it more clearly in [full resolution](https://svs.gsfc.nasa.gov/vis/a000000/a004200/a004204/arctic_ice_extent_12264x6016.tif).

## Comments 

I find that small multiple charts are very useful when it comes to analysing the change and the motion of data in many directions on dimensions. These charts allow us to visualize a big amount of data in a way that shows the evolution and the change of statistical features of this data. Therefore, it makes the meanings of the chart more obvious and easy to visualize.

## Resources : 

[1] An Introduction to Small Multiples - https://www.infragistics.com/community/blogs/b/tim_brock/posts/an-introduction-to-small-multiples
[2] Wikipedia - https://en.wikipedia.org/wiki/Small_multiple
[3] NASA - Scientific Visualization Studio : https://svs.gsfc.nasa.gov/cgi-bin/details.cgi?aid=4204



