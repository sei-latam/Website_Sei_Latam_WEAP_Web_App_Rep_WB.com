# Summary

Webpage and Documentation from Development Protocols and Processes for Accessing Data from the Bolivia Surface Water Balance using monthly measurements of temperature, precipitation, runoff, evapotranspiration (real and reference) between 1980 and 2020.

## Original Repository Application (WEAP_WebAppRepWB)

The official version of the WEAP_WebAppRepWB application is available in a GitHub repository of the Stockholm Environment Institute Latin America (SEI-LA), for more information about the construction and development of the application (codes, libraries, scripts, data, etc.). Please access the following URLs:

 Original Repository
 [https://github.com/sei-latam/WEAP_WebAppRepWB](https://github.com/sei-latam/WEAP_WebAppRepWB)

WEAP_WebAppRepWB Application: [https://ee-carlosmendez.projects.earthengine.app/view/hruwatersei](https://carlosmendezsei.users.earthengine.app/view/hruwatersei)


```html
https://github.com/sei-latam/WEAP_WebAppRepWB
https://carlosmendezsei.users.earthengine.app/view/hruwatersei
```

# Use and install this repository

HTTPS
```html
https://github.com/sei-latam/Website_Sei_Latam_WEAP_Web_App_Rep_WB.com.git
```

SSH
```html
git@github.com:sei-latam/Website_Sei_Latam_WEAP_Web_App_Rep_WB.com.git
```

GitHub CLI
```html
gh repo clone sei-latam/Website_Sei_Latam_WEAP_Web_App_Rep_WB.com
```

# Development WEAP_WebAppRepWB Webpage

Webpage built in `GitHub Pages` `HTML` `CSS` `JavaScript` Languages.

Each page section of WEAP_WebAppRepWB Webpage is described below:

## Summary and structure/design [page](https://sei-latam.github.io/Website_Sei_Latam_WEAP_Web_App_Rep_WB.com/summary.html)

* General introduction to the application, with a brief description of the project “Protocols and development processes for accessing surface water balance data in Bolivia.”

![WEAP_WebAppRepWB_Animations](https://github.com/sei-latam/Website_Sei_Latam_WEAP_Web_App_Rep_WB.com/blob/27ddbe75be038ad87f3ff251043c38627f02dcf7/img/WEAP_WebAppRepWB_Animations.gif)

## Development and structure (Back-End and Front-End) [page](https://sei-latam.github.io/Website_Sei_Latam_WEAP_Web_App_Rep_WB.com/development.html)

### Data structure 

* Database definition
* Merging of temporal and spatial information.
* Creation of multispectral images.
* Creation of monthly and annual image collections.
 
![WEAP_Bolivia_Flux](https://github.com/sei-latam/Website_Sei_Latam_WEAP_Web_App_Rep_WB.com/blob/3c5d3ca7ff706837b05d400be08103820a948233/img/WEAP_Bolivia_Flux.gif)

### Back-End

* Amount and access to monthly and annual ImageCollections
* Preprocessing and automation of images
* Creation and configuration of interfaces, elements, and graphic viewers for the front-end component
* Import of external libraries and extensions for the creation of base maps and symbologies
* Development of the different queries, filters, and analyses defined in the web application design
* Writing and development of the different code versions used through the API (Application Programming Interface) in Google Earth Engine.

### Front-End 
![Front_Design_GEE_WEAP_App](https://github.com/sei-latam/Website_Sei_Latam_WEAP_Web_App_Rep_WB.com/blob/3c5d3ca7ff706837b05d400be08103820a948233/img/Front_Design_GEE_WEAP_App.png)

## Queries, filters and data analysis [page](https://sei-latam.github.io/Website_Sei_Latam_WEAP_Web_App_Rep_WB.com/query.html)

* Base map selection.
* Variable selection and legend update.
* Time series by points and variables.
* Time series drawing polygons and selecting variables.
* Adding images by date and variable.
* Importing external files (.Kml, .Shp, .GeoJSON).
* Downloading images and post-processing .csv files.

[![YouTube Video OlX5Or-l1rQ](https://img.youtube.com/vi/OlX5Or-l1rQ/maxresdefault.jpg)](https://www.youtube.com/watch?v=OlX5Or-l1rQ)


## Contact and Authors [page](https://sei-latam.github.io/Website_Sei_Latam_WEAP_Web_App_Rep_WB.com/contact.html)

* Gustavo Ayala, Research Fellow @GustavoAyalaTicona
* Sebastián Palomino, Research Associate @spalominoa
* Carlos Méndez, Research Associate @CarlosMendez1997Sei

## Credits and repository of data

The original code, repositories and scripts used in this project, are available at: [https://earthengine.googlesource.com/users/carlosmendez/ExercicesSEI/+/refs/heads/master/WEAP_WebAppRepWB](https://earthengine.googlesource.com/users/carlosmendez/ExercicesSEI/+/refs/heads/master/WEAP_WebAppRepWB)

# Credits and Intellectual Acknowledgments to the Original Author of the Website 

### Author Information and Data
Name: Yen-Chia Hsu @yenchiah

Official GitHub Account: https://github.com/yenchiah

Official Repositorio: https://github.com/yenchiah/project-website-template

Demo Website: https://yenchiah.github.io/project-website-template/

Latest Version: [v3.36](https://github.com/yenchiah/project-website-template/tree/277205cb699b02f3f7ba5f9f6ea20d987582c5bf).

### Policy for Open Source Contribution (By Original Author)

`I welcome and appreciate contributions in fixing bugs and enhancing features. However, please avoid submitting pull requests (PRs) that modify the template's existing design without discussing them with me. Please do not submit PRs that are not related to bug fixes or feature enhancements. Editing text in the README file is not encouraged (e.g., fixing grammar errors). PRs with unnecessary editing (e.g., adding unrelated text, changing the design of the template, modifying the README text arbitrarily) or unrelated changes (e.g., changes that are related to only their applications) will be marked as "spam" and "invalid".`

`If you are excited to contribute to the new features directly, please explain your design decisions and how your design matches this template's style in the PR. If you fix bugs, please explain which bug you fixed and how you fixed them. The explanations that you put in each PR can greatly help me determine if the changes can be merged into the master branch. PRs with no explanations will highly likely be rejected and marked as "wontfix".`
