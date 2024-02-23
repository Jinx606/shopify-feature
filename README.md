# README.md Guide for installing on MacOS

## Install Shopify CLI:

Open your terminal and run the following command to install Shopify CLI using Homebrew:

brew tap shopify/shopify
brew install shopify-cli

## Cloning the repository

Navigate to the directory where you would like to clone your theme to and enter the following command:

shopify theme init

You will be prompted for a new name. Once you have named your theme, navigate into it or use your code editor to open the folder.

Start your local development server by entering the following command: 

shopify theme dev --store {store-name}

store-name will be the name of your store so be sure to adjust accordingly

## Changes I have made

I have added a .liquid file to the sections folder of the theme and named it "New Feature section"
This section relies on a .css file I have created and added to the assets folder. 
The new section allows a user to choose a new featured product and have up to 5 product features in a bullet point fashion.
There is also a call to action button which the user is able to link to a URL and name according to their preferences.
At this stage it is still a work in progress however the features do function.

## Using and Modifying the section

Once you have logged in to your shopify admin page, you will be able to add this section by scrolling down to add section. In the search bar type: New, and the feature will pop up. Click on it to add it to the page.

To modify the feature, you are able to select a product from your store. This will automatically have the product title show above the image.
There are 5 text areas to which you are able to add your chosen features.
The button URL needs to be filled in with your chosen URL and the button text will only be visible once you have eneterd your chosen text. The button will also enlarge as you type.

Save your page and continue editing.

## License

Copyright (c) 2021-present Shopify Inc. See [LICENSE](/LICENSE.md) for further details.
