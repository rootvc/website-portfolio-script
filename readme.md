# Website Filter
This contains the scripts and instructions to manage portfolio filtering on the [website](https://root.vc).

## Squarespace

### Adding a Company
Companies are pulled from [this Squarespace gallery](https://kane-hsieh-xn2j.squarespace.com/config/pages/5d449be90fa8570001f17800). 
To add a company, simply upload a new file into the gallery, and change the settings so that it has the corrcet clickthrough URL and "Categories".
### Companies Page
The **Companies** section is simply a Squarespace grid object that is linked to a Squarespace gallery. The code that filters by companies is uploaded as a code injection to the website. To find this code, go to the [**Squarespace Pages**](https://kane-hsieh-xn2j.squarespace.com/config/pages), click on the settings button for the **Welcome** page, and click the **Advanced** tab.
### Changing the Code
The script is found in this repo at [activewebsitescript.html](./activewebsitescript.html). This script relies on a hosted css sheet and javascript script - these have been locally download in this repo at [custom-filter.min.css](./custom-filter.min.css) and [custom-filter.min.js](./custom-filter.min.js). The filter, which was purchased online as a package, came with a [Readme.txt](./Readme.txt) and examples of how to use it in [UniversalFilterPageInjections.txt](./UniversalFilterPageInjections.txt)
