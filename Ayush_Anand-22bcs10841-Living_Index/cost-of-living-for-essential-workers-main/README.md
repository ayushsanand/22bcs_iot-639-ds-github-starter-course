# Cost Of Living for US Essential Workers
Website URL:
(https://github.com/ayushsanand/22bcs_iot-639-ds-github-starter-course.git)
## Team Members and Contribution
Ayush Anand 22BCS10841@cuchd.in

## Project Proposal Abstract
As the pandemic has shown, many workers essential to the functioning of cities are also some of our lowest paid. This interactive visualization design project intends to demonstrate how difficult it is to live as an essential worker in major U.S. cities to build a case for increasing the minimum wage. We will investigate the cost of living of select U.S. cities and compare them with the incomes these workers receive. The groups of interest include both the essential workers who generally receive minimum wage (e.g. restaurant workers, delivery drivers, etc.) and others who are paid higher than minimum wage (e.g. teachers, mail carriers, bus drivers, etc.). We would like to break down the cost of living through different measures such as housing prices or the Cost of Living Index to provide an overview of cities across the country. Also, we want to investigate how many hours an individual would have to work at those low-end wages to live a decent life in those cities either as a single person or as a parent supporting their families. If possible, we would also like to make comparisons highlighting the impacts of pandemic on the targeting community.

Through proper If possible, we would also like to make comparisons highlighting the impact of the pandemic on essential workers.


## Getting Started

This repo is set up to use the [Parcel](https://parceljs.org/) bundler. If you don't
like the way we've set things up, feel free to change it however you like! You are welcome to add, delete, rename, and replace any files contained here. You may also style and organize your final webpage however you would like.

The only restriction is that __your final HTML/CSS/JS output must be stored in the "docs" folder__ so that
GitHub knows how to serve it as a static site.
### Install
#### Required software

You must have Node.js installed. You can get it directly from
https://nodejs.org/en/.

#### Install dependecies

Once you've got `node`, run the command `npm install` in this project folder
and it will install all of the project-specific dependencies (if you're curious open up `package.json` to see where these are listed).

npm is the _node package manager_.

### Local development
Notice that the repository is setup with 3 folders: `src/`, `static/`, and `docs/`.

`src/` is where all of your HTML/CSS/JS files should go. Feel free to add sub-folders to divide CSS and JavaScript files.

`static/` is where you can place your data files. The Parcel static file plugin has been installed,
so any files you put in the `static/` folder will be available over the network. See [this guide](https://gist.github.com/mathisonian/46eed3e6102888ddf741829fbbe262ff) for more information on loading data.

`docs/` is the folder that contains the bundled HTML/CSS/JS that you will serve to your final public project site. See below for a more detailed explanation.


### Running the local dev server

To run the project locally, run `npm start` and it will be available at http://localhost:1234/. When the server is running, any local change that you make will be detected by Parcel and your webpage will auto-update with the new changes. Your local changes will not be visible to your team members until you push the changes to your repository. These changes will not be reflected in the final website unless you run the build script and push the updated docs folder (see below).

### Building the final output

Run `npm run build` and all of your assets will be compiled and placed into the `docs/` folder. Note
that this command will overwrite the existing docs folder. You do not have to manually create the `docs/` folder because everything will be handled in the build script. Parcel will bundle all assets in the `src/` folder and place then in a folder called `dist/`. GitHub Pages requires the folder name to be called `docs/`, so we move all assets from the `dist/` folder to the `docs/` folder for you.

If you are developing on a Windows machine, replace the `build` script in the `package.json` file with this:
`parcel build src/index.html --no-minify --public-url https://cse412-21w.github.io/project-demo & RD /S /Q .\\docs & ren .\\dist docs`

Once pushed to GitHub, the output should be available at cse412-21w.github.io/your-repo-name/.
For example, you can view the sample embedded Tableau, vega-lite, and d3 charts at https://cse412-21w.github.io/project-demo/.


## Other notes
### Using 3rd party libraries

You are more than welcome to use open source packages such as D3.js, just make sure to cite these.

To add a new one run `npm install --save <library-name>`, e.g. `npm install --save d3`. This will
add the library locally so it is available for use in your JS files. It will also add `d3` to the
list of dependencies in `package.json`.

_Note that if you install a library your teammates will need to install it too. Once the dependency is added
to `package.json` simply running `npm install` in this directory will download the new dependency._

#### Acknowledgements
This README was adapted from a [template](https://github.com/UW-CSE442-WI20/FP-Template) created by Matthew Conlen for a previous offering of CSE 442.
