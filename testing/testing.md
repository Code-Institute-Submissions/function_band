# The Function Band

[Back to main README file](https://github.com/aprilha3097/function_band/blob/master/README.md)

## Testing

### Testing Matrix
The overall site has achieved the intended purpose and design. The attached [testing matrix](https://github.com/aprilha3097/function_band/blob/master/testing/user_testing.pdf) on responsivness and browser compatibility outlines the various tests implemented. Below is a more detailed outline of Functionality, Usabillity and Compatability testing. 

### Functionality Testing
Features have been tested and work to its intended purposes. Below outlines the intial design of features, issues found from the oringal features and the resolution to those issues that I have come across during the development of this site. 

#### Navigation Bar: 

<strong>Initial Feature:</strong> 
* The Home and About pages had sticky/fixed navigation bar that scrolled along with the site
* The Gallery and Contact pages, the navigation bar was not fixed to the top of the site and did not scroll when the site scrolled

<strong>Issue Found:</strong>
* Inconsisteny in style
* Users would not be able to re-direct to other sites from the Gallery and Contact page wihout having to scroll to the top of the page
* Text color blended with the white background color of the site making it difficult to read the navigation text when scrolling through 

<strong>Resolution:</strong>
* Added a light grey transparent background color for text to sit on, so text is always easy to read
* Navigation bar is now easy to access as well as to read at each scrolling point of the site

#### Buttons and Links: 

<strong>Initial Feature:</strong>
* Navigation Links: Site re-directs to the corrected pages with `target` not set 
* Call to Action Button: Site re-directs to the form with `target` not set
* Get in Touch Link: Site re-directs to the form on a new tab with `target="_blank"` set
* Form Submit Button: When form is complete and submitted, this will not direct to anywhere as `action="#"`
* Footer Navigation: Links to other pages re-direct to corrected pages with `target` set to `target="_blank"` 
* Footer Trustpilot: Trustpilot link re-directs to Trustpilot site in a new tab with `target` set to `target="_blank"` 

<strong>Issues Found:</strong>
* Form Submit Button: When form is submitted, site does not re-direct as `action` is set to `action="#"` and directs to a 405 Not Allowed page on the GitHub Pages deployed version of site

#### Video: 
<strong>Initial Feature:</strong>
* Video is linked to Youtube and plays video from The Function Band

<strong>Issues Found:</strong>
* Video was not responsive. HTML Validtor did not accept the embeded width and height Youtube has originally set as it was incorrect 

<strong>Resolution:</strong>
* Width and height of video was set manually in CSS to be responsive 

#### Gallery: 
<strong>Initial Feature:</strong>
* CSS grid is active to compile the group of images into 2 columns of various sizes

<strong>Issues Found:</strong>
* A large gap at the bottom of the page did not align straight against the footer
* It looked as if a photo was unable/failed to load 

<strong>Resolution:</strong>
* I re-sized several images for the photos to end in a straight line at the bottom of the page. I re-sized the actual media and re-freshed the HTML page and site

#### Form: 
<strong>Initial Feature:</strong>
* First Name, Last Name, and Email text field are required so the `required` tag is set
* Form will not submit unless all three required elements are correctly inputed and an error will flag which elements are required for successful submission of form
* Email input type is set as `type="email"`, so form is unable to be submitted wihtout the '@' in the email address
* Text area is available for users to write in message box

<strong>Issues Found:</strong>
* Message box did not have a fixed height. The box would overflow out of the form to the end of the page

<strong>Resolution:</strong>
* `min-height: 100px;` and `max-height: 200px;` are set in CSS to stop textarea from overflowing 

### Usability 

The features of the site are useable and intuitive. 
* Navigation Bar: This feature follows users as they navigate through the site. This is a standard feature amoung websites. Competitor sites have a similar feature to allow users to easily naviagate to other pages
* Links: Links that navigate through the site inherit the hover effect. This gives instant and intuitive feedback to users that the text they are hovering over is an active link the re-directs to another page
* Navigation `Active`: The navigation class is set to `class="active"`, so users are able to identify which page that they are currently on. This is a Boostrap active class.

The site is comparable to competitors sites. These sites all follow similar guidelines to user experiences. I've compared my site to these: 
* [The Function Band](https://www.thefunction.band/)
* [Brand New Groove](https://www.brandnewgroove.co.uk/)

Test users (friends and family) were able to test the site on their personal devices. They were able to navigate the site easily and was able to successfully navigate to the contact form via the various links provided throughout the site. I recieved positive feedback on the overall usability.

### Compatibility and Responsiveness
I used Google Chrome Inspect tool to test responsiveness of the site in the varied mobile states. I have also had users to test the mobile versions of this site on their personal devices. 

#### Browser Compatibility
The site was tested on these sites with a variety of success: 
* Google Chrome
* Safari 
* Edge
* Internet Explorer
* Firefox

#### Noted Issues
* CSS Grid is not supported on Safari. The gallery page was not fixed to the 2 coloumn style rule that was implemented
* The height of images were stretched when viewing Microsoft Edge 


