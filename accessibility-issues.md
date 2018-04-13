# Accessibility Issues

## 1. Perceivable
### 1.1 Text Alternatives
#### 1.1.1 Non-text Content - A
* F3: Failure of Success Criterion 1.1.1 due to using CSS to include images that convey important information
* F13: Failure of Success Criterion 1.1.1 and 1.4.1 due to having a text alternative that does not include information that is conveyed by color differences in the image
* F20: Failure of Success Criterion 1.1.1 and 4.1.2 due to not updating text alternatives when changes to non-text content occur
* F30: Failure of Success Criterion 1.1.1 and 1.2.1 due to using text alternatives that are not alternatives (e.g., filenames or placeholder text)
* F38: Failure of Success Criterion 1.1.1 due to not marking up decorative images in HTML in a way that allows assistive technology to ignore them
* F39: Failure of Success Criterion 1.1.1 due to providing a text alternative that is not null (e.g., alt="spacer" or alt="image") for images that should be ignored by assistive technology
* F65: Failure of Success Criterion 1.1.1 due to omitting the alt attribute or text alternative on img elements, area elements, and input elements of type “image"
* F67: Failure of Success Criterion 1.1.1 and 1.2.1 due to providing long descriptions for non-text content that does not serve the same purpose or does not present the same information
* F71: Failure of Success Criterion 1.1.1 due to using text look-alikes to represent text without providing a text alternative
* F72: Failure of Success Criterion 1.1.1 due to using ASCII art without providing a text alternative

* The image is not a purely decorative image and does not have a text alternative.
* The text alternative does not convey the same information or function as the non-text content.
* An image uses colour differences to convey information, but the text alternative does not include the information conveyed by colour in the image.
* The text alternative is not an alternative, e.g. it is a filename or generic placeholder text.
* The text alternative of non-text content that serves as a CAPTCHA does not identify it as a CAPTCHA.

### 1.2 Time-based Media
#### 1.2.1 Audio-only and Video-only (Prerecorded) - A
#### 1.2.2 Captions (Prerecorded) - A
* F8: Failure of Success Criterion 1.2.2 due to captions omitting some dialogue or important sound effects
* F74: Failure of Success Criterion 1.2.2 and 1.2.8 due to not labeling a synchronized media alternative to text as an alternative
* F75: Failure of Success Criterion 1.2.2 by providing synchronized media without captions when the synchronized media presents more information than is presented on the page

#### 1.2.3 Audio Description or Media Alternative (Prerecorded) - AA
#### 1.2.4 Captions (Live) - AA
#### 1.2.5 Audio Description (Prerecorded) - AA
#### 1.2.6 Sign Language (Prerecorded) - AAA
#### 1.2.7 Extended Audio Description (Prerecorded) - AAA
#### 1.2.8 Media Alternative (Prerecorded) - AAA
#### 1.2.9 Audio-only (Live) - AAA

###1.3 Adaptable
#### 1.3.1 Info and Relationships - A
* F2: Failure of Success Criterion 1.3.1 due to using changes in text presentation to convey information without using the appropriate markup or text
* F33: Failure of Success Criterion 1.3.1 and 1.3.2 due to using white space characters to create multiple columns in plain text content
* F34: Failure of Success Criterion 1.3.1 and 1.3.2 due to using white space characters to format tables in plain text content
* F42: Failure of Success Criteria 1.3.1, 2.1.1, 2.1.3, or 4.1.2 when emulating links
* F43: Failure of Success Criterion 1.3.1 due to using structural markup in a way that does not represent relationships in the content
* F46: Failure of Success Criterion 1.3.1 due to using th elements, caption elements, or non-empty summary attributes in layout tables
* F48: Failure of Success Criterion 1.3.1 due to using the pre element to markup tabular information
* F87: Failure of Success Criterion 1.3.1 due to inserting non-decorative content by using :before and :after pseudo-elements and the 'content' property in CSS
* F90: Failure of Success Criterion 1.3.1 for incorrectly associating table headers and content via the headers and id attributes
* F91: Failure of Success Criterion 1.3.1 for not correctly marking up table headers
* F92: Failure of Success Criterion 1.3.1 due to the use of role presentation on content which conveys semantic information


