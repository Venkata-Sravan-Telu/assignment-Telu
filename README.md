# My name iS Venkata Sravan Telu

### My favorate museum is Indian Museum Kolkata in India

This is a museum **founded in 1814**. This museum has unique artifacts of **mughal paintings, armors and their ornaments**.

---

## Travel Directions

The nearest airport to the museum is Netaji Subhash Chandra Bose International Airport
The steps to arrive to Indian Museum Kolkata are
1. Arrive to Netaji Subhash Chandra Bose International Airport
2. Then outside of the airport, you will be see taxi services like Uber or Ola
3. Take a taxi and you can reach the destinated museum.

If you want to visit near by places you can go to
* Victoria Memorial
* Indian Police Museum
* Howrah Bridge


**[AboutMe](https://github.com/Venkata-Sravan-Telu/assignment-Telu/blob/main/AboutMe.md)**

---

## Tables

In this section, I'm going to recommend 4 cities to visit.

| City | Important Location | Amount of time |
| :--- |    ---             |   ---          |
|New Delhi | Qutub Minor    |   1 day        |
|Hyderabad | Charminar      |   1 day        |
|Chennai   |  Beach         |   2 days      |
|Jaipur    |    Forts       |   3 days      |

---

## Quote 

> You must be the change you wish to see in the world *Mahatma Gandhi*

> Strive not to be a success, but rather to be of value *Albert Einstein*

---

## Code fencing

> How to safely store SVGs in a database and deliver as downloads?

[Stack overflow](https://stackoverflow.com/questions/73616108/how-to-safely-store-svgs-in-a-database-and-deliver-as-downloads)

```
<svg width="100%" height="100%">
  
  <!-- Create mask that we'll use to define a slight gradient -->
  <mask maskUnits="userSpaceOnUse" id="fade">
    <!-- Here's that slight gradient -->
     	<linearGradient id="gradient" x1="0" y1="0" x2="0" y2="100%">
      <stop offset="0" style="stop-color: #FFFFFF"></stop>
      <stop offset="1" style="stop-color: #000000"></stop>
    </linearGradient>
    <!-- The canvas for our mask -->
    <rect fill="url(#gradient)" width="100%" height="100%"></rect>
  </mask>
    
  <!-- Let's define the pattern -->
  <!-- The width and height should be double the circle radius we plan to use -->
  <pattern id="pattern-circles" x="0" y="0" width="40" height="40" patternUnits="userSpaceOnUse">
    <!-- Now let's draw the circle -->
    <!-- We're going to define the `fill` in the CSS for flexible use -->
    <circle mask="url(#fade)" cx="20" cy="20" r="20"></circle>
  </pattern>
  <!-- The canvas with our applied pattern -->
  <rect x="0" y="0" width="100%" height="100%" fill="url(#pattern-circles)"></rect>
  
</svg>
```

[linktocsstricks](https://css-tricks.com/snippets/svg/svg-patterns/)