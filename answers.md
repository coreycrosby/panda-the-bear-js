<!-- PART 1 -->
<!-- 1. -->
document.querySelector('.profile-image')
var profileImage = document.querySelector('.profile-image')
profileImage.src = "https://placebear.com/200/300"

<!-- 2. -->
var portfolioImage = document.querySelector('#left-image.portfolio-image img')
portfolioImage.src = "images/pikachu-drawing.jpg"

<!-- 3. -->
var title = document.querySelector('h1.highlight')
title.innerText = "Corey"

<!-- 4. -->
var infoTitle = document.querySelector('#employment.info-inner-container h3.info-title')
infoTitle.innerText = "Unemployment"

<!-- 5. -->
var body = document.querySelector('body')
body.style.color = "red"

<!-- 6. -->
var highlight = document.querySelectorAll('.highlight')
highlight.forEach((h) => h.style.color = "yellow")

<!-- 7. -->
var h1 = document.querySelector('h1')
h1.style.fontFamily = "monospace"

<!-- 8. -->
let iconBgs = document.querySelectorAll('a.action-icon-bg')
iconBgs.forEach((icon) => icon.style.backgroundColor = "black")

<!-- 9. -->
document.querySelector('#name.contact-info').placeholder = 'Identify Yourself'

<!-- 10. -->
document.querySelector('#message').placeholder = 'State your Business'

<!-- 11. -->
document.querySelector('#name.contact-info').value = 'your nemesis'
"your nemesis"

<!-- 12. -->
document.querySelector('#email.contact-info').placeholder = 'koalathebear@gmail.com'

<!-- 13. -->
document.querySelector('#submit').value = 'En garde!'

<!-- 14. -->
document.querySelector('#submit').disabled = true

<!-- 15. -->
document.querySelector('.bio-info').parentNode.removeChild(document.querySelector('.bio-info'))

<!-- #PART 2 -->
<!-- 1. -->
document.querySelector('#time-travel').parentNode.removeChild(document.querySelector('#time-travel'))

<!-- 2. -->
img = document.querySelector('#right-image.portfolio-image img').cloneNode();document.querySelector('portfolio-container').appendChild(img);

<!-- 3. -->
for (i = 0; i < 10; i++) { img = document.querySelector('#right-image img').cloneNode(); document.querySelector('.portfolio-container').appendChild(img); }

<!-- 4. -->
const listItem = document.createElement('li'); const leftSpan = document.createElement('span'); var lastUpdated = document.createTextNode('Page last updated on'); leftSpan.appendChild(lastUpdated); listItem.appendChild(leftSpan); const rightSpan = document.createElement('span'); let date = document.createTextNode(new Date); rightSpan.appendChild(date); listItem.appendChild(rightSpan); const sidebar = document.querySelector('.bio-info'); sidebar.appendChild(listItem);