#### 1.3.2 Meaningful Sequence - A
* F1: Failure of Success Criterion 1.3.2 due to changing the meaning of content by positioning information with CSS
* F32: Failure of Success Criterion 1.3.2 due to using white space characters to control spacing within a word
* F49: Failure of Success Criterion 1.3.2 due to using an HTML layout table that does not make sense when linearised

#### 1.3.3 Sensory Characteristics - A
* F14: Failure of Success Criterion 1.3.3 due to identifying content only by its shape or location
* F26: Failure of Success Criterion 1.3.3 due to using a graphical symbol alone to convey information

###1.4 Distinguishable
#### 1.4.1 Use of Color - A
* F73: Failure of Success Criterion 1.4.1 due to creating links that are not visually evident without color vision
* F81: Failure of Success Criterion 1.4.1 due to identifying required or error fields using color differences only

#### 1.4.2 Audio Control - A
* F23: Failure of 1.4.2 due to playing a sound longer than 3 seconds where there is no mechanism to turn it off
* F93: Failure of Success Criterion 1.4.2 for absence of a way to pause or stop an HTML5 media element that autoplays

#### 1.4.3 Contrast (Minimum) - AA
* F24: Failure of Success Criterion 1.4.3, 1.4.6 and 1.4.8 due to specifying foreground colors without specifying background colors or vice versa
* F83: Failure of Success Criterion 1.4.3 and 1.4.6 due to using background images that do not provide sufficient contrast with foreground text (or images of text)

#### 1.4.4 Resize text - AA
* F69: Failure of Success Criterion 1.4.4 when resizing visually rendered text up to 200 percent causes the text, image or controls to be clipped, truncated or obscured
* F80: Failure of Success Criterion 1.4.4 when text-based form controls do not resize when visually rendered text is resized up to 200%

#### 1.4.5 Images of Text - AA
#### 1.4.6 Contrast (Enhanced) - AAA
#### 1.4.7 Low or No Background Audio - AAA
#### 1.4.8 Visual Presentation - AAA
* F88: Failure of Success Criterion 1.4.8 due to using text that is justified (aligned to both the left and the right margins)

#### 1.4.9 Images of Text (No Exception) - AAA

## 2. Operable
### 2.1 Keyboard Accessible
#### 2.1.1 Keyboard - A
* F54: Failure of Success Criterion 2.1.1 due to using only pointing-device-specific event handlers (including gesture) for a function
* F55: Failure of Success Criteria 2.1.1, 2.4.7, and 3.2.1 due to using script to remove focus when focus is received

#### 2.1.2 No Keyboard Trap - A
* F10: Failure of Success Criterion 2.1.2 and Conformance Requirement 5 due to combining multiple content formats in a way that traps users inside one format type

#### 2.1.3 Keyboard (No Exception) - AAA

###2.2 Enough Time
#### 2.2.1 Timing Adjustable - A
* F40: Failure of Success Criterion 2.2.1 and 2.2.4 due to using meta redirect with a time limit
* F41: Failure of Success Criterion 2.2.1, 2.2.4, and 3.2.5 due to using meta refresh to reload the page
* F58: Failure of Success Criterion 2.2.1 due to using server-side techniques to automatically redirect pages after a time-out

#### 2.2.2 Pause, Stop, Hide - A
F4: Failure of Success Criterion 2.2.2 due to using text-decoration:blink without a mechanism to stop it in less than five seconds
F7: Failure of Success Criterion 2.2.2 due to an object or applet, such as Java or Flash, that has blinking content without a mechanism to pause the content that blinks for more than five seconds
F47: Failure of Success Criterion 2.2.2 due to using the blink element
F50: Failure of Success Criterion 2.2.2 due to a script that causes a blink effect without a mechanism to stop the blinking at 5 seconds or less
F16: Failure of Success Criterion 2.2.2 due to including scrolling content where movement is not essential to the activity without also including a mechanism to pause and restart the content

#### 2.2.3 No Timing - AAA
#### 2.2.4 Interruptions - AAA
#### 2.2.5 Re-authenticating - AAA
F12: Failure of Success Criterion 2.2.5 due to having a session time limit without a mechanism for saving user's input and re-establishing that information upon re-authentication

###2.3 Seizures
#### 2.3.1 Three Flashes or Below Threshold - A
#### 2.3.2 Three Flashes - AAA

