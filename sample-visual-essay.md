<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Mandrake" 
       banner="https://iiif.juncture-digital.org/banner/?url=https://commons.wikimedia.org/wiki/File:NaplesDioscuridesMandrake.jpg#/media/File:NaplesDioscuridesMandrake.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q212742"> <!-- genus Mandragora -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# Sample visual essay

This is a sample visual essay demonstrating a few key features of a visual essay.  Complete [Documentation](https://juncture-digital.org/docs) and helpful [examples](https://juncture-digital.org/examples) are available on the [Juncture site](https://juncture-digital.org).
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">

# Basic usage

## Image

A mandrake is the root of a plant, historically derived either from plants of the genus Mandragora found in the Mediterranean region, or from other species, such as Bryonia alba, the English mandrake, which have similar properties. The plants from which the root is obtained are also called "mandrakes". Mediterranean mandrakes are perennial herbaceous plants with ovate leaves arranged in a rosette, a thick upright root, often branched, and bell-shaped flowers followed by yellow or orange berries. They have been placed in different species by different authors. They are highly variable perennial herbaceous plants with long thick roots (often branched) and almost no stem. The leaves are borne in a basal rosette, and are variable in size and shape, with a maximum length of 45 cm (18 in). They are usually either elliptical in shape or wider towards the end (obovate), with varying degrees of hairiness.

Because mandrakes contain deliriant hallucinogenic tropane alkaloids and the shape of their roots often resembles human figures, they have been associated with a variety of superstitious practices throughout history. They have long been used in magic rituals, today also in contemporary pagan traditions such as Wicca and Odinism.

The English name of the plant derives from Latin mandragora through French main-de-gloire.[^1]
<param ve-image 
       label="Girl with a Pearl Earring" 
       description="painting by Johannes Vermeer" 
       license="public domain" 
       url="https://upload.wikimedia.org/wikipedia/commons/0/0f/1665_Girl_with_a_Pearl_Earring.jpg">

## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Wikipedia: Mandrake](https://en.wikipedia.org/wiki/Mandrake)
