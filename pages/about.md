---
title: About
layout: about
permalink: /about.html
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html %}

{% include feature/nav-menu.html sections="About the Collection;About the About Page" %}

## About the Collection
 

Beginning June 30, 2013, the day that nineteen Granite Mountain Hotshots died fighting the Yarnell Hill Fire, the fence outside Fire Station 7 became a place of tribute and mourning. In September, an amazing group of volunteers recognized the need to preserve the tangible outpouring of community grief and respect along the fence at Prescott Fire Station 7.  Led by Jan Monroe and Dottie Morris, the volunteers began to carefully remove t-shirts, flags, toys and artwork from the fence, photographing them and documenting details. Six months and 10,000 photographs later, Jan and Dottie identified the Arizona Memory Project as the perfect place to make these digital records available to the public, creating a kind of online museum about the Tribute Fence.

## About the About Page

TThe Tribute Fence Preservation Project (TFPP) and Prescott Public Library partnered with the Arizona State Library, Archives and Public Records to create an online digital collection of materials left in tribute for the Prescott Granite Mountain Hotshots.  This digital collection is available to the public as part of the Arizona Memory Project.

- Image --> `{% raw %}{% include feature/item-figure.html objectid="demo_001" width="25" %}{% endraw %}`

{% include feature/item-figure.html objectid="demo_001" width="25" %}

- PDF -- > `{% raw %}{% include feature/item-pdf-embed.html objectid="demo_002"  width="25" %}{% endraw %}`

{% include feature/item-pdf-embed.html objectid="demo_002" width="25" %}

- Video: `{% raw %}{% include feature/item-video-embed.html objectid="demo_004" %}{% endraw %}`

{% include feature/item-video-embed.html objectid="demo_004" %}

- Card -- > `{% raw %}{% include feature/card.html header="This is a Card" text="The card features an image from the collection as a cap" objectid="demo_004" width="25" centered=true %}{% endraw %}`

{% include feature/card.html header="This is a Card" text="The card features an image from the collection as a cap" objectid="demo_004" width="25" centered=true %}

- Buttons -- > `{% raw %}{% include feature/button.html text="Button Link to Somewhere" link="https://collectionbuilder.github.io/" color="success" %}{% endraw %}`

{% include feature/button.html text="Button Link to Somewhere" link="https://collectionbuilder.github.io/" color="success" centered=true %}
  
- Alerts -- > `{% raw %}{% include feature/alert.html text="this is an *alert* that 'warns' a user" color="warning" align="center" %}{% endraw %}`

{% include feature/alert.html text="This is an *alert* that 'warns' a user with centrally aligned text." color="warning" align="center"  %}

- Modals -- > `{% raw %}{% include feature/modal.html button="This is a modal using a 'primary' colored button to invite clicking" title="when clicked:" text="A Modal will pop out a box with some more information" color="primary"  %}{% endraw %}`

{% include feature/modal.html button="This is a modal using a 'primary' colored button to invite clicking" title="When clicked:" text="A Modal will pop out a box with some more information" color="primary"  %}

We hope this makes it easier for site builders to develop the collection AND add interesting and engaging contextual information.  
