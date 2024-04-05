# Wonder of VR

![image](https://github.com/Suth272/Wonder-of-VR/assets/159195438/06a23e6a-61a9-4b34-a1fc-b2ffdf2425c1)

Wonder of VR is an up and coming online newsletter that has a growing community. It covers news on any technology that relates and or progress Virtual Reality and aims to deliver both VR enthuasiasts and VR newbies the freshest news on VR. This webpage in particular is an introductory to Wonder of VR, what VR is and what some of the applications of VR, as well as a sign up to the newsletter and social links to join the growing community.

## Live Site
You can view the deployed site [here](https://suth272.github.io/Wonder-of-VR/).

## Repository
You can view the repository [here](https://github.com/Suth272/Wonder-of-VR).

## Author
Sutharshanan Alagarajah

# Table of Contents
- [Wonder of VR](#wonder-of-vr)
  * [Live Site](#live-site)
  * [Repository](#repository)
  * [Author](#author)
- [Features](#features)
    + [Navigation Bar](#navigation-bar)
    + [Header](#header)
    + [About Us](#about-us)
    + [Main content](#main-content)
    + [Footer](#footer)
  * [Future Features](#future-features)
- [Testing](#testing)
  * [Validation Testing](#validation-testing)
    + [CSS Validation](#css-validation)
    + [HTML Validation](#html-validation)
  * [Compatibility and Responsive Testing](#compatibility-and-responsive-testing)
  * [Manual Testing](#manual-testing)
      - [Main Page:](#main-page-)
      - [Sign up Form:](#sign-up-form-)
  * [Defect Tracking](#defect-tracking)
  * [Accessibility Testing](#accessibility-testing)
    + [Lighthouse Reports](#lighthouse-reports)
      - [Mobile Home Page Testing](#mobile-home-page-testing)
      - [Desktop Home Page Testing](#desktop-home-page-testing)
      - [Mobile Sign Up Page Testing](#mobile-sign-up-page-testing)
      - [Desktop Sign Up Page Testing](#desktop-sign-up-page-testing)
- [Technologies Used](#technologies-used)
  * [Languages](#languages)
  * [Frameworks, Libraries & Programs Used](#frameworks--libraries---programs-used)
- [Deployment](#deployment)
  * [Deploy to GitHub Pages](#deploy-to-github-pages)
- [Credits](#credits)
  * [Content](#content)
  * [Media](#media)
  * [Acknowledgments](#acknowledgments)

# Features
### Navigation Bar
The navigation bar is fixed at the top of the page, so the use can quickly navigate to the different parts of the webpage. It includes navigation to the differnt sections within the home page, as well as navigation to a seperate webpage to sign up to the newsletter. It also has a highlight/colour change feature when you hover the different navigations.

![image](https://github.com/Suth272/Wonder-of-VR/assets/159195438/4903f63f-600a-4ba9-84ed-7b738f62790c)

The navigation bar is also responsive, with it becoming collapsible at mobile phone screen sizes.

![image](https://github.com/Suth272/Wonder-of-VR/assets/159195438/2a8f652b-2933-4cb0-b679-84192f0f1076)


### Header
The header includes the previosuly stated fixed navigation bar, as well as the hero image and a small box on the right, telling the user what the webpage is about.

![image](https://github.com/Suth272/Wonder-of-VR/assets/159195438/381e0bc3-31cd-46db-9272-4477aac3aa79)

### About Us
This section tells the user what the goal of Wonder of VR is, including a hyperlink to the sign up page in case they did not see it in the navigation bar.

![image](https://github.com/Suth272/Wonder-of-VR/assets/159195438/4b7a083f-1ebe-4587-aaaf-9e9cd29dc69a)

### Main content
The main content of the webpage tells the user what VR is and what some of the uses are of VR.

![image](https://github.com/Suth272/Wonder-of-VR/assets/159195438/3e20018a-a9dc-4e21-9acf-38e825499c1e)

### Footer
The footer contains all the social links that the user wants to use to contact us, other ways to keep up with news of VR and or be apart of the Wonder of VR community.
It also includes an colour change feature when the user hovers over the hyperlinked icons.

![image](https://github.com/Suth272/Wonder-of-VR/assets/159195438/9cae49b2-8319-4ee8-a0ca-f7383f3ac7bf)

## Future Features
+ **Thank You Page** - A page that the user is taken to after completing the newsletter sign up that thanks them for joining, informs them they'll recieve a confirmation email soon and to make sure to check out the social platforms Wonder of VR is on.
+ **Page 404** - A custom 404 error page that still has the fixed navigation bar, as well as the footer, but also includes a custom quirky message saying something has gone wrong.

# Testing
This site has been tested in all aspects, all of which and the results can be seen below.

## Validation Testing
This testing section shows the successful tests from different code validators used.
### CSS Validation
+ No errors or warnings were returned when passing the CSS validation test.
+ The CSS validator that was used can be found [here](https://jigsaw.w3.org/css-validator/).

**style.css**
![image](https://github.com/Suth272/Wonder-of-VR/assets/159195438/2db8eac4-59ed-4344-b803-9530d158a71b)

### HTML Validation
+ No errors or warning were returned when passing the HTML validation test.
+ The HTML validator that was used can be found [here](https://validator.w3.org).

**index.html**
![image](https://github.com/Suth272/Wonder-of-VR/assets/159195438/3fe206bb-4244-45ec-9e48-b55e578cef9f)

**signup.html**
![image](https://github.com/Suth272/Wonder-of-VR/assets/159195438/bfd451e6-6344-4d7c-b82d-108cf2af34fe)

## Compatibility and Responsive Testing
I ensured my site was worked well, and looked nice on a variety of devices & browsers as noted in the table below:
| Tool               | Device                   | Browser        | OS         | Viewport width x height (px) |
|--------------------|--------------------------|----------------|------------|------------------------------|
| Real Phone         | OnePlus 7                | Chrome 123     | Android 12 | 412 x 892                    |
| Dev Tools Emulator | iPhone 14 Pro Max        | Safari         | iOS        | 430 x 932                    |
| Dev Tools Emulator | Samsung Galaxy S20 Ultra | Chrome 123     | Android 12 | 412 x 915                    |
| Dev Tools Emulator | iPad                     | Safari         | N/A        | 768 x 1024                   |
| Dev Tools Emulator | Nexus Hub                | N/A            | N/A        | 1024 x 600                   |
| Real Laptop        | HP Omen 15               | Opera GX       | Windows 11 | 1920 x 1080                  |
| Real Laptop        | ASUS ROG Strix G15       | Microsoft Edge | Windows 11 | 1920 x 1080                  |
| Real Desktop       | Custom Tower             | Chrome 123     | Windows 11 | 2560 x 1440                  |

## Manual Testing

#### Main Page:
- [x] Try to navigate to different parts of the webpage via the navigation bar
- [x] Try to use social links
- [x] Looks good on Mobile, Tablet and Desktop

#### Sign up Form:
- [x] Try to submit
- [x] Try to submit the empty form and verify that an error message about the required fields appears
- [x] Try to submit the form with an invalid email address and verify that a relevant error message appears
- [x] Try to submit the form with all inputs valid and verify that a success messsage appears
- [x] Try to submit the form with all required inputs valid with the non-required inputs empty
- [x] Looks good on Mobile, Tablet and Desktop 

## Defect Tracking
**Required** 
While coding the website, defects have occured throughout the build, which I have fixed as the project progressed. All the defects have been recorded in **GitHub Issues**. They can also be seen in the screenshots below.

### Issue 1:
![image](https://github.com/Suth272/Wonder-of-VR/assets/159195438/87a76933-8693-4b3b-9e8d-5faf4375a68e)

### Issue 2:
![image](https://github.com/Suth272/Wonder-of-VR/assets/159195438/02931879-7365-4f77-825c-064f5046b405)

### Issue 3:
![image](https://github.com/Suth272/Wonder-of-VR/assets/159195438/50dd8fc4-42a4-414a-9ab9-caa4f4937397)

## Accessibility Testing
Great has been taken to code the website to make sure it was as accessible as possible to people that have different disabilities. This can be seen in the lighthouse reports below, which were down using Chrome Dev Tools.

### Lighthouse Reports
The lighthouse reports also show the core web vitals, which have near perfect scores across the board in the different testing scenarios apart from the performance vitals. This is due to the size of images used in the website, which could not be compressed any further or else too much image quality would've been lost.

#### Mobile Home Page Testing
![image](https://github.com/Suth272/Wonder-of-VR/assets/159195438/19bc6026-0c72-4ba6-b074-a75745d1255a)

#### Desktop Home Page Testing
![image](https://github.com/Suth272/Wonder-of-VR/assets/159195438/0aa2fa92-640a-448f-9e4f-7736ad202516)

#### Mobile Sign Up Page Testing
![image](https://github.com/Suth272/Wonder-of-VR/assets/159195438/b8e7f39c-9472-4f83-8561-deae88f284ca)

#### Desktop Sign Up Page Testing
![image](https://github.com/Suth272/Wonder-of-VR/assets/159195438/ca056abc-6a43-4fad-8351-f1263b493bf3)

# Technologies Used

## Languages
+ HTML was used to code the content of the website
+ CSS was used to code the styling of the website

## Frameworks, Libraries & Programs Used
+ [Balsamiq](https://balsamiq.com/wireframes/) - Was used to create the Wireframes for the website
+ [Gimp](https://www.gimp.org) - Was used to compress and manipulate the images
+ [Font Awesome](https://fontawesome.com) - Provided the various icons used in the website
+ [Google Fonts](https://fonts.google.com) - Provided the fonts and VR icon used in the website
+ Chrome Dev Tools - Used extensively to test and debug the website throughout its build.
+ [Virtual Studio Code](https://code.visualstudio.com) -  Used to create and host the website 
+ [Github](https://github.com) - Used to deploy the website
+ [Am I Responsive](https://ui.dev/amiresponsive) - Used to create the image of the home page displaying on multiple screens
+ [Favicon](https://favicon.io/favicon-generator/) - Used to create the icon for the website
+ [Markdown Table Generator](https://www.tablesgenerator.com/markdown_tables) - Used to create the table in the compatibility and responsive testing section
+ [Color Hunt](https://colorhunt.co) - The colour scheme used on the website



# Deployment
The site was deployed to GitHub Pages

## Deploy to GitHub Pages
1. Navigate to the **Settings** tab in the GitHub repository.
![image](https://github.com/Suth272/Wonder-of-VR/assets/159195438/a424d1d1-5d21-406d-a6a5-00ca0674d52b)

2. Once your in the settings, click on the **Pages** link in the left-hand menu.
![image](https://github.com/Suth272/Wonder-of-VR/assets/159195438/600388ef-ef95-47c1-afaf-3474013f00c3)

3.  Under the **Build and Deployment** section, click on **Select Branch** and select **main** in the dropdown menu. Make sure that next to it, the folder is selected to **/root**. Afterwards hit save.
![image](https://github.com/Suth272/Wonder-of-VR/assets/159195438/875c2e42-17bb-4b05-b1cc-e4f4caf4d512)

4. Wait about 5-10 minutes and then refresh the page. The link to the deployed site will show up as it does in the image below.
![image](https://github.com/Suth272/Wonder-of-VR/assets/159195438/4db354be-293d-4af8-bbb7-59424e89d001)

# Credits
## Content
+ The About Us and What is VR sections have been created by me, due to my experience with the content.
+ The Uses of VR section has been taken from [TechTarget](https://www.techtarget.com/whatis/definition/virtual-reality) from the **How can virtual reality be used?** section
+ The collapsible/dropdown navigation bar was taken from the **Love Running** project by **Code Institute**, but the code was tweaked and editted for my website. The repisitory for the **Love Running** project can be found [here](https://github.com/Code-Institute-Solutions/love-running-v3/tree/main)

## Media
+ Hero Image - [Photo by Harsch Shivam from Pexels](https://www.pexels.com/photo/man-wearing-vr-goggles-2007647/)
+ VR Training Use Image - [Photo by Tima Miroshnichenko from Pexels](https://www.pexels.com/photo/man-playing-virtual-reality-game-6498960/0)
+ VR Education Use Image - [Photo by Julia M Cameron from Pexels](https://www.pexels.com/photo/man-in-yellow-crew-neck-t-shirt-using-vr-headset-4144179/)
+ VR Health Use Image - [Photo by RDNE Stock project from Pexels](https://www.pexels.com/photo/man-helping-a-man-play-with-virtual-reality-headset-8097988/)
+ VR Entertainment Use Image - [Photo by Tima Miroshnichenko from Pexels](https://www.pexels.com/photo/a-man-playing-virtual-reality-glasses-6499165/)
+ Icon for the website - [Favicon](https://favicon.io/favicon-generator/)
+ Icons inside the webpage - [Font Awesome](https://fontawesome.com) & [Google Fonts](https://fonts.google.com/icons)
+ FonTS used in the webpage - [Google Fonts](https://fonts.google.com)
## Acknowledgments
+ I would like to acknowledge my mentor **[Malia Havlicek](https://github.com/maliahavlicek)** for all the help, tips and advise during this project.
+ I would like to ackknowledge **Code Institute** for the navigation bar and using their [Love Running](https://github.com/Code-Institute-Solutions/love-running-v3/tree/main) project as a code example.