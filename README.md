# Playtime! 🎳 / Drills 📋

One of the ways that I learn best is by playing around with things and then also by doing drills (I still swim drills in the pool, for example). 

So, that is what I am going to do on this branch! 

## 2018

* How many rides have I taken?

   As of now, there's no ride count available on SoulCycle. You just have to scroll your ride history and count individually. That's prone to miscounting, so I opened the browser Console and started trying things. This definitely wants refactoring, but it got me there, so. !
   
   ```
   let myRides = Object.values(document.getElementsByClassName("bike-number"));
   // filter the Array by the presence of the word "bike"
   // because myRides.length shows all the classes *booked* but only those with "bike"
   // are classes I attended
   const ridesTaken = myRides.filter(bike => bike.innerText.includes('bike'));
   ridesTaken.length
   ```


## 2017

### December

* [JS: .map()](javascript-map.html), [Chrome console log of me playing around with `const hogsmeade`](jsmap-hogsmeade.txt)
