# 101 UX principles
- **Author**: Will-Grant
- **Genre**: Design, Non-fiction, UI/UX 

# Fonts and typefaces
- Don't use more than two types of fonts in your applications because it will make it harder for the user to concentrate on the text.
- Always use a fallback font if you are using custom fonts through a CDN like google fonts. The fallback will work until the custom font loads.
- Use Headings and sub-headings properly to direct the user to the most important things first. Using a font size of 16px and a line-height of 1.5 is considered the gold standard for text in user-interface design
- Use an ellipsis(...) next to text to convey that there are more options available.

# Buttons and other controls
- While making a button make sure it looks like a proper button. when clicked/touched it should be pressed backwards and should have text like click here, press here, etc...
- Make your buttons big enough so that the user can click them easily. Make the whole button clickable and not just the text.
- Don't invent new controls. There are already a lot of UI controls that you can use in your app like Scroll-bars, check boxes, dials, etc.. Don't make a new control that your users will need to learn first and then use it.
- Slider controls should only be used for Volume, brightness, and color mixing controls and not for a fixed integer value.
- Use drop-down menus only on mobile devices because you can use check boxes on bigger screens.
- The search bar should be labeled with the placeholder of "Search..." and the button should have a magnifying glass icon.Hide the search bar on small screens and only show it when the search button is clicked.
- Always double check a critical action in your app. An e-commerce website should show a pop-up modal containing all the items in the cart before the user confirms his order so that he doesn't order the wrong items.
- Pagination is used for showing a finite number of items. like the products available on a e-commerce website. Infinite scroll is used when you want to show infinite number of items such as social media feeds to keep him addicted to the app.
- Make your links look like links. Make them visually look like a like.
- Split your menu items into sub-categories of seven items each. Because humans cannot remember more than seven items in a list.
- You top navigation should also be repeated in the footer links section. Don't make the footer a deadly-end section and include a search bar or subscribe to newsletter section in it.
- Add filters and sorting order in your apps search to make searching easier for your users.
- If your user is too deep in your apps a great way to show them exactly where they are is using breadcrumbs for navigation.

# Icons and images
- Only use icons that are consistent. Inconsistent icons make the user confused and wastes their time try to include icons only where necessary.
- Each icon has a meaning. don't misplace icons in your UI and don't use out-dated icons for new projects.
- Don't include text "inside" the icon, place your text around the icon not inside it.
- If you want to deliver simple and meaningful icons to your customers just use Emojis. Almost all of your users will be able to recognize emojis.
- Progress bars should be linear and should show an integer value to show much the current task has been completed(20%, 50%...)
- Spinner loading bard should show text below them that says loading... or still loading... This makes the user at ease.

# Forms
- If you are building a form or any type of user-interface make sure to use native-input features. If the form has a field where you have to input an integer make sure to use the on-screen keyboard that is the num-pad rather than the full qwerty keyboard.
- Hide user passwords in the password field using *** or black dots but also provide an icon for him to paste into the password field.
- Don't clear forms automatically. Only perform this action if the user asks for it.
- The size of the input fields in forms matters a lot. make sure a field is not too big or too small for the user.
- Make your forms to ask for as less information as possible. Why does a social media site need a users ZIP code and address?
- If a user logs into your app and forgets his/ her password and clicks on the forgot password link you should auto-fill the recovery email field with his email this makes for better user experience.
- In-app search results should always show the most relatable content on the top and less relatable after that.
- Make it easier for the user to input credit card and postal code address in the forms.
- In your form controls use both placeholders and labels. The label tells the user what to put in this field and the placeholder tells him that how to put it.

# Dumbing down
- Always pick the right user-interface control for the job. If a user wants to check-in use a date and time picker. Radio button for yes or no, check boxes for more than two options. Use pre-built components don't try to invent your own ui components.
- Be careful and forgiving towards your users and make your UI idiot-proof as much as possible and also test it if it can handle edge-cases.
- Don't make uploading images hard. The image picker user-interface should offer two choices, Select a picture from the gallery or open the camera. If you're giving them the option to select an image from the gallery add an option to select multiple images all at once.
- E-commerce apps should a simple 3-step process to make the users process as friction-less as possible.  **See Product > Add to cart > Checkout** This is the best possible process to sell more products from your e-commerce business. Adding another step in between these creates unnecessary friction which diverts the user.
- Terminology in software should not be confusing for the end-user. Make your menu entries like "Sign up" easy to read don't use words like "Log on" because it will just confuse them.

# Validation
- Implement client-side validation in your user interface. Your form should not make a "round-trip" to the server just to validate the correct syntax of an email address.
- Even if you do server-side validation. make sure the user clearly sees it.
- Don't validate phone number on the user-interface, just let the user add his number. on mobile devices use the dedicated num-pad and not the qwerty keyboard.

# Mobile design
- If you have a mobile app, occasionally remind your users for a rating but don't shove it in their throats.
- Create a simple splash screen for your mobile. Don't embed your "Company visions" into the splash screen. Load the app as quick as possible so that the user can do his work.
- Make your app icon or website fav-icon unique and recognizable.
- Try to add a import existing or create from existing workflow in your app has a feature that other apps also have. This makes the user feel at home and makes his on-boarding faster.
- On mobile devices use a slide-in navigation to make users show there are more items in the menu.
- Always save the users position if your app uses infinite scroll because no one wants to keep scrolling forever. 
- Avoid using hamburger menus for less than 5 menu items. You can instead use a bottom or tabbed navigation instead of a hamburger menu.

# Saving data
- If the user does anything that needs to be saved auto save it. If not, tell him through a pop-up modal to save his work or show it in the title bar. "Document-1 (Unsaved)" the asterisk symbol can also be used to show an unsaved document.
- Your users don't know how the file system of their devices works. Make it dead-simple for them to save and retrieve files from their system that your app needs.

# Accessibility 
- Show, don't tell. Create video tutorials about complex UI in your app. Allow users to see and do what they want instead of telling them.
- You app should have a balanced default options that match most of the users default behavior so that they don't fiddle in the settings and just get their work done.
- Try to make your apps UX familiar to a new user so that they carry their previous knowledge and be more productive while using your app
- Make your app simple as possible. The more simple your UX will be the more users will flock to it.
- Designers are trained to invent their own unique way of design and not to copy others. UX designers on the other hand are complete opposite of this law. Your UX should be similar to the most popular app in your niche because it will help new user feel at home.
- Add simple on-boarding illustrations to users dashboards if there are no items in it. (You can show a plus icon and then a add more button.)
- On-boarding or getting started tips sometimes tend to annoy users. Make sure that they are easily dismiss-able.
- Show the last unread message or notification on the top. Give your users the ability to refresh the feed themselves.
- Make your app case-insensitive. "John" and "john" should be displayed same in your UI.	
- The contrast ratio of your text to your background must be 7.5:1 for maximum readability.
- If your app shows a red notification for alerts and green for success messages. It is useless for a user that is blind or visually impaired. The best option is to notify the user through both alerts and sounds.
- If you have a notifications feature in your app make sure the user can customize the amount and frequency of the notifications he receives.
- If your user is new user and is using your app for the first time. make sure there is a "skip this" link on your on-boarding page.
- Hide "Advanced settings" most users. Only give access to the power users to these settings.

# Testing
- AB testing and beta testing is essential for any app to succeed in today's world where a dozen apps exists for a single task. 
- Launch a beta version of your app to a small number of users first and then collect the feedback to improve for the final launch.


