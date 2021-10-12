<<<<<<< HEAD
# Dreamhouse Lightning Web Components Sample Application

[![CI Workflow](https://github.com/trailheadapps/dreamhouse-lwc/workflows/CI/badge.svg)](https://github.com/trailheadapps/dreamhouse-lwc/actions?query=workflow%3ACI) [![Packaging Workflow](https://github.com/trailheadapps/dreamhouse-lwc/workflows/Packaging/badge.svg)](https://github.com/trailheadapps/dreamhouse-lwc/actions?query=workflow%3APackaging) [![codecov](https://codecov.io/gh/trailheadapps/dreamhouse-lwc/branch/main/graph/badge.svg)](https://codecov.io/gh/trailheadapps/dreamhouse-lwc)

> IMPORTANT: This is the new Lightning Web Components version of the Dreamhouse sample application. If you are looking for the Aura version, click [here](https://github.com/dreamhouseapp/dreamhouse-sfdx).

![dreamhouse-logo](dreamhouse-logo.png)

DreamHouse is a sample application that demonstrates the unique value proposition of the Salesforce platform for building Employee Productivity and Customer Engagement apps.

<div>
    <img src="https://res.cloudinary.com/hy4kyit2a/f_auto,fl_lossy,q_70,w_50/learn/projects/quick-start-dreamhouse-sample-app/17d9a9454cb84973b3adfe25e9f12b01_badge.png" align="left" alt="Trailhead Badge"/>
    Learn more about this app by completing the <a href="https://trailhead.salesforce.com/en/content/learn/projects/quick-start-dreamhouse-sample-app">Quick Start: Explore the Dreamhouse Sample App</a> Trailhead project.
    <br/>
    <br/>
    <br/>
</div>

> This sample application is designed to run on Salesforce Platform. If you want to experience Lightning Web Components on any platform, please visit https://lwc.dev, and try out our Lightning Web Components sample application [LWC Recipes OSS](https://github.com/trailheadapps/lwc-recipes-oss).

## Table of contents

-   [Installing Dreamhouse Using a Scratch Org](#installing-dreamhouse-using-a-scratch-org): This is the recommended installation option. Use this option if you are a developer who wants to experience the app and the code.

-   [Installing Dreamhouse Using an Unlocked Package](#installing-dreamhouse-using-an-unlocked-package): This option allows anybody to experience the sample app without installing a local development environment.

-   [Installing Dreamhouse using a Developer Edition Org or a Trailhead Playground](#installing-dreamhouse-using-a-developer-edition-org-or-a-trailhead-playground): Useful when tackling Trailhead Badges or if you want the app deployed to a more permanent environment than a Scratch org.

-   [Note on Sample Data Import](#note-on-sample-data-import)

-   [Optional installation instructions](#optional-installation-instructions)

-   [Code tours](#code-tours)

## Installing Dreamhouse using a Scratch Org

1. Set up your environment. Follow the steps in the [Quick Start: Lightning Web Components](https://trailhead.salesforce.com/content/learn/projects/quick-start-lightning-web-components/) Trailhead project. The steps include:

    - Enable Dev Hub in your Trailhead Playground
    - Install Salesforce CLI
    - Install Visual Studio Code
    - Install the Visual Studio Code Salesforce extensions, including the Lightning Web Components extension

1. If you haven't already done so, authorize your hub org and provide it with an alias (**myhuborg** in the command below):

    ```
    sfdx auth:web:login -d -a myhuborg
    ```

1. Clone this repository:

    ```
    git clone https://github.com/dreamhouseapp/dreamhouse-lwc
    cd dreamhouse-lwc
    ```

1. Create a scratch org and provide it with an alias (**dreamhouse** in the command below):

    ```
    sfdx force:org:create -s -f config/project-scratch-def.json -a dreamhouse
    ```

1. Push the app to your scratch org:

=======
# DreamHouse Aura Sample Application
Hi Welcome to Salesforce Project

> **⚠️ IMPORTANT ⚠️ :** This is the Aura version of the DreamHouse sample application. If you are looking for the new Lightning Web Components version, click [here](https://github.com/dreamhouseapp/dreamhouse-lwc).

![dreamhouse-logo](dreamhouse-logo.png)

[![CircleCI](https://circleci.com/gh/dreamhouseapp/dreamhouse-sfdx.svg?style=svg)](https://circleci.com/gh/dreamhouseapp/dreamhouse-sfdx)

Dreamhouse is a sample application for the real estate business built on the Salesforce platform. It allows brokers to manage their properties and customers to find their dream house.

## Table of contents

* [Installation instructions](#installation-instructions)
    * [Installing DreamHouse using Salesforce DX](#installing-dreamhouse-using-salesforce-dx)
    * [Installing DreamHouse using an unlocked package](#installing-dreamhouse-using-an-unlocked-package)
* [Code highlights](#code-highlights)
* [Additional resources](#additional-resources)

## Installation Instructions

There are two ways to install DreamHouse:
- Using Salesforce DX
- Using an unlocked package

### Installing DreamHouse using Salesforce DX
This is the recommended installation option for developers who want to experience the app and the code.

1. Install Salesforce DX. Enable the Dev Hub in your org or sign up for a Dev Hub trial org and install the Salesforce DX CLI. Follow the instructions in the [Salesforce DX Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm?search_text=trial%20hub%20org) or in the [App Development with Salesforce DX](https://trailhead.salesforce.com/modules/sfdx_app_dev) Trailhead module.

1. Clone the **dreamhouse-sfdx** repository:
    ```
    git clone https://github.com/dreamhouseapp/dreamhouse-sfdx
    cd dreamhouse-sfdx
    ```

1. Create a scratch org and provide it with an alias of your choice (**dh** in the command below):
    ```
    sfdx force:org:create -s -f config/project-scratch-def.json -a dh
    ```

1. Push the app to your scratch org:
>>>>>>> 47d15fe85b948ea7bf6d4f47f7edc7e55f9368c7
    ```
    sfdx force:source:push
    ```

1. Assign the **dreamhouse** permission set to the default user:
<<<<<<< HEAD

=======
>>>>>>> 47d15fe85b948ea7bf6d4f47f7edc7e55f9368c7
    ```
    sfdx force:user:permset:assign -n dreamhouse
    ```

<<<<<<< HEAD
1. (Optional) Assign the `Walkthroughs` permission set to the default user.

    > Note: this will enable your user to use In-App Guidance Walkthroughs, allowing you to be taken through a guided tour of the sample app. The Walkthroughs permission set gets auto-created with In-App guidance activation.

    ```
    sfdx force:user:permset:assign -n Walkthroughs
    ```

1. Import sample data:

    ```
    sfdx force:data:tree:import -p data/sample-data-plan.json
    ```

1. Open the scratch org:

=======
1. Open the scratch org:
>>>>>>> 47d15fe85b948ea7bf6d4f47f7edc7e55f9368c7
    ```
    sfdx force:org:open
    ```

<<<<<<< HEAD
1. In **Setup**, under **Themes and Branding**, activate the **Lightning Lite** theme.

1. In App Launcher, select the **Dreamhouse** app.

## Installing Dreamhouse using an Unlocked Package

Follow this set of instructions if you want to deploy the app to a more permanent environment than a Scratch org or if you don't want to install the local developement tools. You can use a non source-tracked orgs such as a free [Developer Edition Org](https://developer.salesforce.com/signup) or a [Trailhead Playground](https://trailhead.salesforce.com/).

Make sure to start from a brand-new environment to avoid conflicts with previous work you may have done.

1. Log in to your org

1. Click [this link](https://login.salesforce.com/packaging/installPackage.apexp?p0=04t3h000004VW48AAG) to install the Dreamhouse unlocked package in your org.

1. Select **Install for All Users**

1. In App Launcher, click **View all**, select the Dreamhouse app.

1. Click the **Settings** tab and click the **Import Data** button in the **Sample Data Import** component.

1. If you're attempting the [Quick Start](https://trailhead.salesforce.com/en/content/learn/projects/quick-start-dreamhouse-sample-app) on Trailhead, this step is required, but otherwise, skip:

    - Go to **Setup > Users > Permission Sets**.
    - Click **dreamhouse**.
    - Click **Manage Assignments**.
    - Check your user and click **Add Assignments**.

1. In **Setup**, under **Themes and Branding**, activate the **Lightning Lite** theme.

1. In App Launcher, select the **Dreamhouse** app.

## Installing Dreamhouse using a Developer Edition Org or a Trailhead Playground

Follow this set of instructions if you want to deploy the app to a more permanent environment than a Scratch org.
This includes non source-tracked orgs such as a [free Developer Edition Org](https://developer.salesforce.com/signup) or a [Trailhead Playground](https://trailhead.salesforce.com/).

Make sure to start from a brand-new environment to avoid conflicts with previous work you may have done.

1. Clone this repository:

    ```
    git clone https://github.com/dreamhouseapp/dreamhouse-lwc
    cd dreamhouse-lwc
    ```

1. Authorize your Trailhead Playground or Developer org and provide it with an alias (**mydevorg** in the command below):

    ```
    sfdx auth:web:login -s -a mydevorg
    ```

1. Run this command in a terminal to deploy the app.

    ```
    sfdx force:source:deploy -p force-app
    ```

1. Assign the `dreamhouse` permission set to the default user.

    ```
    sfdx force:user:permset:assign -n dreamhouse
    ```

1. Import some sample data.

    ```
    sfdx force:data:tree:import -p ./data/sample-data-plan.json
    ```

1. If your org isn't already open, open it now:

    ```
    sfdx force:org:open -u mydevorg
    ```

1. In **Setup**, under **Themes and Branding**, activate the **Lightning Lite** theme.

1. In App Launcher, select the **Dreamhouse** app.

## Note on Sample Data Import

Properties inserted using the Salesforce CLI will appear as listed on TODAY() - 10 days. If you want to have this value randomized, perform the data import from the app Settings tab instead.

## Optional Installation Instructions

This repository contains several files that are relevant if you want to integrate modern web development tooling to your Salesforce development processes, or to your continuous integration/continuous deployment processes.

### Code formatting

[Prettier](https://prettier.io 'https://prettier.io/') is a code formatter used to ensure consistent formatting across your code base. To use Prettier with Visual Studio Code, install [this extension](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) from the Visual Studio Code Marketplace. The [.prettierignore](/.prettierignore) and [.prettierrc](/.prettierrc) files are provided as part of this repository to control the behavior of the Prettier formatter.

### Code linting

[ESLint](https://eslint.org/) is a popular JavaScript linting tool used to identify stylistic errors and erroneous constructs. To use ESLint with Visual Studio Code, install [this extension](https://marketplace.visualstudio.com/items?itemName=salesforce.salesforcedx-vscode-lwc) from the Visual Studio Code Marketplace. The [.eslintignore](/.eslintignore) file is provided as part of this repository to exclude specific files from the linting process in the context of Lightning Web Components development.

### Pre-commit hook

This repository also comes with a [package.json](./package.json) file that makes it easy to set up a pre-commit hook that enforces code formatting and linting by running Prettier and ESLint every time you `git commit` changes.

To set up the formatting and linting pre-commit hook:

1. Install [Node.js](https://nodejs.org) if you haven't already done so
1. Run `npm install` in your project's root folder to install the ESLint and Prettier modules (Note: Mac users should verify that Xcode command line tools are installed before running this command.)

Prettier and ESLint will now run automatically every time you commit changes. The commit will fail if linting errors are detected. You can also run the formatting and linting from the command line using the following commands (check out [package.json](./package.json) for the full list):

```
npm run lint
npm run prettier
```

## Code Tours

Code Tours are guided walkthroughs that will help you understand the app code better. To be able to run them, install the [CodeTour VSCode extension](https://marketplace.visualstudio.com/items?itemName=vsls-contrib.codetour).

## Credits

The app GeocodingService uses OpenStreetMap API to geocode property addresses. OpenStreetMap® is open data, licensed under the [Open Data Commons Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/) by the [OpenStreetMap Foundation (OSMF)](https://wiki.osmfoundation.org/wiki/Main_Page). You are free to copy, distribute, transmit and adapt OpenStreetMap data, as long as you credit OpenStreetMap and its contributors. If you alter or build upon our data, you may distribute the result only under the same licence. The [full legal code](https://opendatacommons.org/licenses/odbl/1-0/) explains your rights and responsibilities in regard to the service.
=======
1. Select **DreamHouse** in the App Launcher

1. Click the **Data Import** tab and click **Initialize Sample Data**

### Installing DreamHouse using an unlocked package
This is the recommended option for non developers. Use this option if you want to experience the sample app but do not plan to modify the code.

1. [Sign up](https://developer.salesforce.com/signup) for a developer edition.

1. Enable My Domain. Follow the instructions to enable My Domain [here](https://trailhead.salesforce.com/modules/identity_login/units/identity_login_my_domain).

1. Click [this link](https://login.salesforce.com/packaging/installPackage.apexp?p0=04t1I0000036u98QAA) to install the DreamHouse unlocked package into your developer edition org.

1. Select **Install for All Users**. When prompted, make sure you grant access to the external sites (api.lifx.com, dreamhouzz-push-server.herokuapp.com, and hooks.slack.com).

1. Select **DreamHouse** in the App Launcher.

1. Click the **Data Import** tab and click **Initialize Sample Data**.

## Code highlights

### Lightning components
DreamHouse features a large number of Lightning Components to enhance the user experience. Lightning Components are used on the Property record page, on an app pages (**Property Finder** and **Property Explorer**), in the utility bar, and as quick actions.

Installing a Lightning component as a **quick action** can be a great alternative to adding the component directly to the page layout because the component instantiation is deferred until the action button is clicked (lazy instantiation). Installing less frequently used components as quick or global actions can contribute to a faster page loading time, and a streamlined user interface. In DreamHouse, the [SmartHome](force-app/main/default/aura/SmartHome) component is installed as a quick action on the Property record page.

The **utility bar** is a great place to host components you always want at your fingertips. [MortgageCalculator](force-app/main/default/aura/MortgageCalculator) is a great example.

### Base Lightning components
Base Lightning Components are a set of powerful UI components available in the Lightning Component Framework. The DreamHouse custom components use many Base Lightning Components as building blocks. For example, **lightning:card**, **lightning:button**, and **lightning:layout** are used throughout the application. [PropertyCarousel](force-app/main/default/aura/PropertyCarousel/PropertyCarousel.cmp), which allows you to navigate through the pictures of a property and upload new pictures, is built using **lightning:carousel** and **lightning:fileUpload**. [PropertySummary](force-app/main/default/aura/PropertySummary/PropertySummary.cmp) leverages **lightning:formattedAddress** and **lightning:formattedNumber**.

### Lightning Data Service
Lightning Data Service allows you to manipulate (retrieve, create, update, delete) Salesforce records without writing server-side code (Apex). In DreamHouse, all the Lightning components that work with a single Property record use Lightning Data Service. Check out [PropertySummary](force-app/main/default/aura/PropertySummary) for an example.

### Third-Party JavaScript libraries
You can use third-party JavaScript libraries in Lightning Components using **ltng:require**. For example:
- [Map](force-app/main/default/aura/Map) and [PropertyListMap](force-app/main/default/aura/PropertyListMap) use the [Leaflet](https://leafletjs.com/) library.
- [PriceRange](force-app/main/default/aura/PropertyListMap) uses the [nouislider](https://refreshless.com/nouislider/) library for its double slider.

### Standard application events
Standard application events are available by default in the framework and are used to trigger high level actions. For example, in [PropertySummary](force-app/main/default/aura/PropertySummary/PropertySummaryController.js), **force:navigateToSObject** is used to navigate to the broker record page, and **force:editRecord** is used to edit a record in place.

### Custom application events
Custom application events are used for communication between components in App Builder. For example, the [PropertyFilterChange](force-app/main/default/aura/PropertyFilterChange) event is fired in the [PropertyFilter](force-app/main/default/aura/PropertyFilter) component to notify other components that new filtering criteria have been selected.

### Component events
Component events are used for finer-grained communication between components. For example, the [PropertyPaginator](force-app/main/default/aura/PropertyPaginator) component fires the **pageNext** and **pagePrevious** events to notify its parent ([PropetyTileList](force-app/main/default/aura/PropertyTileList)) that the user requested the next or previous page.

### Custom page templates
Custom page templates allow you to create ad hoc page layouts that admins can use in App Builder to create new pages. Custom page templates are implemented as Lightning Components. There are two custom page templates in Dreamhouse: [PageTemplate_2_6_4](force-app/main/default/aura/PageTemplate_2_6_4/PageTemplate_2_6_4.cmp) (used by the **Property Finder** page) and [PageTemplate_2_7_3](force-app/main/default/aura/PageTemplate_2_7_3/PageTemplate_2_7_3.cmp) (used by the **Property Explorer** page). They provide custom three column layouts using different relative widths for each column.

### Reports and dashboards
Reports and dashboards are easy to create and look great in Lightning. Just to get things started, the DreamHouse app includes a few reports in the **DreamHouse Reports** folder (**Days on Market**, **Properties by Broker**, and **Portfolio Health**), and a dashboard in the **DreamHouse Dashboard** folder (**My Dashboard**).

### Einstein Vision
The [VisualSearchBox](force-app/main/default/aura/VisualSearchBox) component leverages Einstein Vision to provide a visual search feature that allows you to find houses based on the picture of a house you like. Just select or drag a picture in the Visual search area of the property filters: Einstein Vision will recognize the type of house (colonial, victorian, or contemporary) and you will be presented with a list of houses matching that category. Follow the instructions below to enable visual search in the **Property Finder** and **Property Explorer** pages:

1. Get an **Einstein Platform Services** account. Follow the instructions [here](https://trailhead.salesforce.com/projects/predictive_vision_apex/steps/predictive_vision_apex_prep).

1. In Salesforce, click the **Files** tab and upload **einstein_platform.pem**.

1. In **Setup**, type **Custom** in the Quick Find box and click the **Custom Settings** link.

1. Click the first **New** Button (at the top of the screen).

1. For **Einstein Vision Email**, specify the email address you used when you created your Einstein Platform Services account (step 1), and click **Save**.

1. In the DreamHouse app, click the **Einstein Vision** tab.

1. Click the **Create Dataset** button.

1. In the **houses** tile, click the **Train** button, the click the **Models** tab.

1. Click the **Refresh Models** button until the Progress column indicates **100%**.

1. Copy the **Model Id** in your clipboard.

1. Click the **Property Finder** Tab, click the gear icon (upper right corner), and click **Edit Page**. Click the **Filters** component and paste the Model Id in the **Einstein Model Id** field in the right sidebar. Save the page.

1. Repeat the last step for the **Property Explorer** page.

You can now search houses by uploading (or dropping) a picture in the visual search box that is part of the Filters component on the **Property Finder** and **Property Explorer** pages.

## Additional resources
DreamHouse has many more features not discussed here. For example, DreamHouse also demonstrates how to:

- Use the Salesforce Mobile App
- Create a customer engagement mobile app with the Mobile SDK
- Automate processes with Process Builder, including sending push notification messages to the customer engagement app
- Integrate with Alexa, Slack, and Facebook Messenger
- Integrate with IoT devices like smart lights, smart thermostats, and smart locks

Head over to [dreamhouseapp.io](http://dreamhouseapp.io) to learn more.
>>>>>>> 47d15fe85b948ea7bf6d4f47f7edc7e55f9368c7
