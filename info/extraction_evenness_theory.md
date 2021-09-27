---
layout: default
title: Extraction evenness: Theory
parent: Information
nav_order: 5
---

# Extraction evenness in espresso: Theory

_Extraction_ is the process of dissolving soluble compounds from ground coffee beans into the extraction medium a.k.a water. This is usually measured as a percentage of the total solid coffee that dissolves in water and ends up in the cup and is referred to as _extraction yield_. 

"Channeling" is often cited as one of the main reasons for poor shot quality and a lot of emphasis is put on puck prep to reduce the effect of channeling. If you've ever tasted a shot that obviously channeled, you'll know that it tastes weird, with some bitterness and astringency while simultaneously also having some unpleasant sourness. This is usually understood to result from a combination of parts of the puck that were very highly extracted and parts that were poorly extracted. It is quite instructive to think about the broader concept of _extraction evenness_, of which channeling is an example and will be more concretely defined below.

## Common types of extraction unevenness

An even extraction is very simple to understand. It is when every coffee particle in the puck is equally extracted. Practically, this is never strictly true but one may say a puck was evenly extracted if the variance in the extraction yields of the spatially separate parts of the puck is low. The average extraction yield of a shot can be measured using a refractometer that measures the mass fraction of dissolved solids in the cup. However, there isn't a clear way to measure _localized extraction yield_. Thinking about common types of extraction unevenness can help in assessing specific issues and trying to address them.

Extraction unevenness can be broadly categorized into two groups based on the dominant orientation of extraction gradients:
1. Axial unevenness
2. Lateral unevenness

These are defined below.

### Axial unevenness

Axial unevenness is when the localized extraction yield varies dominantly from the top to the bottom of the puck. The dominant direction of the gradient of localized extraction yield is aligned with the axial axis of the puck (all pucks are cylindrical, hopefully!). The schematic below depicts this pictorially with darker areas having lower extraction yield and lighter areas having higher extraction yield.

![Axial unevenness](/images/axial_unevenness.svg){:height="50%" width="50%"}
*Schematic showing axial unevenness. Darker areas depict lower local extraction yield and lighter areas depict higher local extraction yield*

The most probable reason for axial unevenness is that the top of the puck sees water with no dissolved coffee solubles while the bottom sees a significant amount of dissolved solids. This will cause the top and the bottom to extract at different rates. Axial unevenness can also stem from pre-infusion. A fast initial fill rate in a pump machine or a higher pre-infusion pressure in a lever machine will cause the puck to saturate more evenly since the time delay between the top and bottom of the puck seeing water is lower. A slayer style slow flow rate pre-infusion will have a much larger time delay between the top and the bottom of the puck getting saturated with water.

### Lateral unevenness

Lateral unevenness is variation in local extraction yields along a cross section of a puck. In this case, the dominant direction of the gradient of localized extraction yield is orthogonal to the axial axis of the puck. The schematic below shows shows this visually.

![Lateral unevenness](/images/lateral_unevenness.svg){:height="50%" width="50%"}
*Schematic showing lateral unevenness. Darker areas depict lower local extraction yield and lighter areas depict higher local extraction yield*

Within this classification, we can further think about two common types of lateral unevenness.

#### Channeling

Channeling is the most commonly discussed type of lateral unevenness. Channeling is when parts of the puck offer lower resistance and this causes a flow rate variation across the cross section of a puck.  The image above of lateral unevenness is representative of channeling where there are localized regions that are under or over extracted compared to the puck average.

The fundamental reason for channeling is largely unknown. One suspicion (even if only by the author) is that it is a manifestation of viscous flow instabilities. If you are interested in learning more about this topic, the Saffman-Taylor instability or viscous fingering seems very applicable here.

#### Edge underextraction

Another common form of lateral unevenness is edge underextraction. This is when the outer edge of the puck bottom is underextracted compared to the center. The schematic below depicts this.

![Edge underextraction](/images/edge_underextraction.svg){:height="50%" width="50%"}
*Schematic showing edge underextraction. Darker areas depict lower local extraction yield and lighter areas depict higher local extraction yield*

Edge underextraction stems from typical basket designs where holes of the basket do not go all the way to the edge. At the bottom of the puck at the edge, there has to be some lateral flow in order for the liquid to exit the basket (since there aren't any holes at the edge). This causes a radial pressure gradient and a reduction of flow along the edge of the basket causing the edge to be extracted lower than the center. This is usually a concern for most basket designs. It is also usually much more prevalent in slower flowing shots with a finer grind than in faster flowing turbo shots.

## Is evenness of extraction a worthy goal?

This is a bit of a subjective question and so the answer, as is for many questions of this ilk, is _it depends_. Even extractions are, by construction, more repeatable and consistent since there isn't any room for extraction variation patterns to shift from shot to shot. So from this point of view, evenness of extraction is a worthy goal. It also makes higher average extraction yields accessible. In some cases, it might be desirable to have some predictable unevenness of extraction or _controlled complexity_. However, this is much harder to achieve if you are not able to consistently get even extractions before changing some parameters to get uneven but repeatable extractions.

Extraction evenness opens up inaccessible regimes of extraction and makes shots more repeatable and controllable, so give it a shot and see how you like it.