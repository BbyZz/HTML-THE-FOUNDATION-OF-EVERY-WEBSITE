# HTML-THE-FOUNDATION-OF-EVERY-WEBSITE

This document serves as a guide to understanding and recreating a personal webpage using HTML. The webpage is designed to document and display memories through text, images, and interactive elements. It employs fundamental HTML components, such as structured headings, navigation menus, multimedia integration, and forms, to create an engaging user experience. By following this guide, users will be able to develop their own version of the webpage, customize its content, and enhance its features as needed.

![iamge](https://www.oxfordwebstudio.com/user/pages/06.da-li-znate/sta-je-html/sta-je-html.jpg)

## 📋 Requirements
1. A text editor (e.g., VS Code, Notepad++, Sublime Text)

2. A modern web browser (e.g., Chrome, Firefox, Edge)

## 🎯 Objectives
1. Understand the structure and purpose of various HTML elements.

2. Learn how to create a simple, interactive webpage with multimedia content.

3. Gain experience in organizing webpage content using HTML tags.

4. Develop navigation and linking skills for user-friendly web experiences.

5. Customize the design and functionality of their own webpage.

## Part 1: Install your selected IDE (I use VScode)
1. Visit (https://code.visualstudio.com/Download) to download VScode and install it.
2. Launch Visual Studio Code and Select "Open Folder..."
3. Go to a location you would like to store your files.
4. In the top left hover your mouse towards the name of the folder you created
5. then select "New Folder...", type in "assets". Inside the asset folder put a picture that is a good memory for you
6. similar to step 4, now select "New File...", type in "index.html"
7. press "Ctrl + Shift + X" and install the following:
   
    HTML CSS Support by ecmel
   
    HTML Format by Mohamed akram
   
    HTML Preview by George Oliveira
   
    Inline HTML by pushqrdx

   Prettier by Prettier

## Part 2: Coding the head tag
1. type "!" then enter, a boilerplate should appear that will act as your template.
2. Inside the head tag edit your title as you want, this would change the name of the tab when using the a browser.
3. After the title, type "h1" and enter, a new set of tags should appear. Write in a message for everyone to see.
4. After the heading, type "hr" and enter, this creates a thematic line that serves as your seperation.
5. Preview the html by saving with "Ctrl + S" and right clicking the "index.html" tab in VScode and then select "Show in Browser"

## Part 3: Coding the body tag 
1. Type "h3" then enter, in here write another message don't worry you can go back to this later to cusutomize it again.
2. Under the h3 tag, type "p" and enter, follow it by typing "em" then enter, follow it by typing "strong" then enter, lastly follow it again by typing "u" then enter. Then type in "Browse my memories by clicking the arrow!"

  This shows us the application of nesting tags
  
3. Type <br> after "</p>" to provide a line break.
4. Beautify the code by providing ample space. 
5. Save the file and see the changes!

## Part 3: Coding a navigation area
1. Type "div" and enter, then type"details" and enter, then type"summary" and enter, within the "summary tag" type "Fun Moments" and enter, arrange the code so it looks similar to this
![image](https://github.com/user-attachments/assets/903edd49-1b1e-4f8f-80af-513c1f2ab0e8)

2. Below the "Summary Tag", type "nav" then enter, then type"ul" and enter, then type"li" and enter,then type"a" and enter. Arrange the code it should look similar as below.
![image](https://github.com/user-attachments/assets/69d9ba7a-0d1a-4002-935c-60b463431b4e)

3. Within the "a" tag, type "First Memory".
4. then inside the quoation marks after "href", type "index.html#FirstMemory"
   this would link to the section that we will create later making it jump to that certain id.
5. Arrange the code, and it should look like this.
![image](https://github.com/user-attachments/assets/b9ea29bd-d0a8-47f2-b273-a73f1367e169)

## Part 4: Adding our section which will contain images
1. Under the previous "div" tag, type "section" then enter, then type "h2" then enter then put a heading title to describe the images you would like to put in.
2. After the "h2" tag, type "p" then enter, within it put another description.
3. After "p" write a "br" tag to create space for the next element.
4. After "br", type in "img" then enter. "src" and "alt" should appear, within the "src" type "assets/" then enter the picture you want.
5. then in the "alt" write in a description of the image, it will serve as an alternative output if the image is not loaded.
6. then inside the "img" tag, type in "style" then enter, followed by "height" then enter, then enter a value of "200px". Customize it as you want
7. Arrange the code it should look similar to this
   ![image](https://github.com/user-attachments/assets/fd9b4b91-9656-4047-87ca-5b5a9c49d76b)
8. then under the "img" tag, type "p" then enter, within it add another message.
9. then go back to the "section" tag, and inside it type "id="FirstMemory"".
10. arrange the code, it should look similar to this
![image](https://github.com/user-attachments/assets/b58daefd-ad81-426b-9ea8-c74eb2319b02)

 11. save the html file then check the preview in the browser
![image](https://github.com/user-attachments/assets/00e45ce1-4d92-492b-9687-ccb5636bc6fb)




## Part 5: Adding div as spacers

now to use our navigation area that we created earlier we are goiing to add spacers
this will be added before and after our section tag
1. type "div" then enter, inside of the opening tag of "div" type in "style" then enter, type "marging-bottom" then enter a value of "1000px"
2. add this before and after the "section" tag to create space
3. it should look like this
![image](https://github.com/user-attachments/assets/42696b56-5e2d-4761-b2b3-0cdecab09a10)
4. then save the file and browse the changes in the browser.






















































































   
