## Feature *Includes* Bonanza page

Check all the includes. Steal Code! 

### Image Options

#### Image from Collection (auto caption)

{% include feature/image.html objectid="demo_001" width="75" %}

Example Code --> `{% raw %}{% include feature/image.html objectid="demo_001" width="75" %}{% endraw %}`


#### Image from Collection (with a caption)

{% include feature/image.html objectid="demo_001" width="75" caption="an image" %}

Example Code --> `{% raw %}{% include feature/image.html objectid="demo_001" width="75" caption="an image" %}{% endraw %}`


#### Multiple Images from the Collection (auto caption)

{% include feature/image.html objectid="demo_001;demo_004;demo_005"  %}

Example Code --> `{% raw %}{% include feature/image.html objectid="demo_001;demo_004;demo_005"  %}{% endraw %}`


#### Multiple Images from the Collection (with captions)

{% include feature/image.html objectid="demo_001;demo_004;demo_005" width="75" caption="demo1;nother" %}

Example Code --> `{% raw %}{% include feature/image.html objectid="demo_001;demo_004;demo_005" width="75" caption="demo1;nother" %}{% endraw %}`


#### External Image (without a caption)

{% include feature/image.html objectid="https://www.lib.uidaho.edu/collectionbuilder/demo-objects/mg101_b6_photographs_01.jpg" width="75" alt="Frank B. Robinson at the Organ" %}

Example Code --> `{% raw %}{% include feature/image.html objectid="https://www.lib.uidaho.edu/collectionbuilder/demo-objects/mg101_b6_photographs_01.jpg" width="75" alt="Frank B. Robinson at the Organ" %}{% endraw %}`


#### External Image (with a caption)

{% include feature/image.html objectid="https://www.lib.uidaho.edu/collectionbuilder/demo-objects/mg101_b6_photographs_01.jpg" width="75" alt="Frank B. Robinson at the Organ" caption="This guy is good!"%}

Example Code --> `{% raw %}{% include feature/image.html objectid="https://www.lib.uidaho.edu/collectionbuilder/demo-objects/mg101_b6_photographs_01.jpg" width="75" alt="Frank B. Robinson at the Organ" caption="This guy is good!"%}{% endraw %}`


#### Multiple External Images (with captions and a link)

{% include feature/image.html objectid="https://www.lib.uidaho.edu/collectionbuilder/demo-objects/mg101_b6_photographs_01.jpg;https://www.lib.uidaho.edu/collectionbuilder/demo-objects/mg101_b6_psychiana_photographs_010.jpg" caption="this guy!;(was nothing without these women!)" link="https://www.lib.uidaho.edu/digital/psychiana/items/psychiana519.html;https://www.lib.uidaho.edu/digital/psychiana/items/psychiana547.html" alt="Frank B. Robinson at the Organ;Women staff members of Psychiana lined up outside the Psychiana headquarters" %}

Example Code --> `{% raw %}{% include feature/image.html objectid="https://www.lib.uidaho.edu/collectionbuilder/demo-objects/mg101_b6_photographs_01.jpg;https://www.lib.uidaho.edu/collectionbuilder/demo-objects/mg101_b6_psychiana_photographs_010.jpg" caption="this guy!;(was nothing without these women!)" link="https://www.lib.uidaho.edu/digital/psychiana/items/psychiana519.html;https://www.lib.uidaho.edu/digital/psychiana/items/psychiana547.html" alt="Frank B. Robinson at the Organ;Women staff members of Psychiana lined up outside the Psychiana headquarters" %}{% endraw %}`

#### Cloud Include

{% include feature/cloud.html fields="subject" min="1" background="dark" button="outline-warning" %}

Example Code --> `{% raw %}{% include feature/cloud.html fields="subject" min="1" background="dark" button="outline-warning"  %}{% endraw %}`


#### TimelineJS

{% include feature/timelinejs.html  %}

Example Code --> `{% raw %}{% include feature/timelinejs.html  %}{% endraw %}`



#### Include a Button 

- Buttons -- > `{% raw %}{% include feature/button.html text="Button Link to Somewhere" link="https://collectionbuilder.github.io/" color="success" %}{% endraw %}`

{% include feature/button.html text="Button Link to Somewhere" link="https://collectionbuilder.github.io/" color="success" centered=true %}
  
#### Include an Alert

- Alerts -- > `{% raw %}{% include feature/alert.html text="this is an *alert* that 'warns' a user" color="warning" align="center" %}{% endraw %}`

{% include feature/alert.html text="This is an *alert* that 'warns' a user with centrally aligned text." color="warning" align="center"  %}

#### Include a Modal

- Modals -- > `{% raw %}{% include feature/modal.html button="This is a modal using a 'primary' colored button to invite clicking" title="when clicked:" text="A Modal will pop out a box with some more information" color="primary"  %}{% endraw %}`

{% include feature/modal.html button="This is a modal using a 'primary' colored button to invite clicking" title="When clicked:" text="A Modal will pop out a box with some more information" color="primary"  %} 
