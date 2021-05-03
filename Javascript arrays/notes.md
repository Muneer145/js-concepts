- Arrays allow us to group data together
- it is an ordered collection of values 
- examples include a list of comments on an ig post, songs in a playist etc

Creatign arrays 
- to make an empty array  
   let students =[];

- an array of strings 
   let students=["dave","goku","ben"];

- an array of numbers
   let students=[1,2,3,4];

- a mixed array 
  let students=[true,"cat",12,null]
 

- Arrays are indexed and start counting from 0
- Arrays can be modified
  let days=['Monday','Tuesday','Wednesday','Thursday','Saturday']
  days[4]='Friday';
  calling days will not show Monday-Friday
- You can target whatever you want on arrays using its indices
  days[2][1] (calling this will first pick "Wednesday" then select "e" from wednesday)
  

Array methods
 - push-adds to the end
 - pop-removes from the end 
 - shift-remove from the start 
 - unshift- add to the start 
   eg array.push
- concat-merge arrays
- includes-look for a value
- indexOf-just like string.indexOf
- join-creates a string from an array
- reverse-reverses an array
- slice- copies a portion on an array
- splice-removes/replaces elements 
- sort-sorts an array 

- when using concat, it doesn't store what you concatenated in the original array, you have to store what you're concatenating into a new variable
- includes is a boolean array method. It returns true or false

- reverse is a destructive array(it will change the original array)

- with slice.(start,end), what we set as the the start and end will determine what is copied into a new array
 
  e.g let days=['Monday','Tuesday','Wednesday','Thursday','Saturday']

        days.slice(0,3) will return ['Monday','Tuesday','Wednesday]
        days.slice(1) will return['Tuesday','Wednesday','Thursday','Saturday']
- using a negative index will start the counting from the other direction.

- for splice(1,0,"text"), 1-denotes where you want to start, 0-denotes what you want to delete, text- denotes what you want to replace 