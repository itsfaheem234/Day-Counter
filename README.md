# 🚀Day Counter
I built a countdown timer web app from scratch using HTML, CSS, and JavaScript

# 📸Overview
A dynamic countdown timer that tracks the days, hours, minutes, and seconds until a particular event with a rotating motivational quote.

# 📸Preview
Screenshot of The Countdown Page
<img src="ss.png" alt="Countdown Screenshot" width="600"/>

# 🎯Why I Built This
I created this project as a fun way to practice my coding skills and build something I can actually use every day.

# Technologies Used

1)HTML5 - Structure of the page

2)CSS3 - Styling, gradients, and responsive design

3)JavaScript - Countdown logic, DOM manipulation, and quote rotation

# 📂How to Run this Locally

1)**Clone the repository**

*git clone https://github.com/[yourusername]/countdown-timer.git*

2)**Navigate to the project folder**

*cd countdown-timer*

3)**Open the file**

Simply double click on the saved file or right click and then click "Open with" and choose your favorite browser

# ✨Features

1)⏰ Real-time countdown updated every second

2)🔧 Easy to customize - just change the target date in the JavaScript

3)📱 Fully responsive - looks great on both desktop and mobile

# 🔧How to Customize It

1. **Change target date**

Date is set to Aug 1st,2026 at 12pm. In order to change the date:

Open saved file, then go to line 142 and update:

*const targetDate = new Date(2026, 5, 1, 12, 0, 0);* 

*// Year, Month (0-11), Day, Hour, Minute, Second*

2. **Modify quotes**

Scroll to line 146 and then modify quotes array:
const quotes = *[
    "Your quote here",
    "Another awesome quote"
]:*

3. **Change colours**
   
Find the CSS on line ~27 and update the gradient or accent colors.

# 🚀 Deployment

This project is deployed using GitHub Pages. To deploy your own version:

1)Fork this repository

2)Go to Settings → Pages

3)Select the main branch and save

4)Wait 2 minutes, and then the site is live.

# 📚 What I Learned

1)How to work with JavaScript's Date object and time calculations

2)How to manipulate the DOM to update content dynamically

3)How to use setInterval() for real-time updates

4)How to deploy a static site with GitHub Pages

5)The importance of writing clean, commented code

# 🌟 Future Improvements

Here's what I'd add next to keep learning:

□ Add a "dark mode / light mode" toggle

□ Let users set their own target date with a date picker

□ Add confetti animation when the countdown hits zero

□ Save the target date in localStorage so it persists

# 🙌 Acknowledgments
Built as a personal project during my 12th grade year

# 📝 License
This project is open source and available under the ***MIT License.***

**Made by Faheem Mohammed Shabeer**
Instagram -> ***@its.faheem234***
