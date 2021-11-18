# ClonedGmail

Google Mail's Homepage entirely built with HTML5, CSS3, and SCSS.

# Custom colors (Sass)

$hover-color: #f1f3f4;
$bottom-color: #b1adad;
$svg-color: invert(39%) sepia(11%) saturate(236%) hue-rotate(174deg)
  brightness(93%) contrast(88%);
$icons-color: #5f6368;
$compose-shadow: 0 1px 2px 0 rgba(60, 64, 67, 30%),
  0 1px 3px 1px rgba(60, 64, 67, 15%);
$shadow-design: 0 2px 0 rgba(0, 0, 0, 0.1), 0 0 0px rgba(65, 63, 63, 0.5);
$other-shadow: 0 0 4px rgba(0, 0, 0, 0.1), 0 0 6px rgba(0, 0, 0, 0.2);
$mailcount-bg: rgba(0, 0, 0, 0.2);

# Abstract mailing list (when hovered on the mail container

.maincontainer--mailinglist .mailinglist--right {
color: #5f6368;
display: flex;
justify-content: space-evenly;
align-self: center;
font-size: 17px;
display: none;
transition: 0.3s;
}
.maincontainer--mailinglist:hover .mailinglist--right {
color: #5f6368;
display: flex;
flex-basis: 15%;
justify-content: space-evenly;
align-self: center;
font-size: 17px;
padding-right: 0.1rem;
transition: 0.3s;
}

# Font style

"Roboto"
[Live Site on Netlify](http://)
