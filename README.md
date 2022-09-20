## Setup

---

## Task
### Function One
- Define a function called `padel_court_cost` 
- This function has two arguments, `hours` and `court_type`
- If the `court_type` is indoors, the padel court costs 30 KWD per hour.
- If the court_type is outdoors, the padel court costs 20 KWD per hour.
- The function calculates the padel court cost and returns it.
- BONUS: If the number of hours is three or more, the cost will be reduced by 20%.

### Function Two
- Define a function called `rackets_cost`
- This function has one arguments `racket_brand`, which is a string
- The function should return a different price depending on the racket brand. Below are the valid rackets and their corresponding prices.
- Bullpadel: 50 KWD
- Wilson: 110 KWD 
- Adidas: 235 KWD

### Function Three
- Define a function called `padel_balls_cost`
- It has an argument called `ball_boxes`. 
- Calculate the cost of buying ball boxes
- Every box costs 2 KWD.
- If you buy two boxes, it will cost 3.5 KWD.
- If you buy three boxes, it will cost 5 KWD.
- Return that cost.

### Function Four
- Define a function called `padel_game_cost` 
- It takes no arguments 
- In the function ask the user to enter the following:
  - number of hours
  - the court type 
  - racket brand
  - number of ball boxes
- Have your function return the sum of calling the previous functions.
- Print out the game cost for the following game:
  - hours: 3
  - court_type: "indoors"
  - racket_brand: "Adidas"
  - ball_boxes: 2