### 2.4 Navigable
#### 2.4.1 Bypass Blocks - A
#### 2.4.2 Page Titled - A
* F25: Failure of Success Criterion 2.4.2 due to the title of a Web page not identifying the contents

#### 2.4.3 Focus Order - A
* F44: Failure of Success Criterion 2.4.3 due to using tabindex to create a tab order that does not preserve meaning and operability
* F85: Failure of Success Criterion 2.4.3 due to using dialogs or menus that are not adjacent to their trigger control in the sequential navigation order

#### 2.4.4 Link Purpose (In Context) - AA
* F63: Failure of Success Criterion 2.4.4 due to providing link context only in content that is not related to the link
* F89: Failure of Success Criteria 2.4.4, 2.4.9 and 4.1.2 due to not providing an accessible name for an image which is the only content in a link


#### 2.4.5 Multiple Ways - AA
#### 2.4.6 Headings and Labels - AA
#### 2.4.7 Focus Visible - AA
* F78: Failure of Success Criterion 2.4.7 due to styling element outlines and borders in a way that removes or renders non-visible the visual focus indicator

#### 2.4.8 Location - AAA
#### 2.4.9 Link Purpose (Link Only) - AAA
* F84: Failure of Success Criterion 2.4.9 due to using a non-specific link such as "click here" or "more" without a mechanism to change the link text to specific text.

#### 2.4.10 Section Headings - AAA

## 3. Understandable
### 3.1 Readable
#### 3.1.1 Language of Page - A
#### 3.1.2 Language of Parts - AA
#### 3.1.3 Unusual Words - AAA
#### 3.1.4 Abbreviations - AAA
#### 3.1.5 Reading Level - AAA
#### 3.1.6 Pronunciation - AAA

### 3.2 Predictable
#### 3.2.1 On Focus - A
* F52: Failure of Success Criterion 3.2.1 and 3.2.5 due to opening a new window as soon as a new page is loaded

#### 3.2.2 On Input - A
* F36: Failure of Success Criterion 3.2.2 due to automatically submitting a form and presenting new content without prior warning when the last field in the form is given a value
* F37: Failure of Success Criterion 3.2.2 due to launching a new window without prior warning when the selection of a radio button, check box or select list is changed

#### 3.2.3 Consistent Navigation - AA
* F66: Failure of Success Criterion 3.2.3 due to presenting navigation links in a different relative order on different pages

#### 3.2.4 Consistent Identification - AA
* F31: Failure of Success Criterion 3.2.4 due to using two different labels for the same function on different Web pages within a set of Web pages

#### 3.2.5 Change on Request - AAA
* F9: Failure of Success Criterion 3.2.5 due to changing the context when the user removes focus from a form element
* F22: Failure of Success Criterion 3.2.5 due to opening windows that are not requested by the user
* F60: Failure of Success Criterion 3.2.5 due to launching a new window when a user enters text into an input field
* F61: Failure of Success Criterion 3.2.5 due to complete change of main content through an automatic update that the user cannot disable from within the content

### 3.3 Input Assistance
#### 3.3.1 Error Identification - A
#### 3.3.2 Labels or Instructions - A
* F82: Failure of Success Criterion 3.3.2 by visually formatting a set of phone number fields but not including a text label

#### 3.3.3 Error Suggestion - AA
#### 3.3.4 Error Prevention (Legal, Financial, Data) - AA
#### 3.3.5 Help - AAA
#### 3.3.6 Error Prevention (All) - AAA

## 4. Robust
#### 4.1 Compatible
#### 4.1.1 Parsing - A
* F70: Failure of Success Criterion 4.1.1 due to incorrect use of start and end tags or attribute markup
* F77: Failure of Success Criterion 4.1.1 due to duplicate values of type ID

#### 4.1.2 Name, Role, Value - A
* F15: Failure of Success Criterion 4.1.2 due to implementing custom controls that do not use an accessibility API for the technology, or do so incompletely
* F59: Failure of Success Criterion 4.1.2 due to using script to make div or span a user interface control in HTML without providing a role for the control
* F79: Failure of Success Criterion 4.1.2 due to the focus state of a user interface component not being programmatically determinable or no notification of change of focus state available
* F86: Failure of Success Criterion 4.1.2 due to not providing names for each part of a multi-part form field, such as a US telephone number
* F68: Failure of Success Criterion 4.1.2 due to a user interface control not having a programmatically determined name

