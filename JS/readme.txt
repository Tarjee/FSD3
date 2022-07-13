1. variables

var 
let
const


camecase: lastNameIs
pascalcase: MyNmaeIs , LastNameIs


name      length    position/index

F           1         0
a           2         1
i           3         2
z           4         3
a           5         4



/////////////
1.Math operations
2.Escape characters
3.Concat
4.Conditionals if...else
5.Functions
6.Arrays
7.switch
8.objects
9.while , do while loop
10. generate random number
11.Ternary operator
12.Mutations
13. Destructure , spread , rest
14. Date
15. Assignments




/////////
1.while, do while
2. Destructure , spread , rest,array methods
3. Random number
4.Date
5.String methods, object methods
6. Deep copy and shallow copy
7.DOM manipulation
     - access html from js
       - id, class, 
     - modify html and css from js
     - event handling
     - create html and css from js

8. Single thread, async
9.promises
10. fetch
11. XML
12.API
13.AJAX
14.HTTP request
15. HTML5 API - drag drop




JS Assignment:

1. create html file, script tag
2. Create array of objects- 5objects
Ex: let contacts = [
     {
firstName : 'string'
    lastName : 'string'
    phoneNo : number
    likes : ['','','','']
     },
     {

     }
]
3. object will have properties :

    - firstName : 'string'
    - lastName : 'string'
    - phoneNo : number
    - likes : ['','','','']

4. create a function findContact . This function will take 2 parameters
    - name 
    - prop
5. If provided firstName exists in your array object
    if firstName does exists then find if the given property (prop) exists for the same object
        if property exists then return the value of that property
        if firstName value exists and property(prop) does not exists then return 'No property found'
    if firstName does not exists then retrun 'No such contact'


findContact('pooja','phoneNo') 
findContact('firstName value from the object' ,'property of the object')


//////////////////
DOM - Document Object Model(represention of object)
document

const webpage = {
    p:{
        color: 'green'
    }
    h1:'',
    color: 'red'
}

1. Access elements from html
       -  getElementById()
            - if present returns elements
            - if no exists return null

        - getElementsByClassName()
            - if exists - return collection of elements - array of all the elements - 0
       
        - getElementsByTagName()
            - if exists - return collection of elements - array of all the elements - 0

     
        - getElementsByName()   
           - if exists - return collection of elements - array of all the elements - 0


2. Create new elements
        - createElement and appendChild or append

3. Access 
      - querySelector()  - .class , #id  , tag
      - querySelectorAll() - .class , #id  , tag
      4. Create new attribute
        - createAttribute() and setAttributeNode()

4.create new attribute
       - createAttribute and setAttributeNode()

5. append