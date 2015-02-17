# **Storytelling With Spatial Narratives and Mapping Tools**

The purpose of this short tutorial is to introduce the concept of a spatial narrative or the spatial stories described by [Michel de Certeau](https://github.com/vanhoesenj/MSFS15-Digital-Stories/raw/master/certeau.pdf).

You want to do your best to avoid your readers having this experience:

![](http://media.giphy.com/media/og1j2W8BkkaAw/giphy.gif) 

and instead, by contextualizing your content with an underlying spatial narrative, they should have this experience

![](http://media.giphy.com/media/1unWthRtNnzkA/giphy.gif) 


***
# **Digital Storytelling: Examples**

1. Invasion of America: [http://invasionofamerica.ehistory.org/](http://invasionofamerica.ehistory.org/) 
2. Visualizing U.S. Expansion: [https://vimeo.com/27376376](https://vimeo.com/27376376) 
3. Losing Ground:  [http://projects.propublica.org/louisiana/](http://projects.propublica.org/louisiana/) 
4. Twitter (Ferguson): [http://j-vh.me/1pdmR8t](http://j-vh.me/1pdmR8t)
5. Twitter (Ukraine): [http://j-vh.me/1yC0j56](http://j-vh.me/1yC0j56)
6. Twitter (Beyoncé): [http://j-vh.me/1yC0j56](http://j-vh.me/1yC0j56)
7. Twitter (Je Suis Charlie): [http://j-vh.me/1Axj1Pp](http://j-vh.me/1Axj1Pp)
7. Downside of the Boom: [http://j-vh.me/1AxgEw7](http://j-vh.me/1AxgEw7)
8. Sasquatch Sightings: [http://j-vh.me/1AxgLrl](http://j-vh.me/1AxgLrl)
9. A Geography of Geologic Lexicon: [https://flic.kr/p/qQcK7h](https://flic.kr/p/qQcK7h)
10. United States of Petroleum: [https://flic.kr/p/qaTtHR](https://flic.kr/p/qaTtHR)
11. Shale Bubble Map: [http://j-vh.me/1xWj6u2](http://j-vh.me/1xWj6u2)
12. Snowfall: [http://j-vh.me/10wdoA4](http://j-vh.me/10wdoA4)
13. Disasters in America: [http://j-vh.me/1Axivkq](http://j-vh.me/1Axivkq)
14. Hollow The Film: [http://hollowdocumentary.com/](http://hollowdocumentary.com/)


![](https://raw.githubusercontent.com/vanhoesenj/GDAL-VCGI/master/Images/geology.png)

****
## **USEFUL GDAL TOOLS (in no particular order)**
**Note**: not all of these utilities have screenshots or command line examples.
  
##### **1. Translate** ([gdal_translate](http://gdal.org/1.11/gdal_translate.html))
This is the Leatherman (I mean not all Swiss Army knives are actually multitools right?) of the GDAL library. This tool allows us to change the raster output format (i.e. - JPG, GeoTiff, etc), create a subset of the layer (i.e. - crop <-- seriously, crop not clip...), change the output size (outsize), extract and mask individual bands (`-b band`, `mask band`), and variety of other options described in the documentation.

![](https://raw.githubusercontent.com/vanhoesenj/GDAL-VCGI/master/Images/gdal_translate.png)

![](https://raw.githubusercontent.com/vanhoesenj/GDAL-VCGI/master/Images/gdal_clipper.png)