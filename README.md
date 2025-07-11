# Description

The intention of this project was to create a prettier looking widget to
display iNaturalist observations on a website.

The resulting javascript link inserts a bootstrap carousel widget into your
website that displays a specified number of observations from the desired 
iNaturalist project.

Copy the below script into your webpage to embed, and customize the data attributes
as desired. The only required attribute is the project id.
```
<script src="https://Callisto-Burns.github.io/iNat-Widget/inat-widget.js"
    data-project-id="YOUR-PROJECT-ID"
    data-num-obs="9"
    data-title="TITLE"
    data-color="limegreen"
    data-height="350"
    date-image-size="medium"
    data-font="Young Serif"></script>
```
Available image sizes are square, small, medium, and large.

Multiple instances of the widget may be easily added to your website that each
link to separate projects if desired.

# Demo
![Widget demo screenshot](assets/widget_demo.png)

To view a live demo, visit the github pages site for this repo 
[here](https://Callisto-Burns.github.io/iNat-Widget)
