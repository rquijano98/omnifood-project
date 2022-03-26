# Omnifood Project

## Description

This Omnifood Project is a landing page for a fictional service. This fictional service is a 365-day subscription that uses AI to design meals for the subscriber; these meals are then delivered to the subscriber daily. This landing page gives important information about the service as well and contains a call-to-action section, where the user can sign up for the fictional service. The details of this landing page are provided as highlights, which are listed below in this README file.

_**Disclaimer** Although I fully understand the HTML, CSS, and JavaScript of this project, this project was created as part of an online course, so this is not an original idea of mine._

## Highlights

<ins>**Note**</ins>: The entire page is dynamic by virtue of media queries. As such, I will not detail every single dynamic component of every section. I will only note the most noteworthy dynamic components.

### Header (bar at the top of the page that contains Omnifood logo and navigation)

1. The header bar is sticky. Once the user scrolls past the hero section (the part of the page titled **A healthy meal delivered to your door, every single day**), the header bar will show at the top of the page no matter how much the user scrolls.
2. When the user clicks on any of the navigation elements, they are scrolled smoothly to a component of the page that corresponds to that element. For example, if the user clicks on "How it works", they are brought to the component of the page that explains how the Omnifood service works.
3. <ins>**Responsive Highlight**</ins>: If the user's window is 944px or less, the navigation items no longer show in the top right. Instead, a hamburger icon is shown. When this hamburger icon is clicked on, a navigation menu containing the navigation items slides into view from the right side of the page. If the user clicks on one of these navigation items, the navigation menu closes and they are smoothly scrolled to the corresponding section on the page

### Hero Section (section titled "A healthy meal delivered to your door, every single day")

1. Clicking on the "Start eating well" button will smoothly scroll the user to the call-to-action section of the page, where they can input their information to sign up for the service. Clicking on the "Learn more" button will smoothly scroll the user to the component of the page immediately after the hero section where details about the service are given.

### Meals Section (titled "Omnifood AI chooses from 5,000+ recipes")

1. If the user hovers the cursor over one of the meal cards, it translates slightly vertically to indicate that it is "active." This is done using the transform and transition CSS properties.
2. <ins>**Note**</ins>: Clicking on "See all recipes" in this section simply takes the user to the top of the page; there currently is not another page that has a list of all of the recipes.

### Testimonials Section (titled "Once you try it, you can't go back")

1. The gallery of pictures shown off to the right hand side of this component has interactive pictures; when the user hovers over one, it zooms in slightly to show it is "active."
2. <ins>**Responsive Highlight**</ins>: Above a viewport width of 1344px, the gallery is a 4x3 grid off to the right; between 944px and 1344px, the gallery is a 6x2 grid off to the right; below 944px, the gallery is a 2x6 grid at the bottom of this section.

### Pricing Section (titled "Eating well without breaking the bank")

1. Whenever the user clicks on any of the two "Start eating well" buttons, they are brought to the call to action section, where the user can type in their information to sign up for the service.

### Call-to-Action Section (titled "Get your first meal for free!")

1. The user can input their information in order to sign up for the service. They can either click "Sign up now" or hit enter after they have typed in their information. Currently, the only thing that happens when the user signs up is that the page reloads.
2. This is a form with input validation. If the user inputs an unaccpetable value for one of the fields, a prompt appears that lets them know so. The user cannot sign up until all of the input fields are acceptable.

## How to Run the Application

1. Download or clone the "omnifood-project" repository from GitHub.
2. Navigate to the newly created directory, which should be called "omnifood-project" on your machine.
3. Open index.html in your web browser.
