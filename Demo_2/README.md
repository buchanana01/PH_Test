<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Mapping with Juncture"
       author="Ashley Buchanan"
       banner="https://iiif.juncture-digital.org/banner/?url=https://upload.wikimedia.org/wikipedia/commons/4/47/Bartholomeus_Johannes_van_Hove%2C_Het_Mauritshuis_te_Den_Haag.jpg" 
       layout="vertical">

### Domestication of Maize
Maize domestication is one of the greatest feats of artificial selection and evolution, wherein a weedy plant in Central Mexico was converted through human-mediated selection into the most productive crop in the world.
<param ve-map
       title="Approximate timing and location of maize domestication."
       center="12.684407961343284, -76.70109703556372"
       zoom="3"
       show-labels
       time-dimension
       time-interval="-8700/900"
       duration="P10000Y"
       max-zoom="5"
       date-format="YYYY"
       fps="3"
       fill="#5C6609"
       auto-play="true">
<param ve-map-layer geojson 
       url="/Demo_2/spread_of_maize.json">

### Adding an Image
_Apollo and Daphne_ is a life-sized Baroque marble sculpture by Italian artist Gian Lorenzo Bernini, executed between 1622 and 1625. Housed in the Galleria Borghese in Rome, the work depicts the climax of the story of Apollo and Daphne (Phoebus and Daphne) in Ovid's _Metamorphoses_.
<param ve-image 
       label="Apollo and Daphne" 
       description="sculpture by Gian Lorenzo Bernini"
       license="Creative Commons"                 url="https://upload.wikimedia.org/wikipedia/commons/9/94/%CE%91%CF%80%CF%8C%CE%BB%CE%BB%CF%89%CE%BD_%CE%BA%CE%B1%CE%B9_%CE%94%CE%AC%CF%86%CE%BD%CE%B7_4.jpg">    
      
       
### Sample visual essay
This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">

# Basic usage

## Image

_Girl with a Pearl Earring_ (Dutch: Meisje met de parel) is an oil painting by Dutch Golden Age painter Johannes Vermeer, 
dated c. 1665. Going by various names over the centuries, it became known by its present title towards the end of the 
20th century after the earring worn by the girl portrayed there.[^1]
<param ve-image 
       label="Girl with a Pearl Earring" 
       description="painting by Johannes Vermeer" 
       license="public domain" 
       url="https://upload.wikimedia.org/wikipedia/commons/0/0f/1665_Girl_with_a_Pearl_Earring.jpg">

## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various 
literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Wikipedia: Girl with a Pearl Earring](https://en.wikipedia.org/wiki/Girl_with_a_Pearl_Earring)
