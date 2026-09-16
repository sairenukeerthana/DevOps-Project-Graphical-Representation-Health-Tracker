Heal - Graphical Representation Health Tracker 

**Heal** is a privacy-first wellness app that helps users track mental and physical health alongside their menstrual cycle. By logging daily wellness and visualizing patterns, Heal enables users to recognize connections between mental state, physical health, and cycle phases—helping them:

Understand their body better
Predict mood/energy patterns
Share data with healthcare professionals
Optimize daily life based on cycle phases
Maintain complete privacy (device-only storage)

the current application in the main branch works on:

HTML5 - Semantic markup & structure
CSS3 - Styling, gradients, responsive design
Vanilla JavaScript (ES6+) - Application logic
Chart.js - Data visualization (included via CDN)
LocalStorage API - Client-side data persistence

Hence the data flow is:

User
 ↓
Heal HTML page
 ↓
JavaScript
 ↓
Browser localStorage
 ↓
Chart.js displays the data

the wellness entries are saved using the code:
localStorage.setItem('wellnessData', JSON.stringify(data));

**Installation Instructions**
directly download the file, and you can start using it without worrying about data privacy.
the file will open in the browser such as Microsoft edge or chrome.














 


















Happy building! 🚀
