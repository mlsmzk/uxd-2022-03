---
layout: page
title: Prototype Documentation
show_sidebar: false
menubar: design_refinement_menu
permalink: /design-refinement-phase/prototype-documentation/
---
### Link to System
<a class="normal_link" href="https://www.figma.com/file/3CFsnljoqRCtg0DkCvcSeH/Wireframing?node-id=0%3A1" target="_blank">
    Figma Interactive Prototype
</a>


### Context and Setup Notes
When working through the prototype, please fit the prototype to your screen. You can do this by pressing “Z” on your keyboard or by going to “Options” in the top right corner of the prototyping flow and selecting “Fit to Screen.” Although we are prototyping 2-dimensional screens on Figma, we intend our experience to be an augmented reality (AR) interface; when testing, imagine that you are wearing AR glasses, and all of the touch interfaces are superimposed on your current background.
 

### What Type of User You Are
You are a climate advocate and have oriented your life around sustainability. You research grocery items for hours before buying, confirming that they are sustainable. 


### Context for What We Built
Little Trees AR is an app that displays information about the sustainability of a product while you’re in a grocery store. There are three icons you’ll encounter, the leaves indicate the sustainability of an item and range from 1 tree (low sustainability) to 3 (high sustainability). This score is based on the reports we’ve aggregated from companies; we are not creating the data ourselves. The stars are reviews from peer shoppers, price is the amount it costs for the product. We divided our prototype into two separate experiences that the user would complete at different times: configuration of the app (tailor settings to user preferences) and usage of the app in-store. For testing, these will be two flows that are independent and will need to be tested separately. We do not have full functionality implemented yet; the instructions below will describe which interfaces have functionality and which ones do not.


### How to Walk Through the Configuration Flow
You will begin with onboarding so we can get to know what type of shopper you are. You should start testing at the flow labeled “Configuration Flow.” The first slides walk through three personas of shoppers, select which one you are. The second part of the flow asks you where you shop and what items you purchase. Then, you begin preshopping.
 
At the time of testing, there may not be a flow from persona selection to preshopping. If this is the case, begin testing at the flow labeled “Pre-Shopping Flow.” Little Trees will ask you a series of questions where you have to choose which product you prefer from a selection of three. It will also ask the user to select what influenced their selection. They repeat this process 10 times. This allows Little Trees to get an initial understanding of the user’s preferences to help make a smoother recommendation system to start with. 
 
Subsequently, Little trees asks the user to select the grocery categories that the user may be interested in. This process is similar to how Pinterest asks the user what categories they are interested in when they sign up. This also contributes to the learning algorithm to improve the earlier shopping experiences. After some time, the learning algorithm will rely less on the initial configuration and more on their in-store decisions.
 
We currently do not have functionality for each of the selection options; please click on the simulation screen to see which buttons have interactions, and which do not. It is our intent to build out options for each of the possible selections in the future.


### How to Walk Through the Shopping Flow
You should start testing at the flow that is labeled “Explore Flow.” The explore flow is a shopping experience for those who have no items in their shopping list and just want to explore the store. Currently, you can only interact with the Folger’s Classic Roast icon and the On/Off toggle, but we intend for all of the explore items at the top of the screen to have similar functionality. If you add the Classic Roast coffee to the shopping list, you will also be able to remove it using the red trash icon. If at any point you click the “Add Item” button at the bottom of the shopping list, it will take you to another section of our shopping experience, and you will not be able to go back to the explore screens without resetting the flow. Our intent is that whenever you add your first item to your list, whether through the explore options or through the “Add Item” button, you will leave the explore mode and enter the shopping list mode. At the moment, this transition happens only through the “Add Item” button.
 
After clicking on “Add Item,” you will see a search menu pop up with a search bar at the top and some category buttons. At the moment, only the top left buttons have functionality. So, to move through the search screens, you need to click “Dairy” → “Milk” → “Whole” → “Fairlife.” We intend to have similar functionality for all of the buttons in the search menu.
 
After clicking through the search experience, you will be brought to a screen with a shopping list that is more filled out, with the milk that you just selected at the bottom; this shopping experience is directed towards those that shop from a list. The buttons that are functional in this part of the shopping experience are the green “Replace” buttons, the red “Dismiss” button, the On/Off toggle for the mini explore panel at the top of the screen, and the green and red accept and reject buttons in that mini explore panel. In the future, we intend the “Add Item” button to be functional in this part of the experience as well, and eventually you should be able to remove items from the shopping list as well as click on them to see more detailed information panels, as in the Explore screens.