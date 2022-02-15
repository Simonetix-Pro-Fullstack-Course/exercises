Components | CreditCard
Create a CreditCard component that displays a square with a background color based on props. For this. You will need a styled component.

It takes 8 props:

type: A string that can be "Visa" or "Master Card"
number: A string that is number of the credit card. You will only display the 4 last digits for security reasons 😉
expirationMonth: A number that represents the month, between 1 and 12
expirationYear: A number that represents the year
bank: A string that represents the name of the bank
owner: A string the reprensents the name of the owner
bgColor: A string for the background color of the card
color: A string for the text color of the card
Take your time to do as close to the output. You probably have to use flexbox.

Example

<CreditCard 
  type="Visa"
  number="0123456789018845"
  expirationMonth={3}
  expirationYear={2021}
  bank="BNP"
  owner="Maxence Bouret"
  bgColor="#11aa99"
  color="white" />
<CreditCard 
  type="Master Card"
  number="0123456789010995"
  expirationMonth={3}
  expirationYear={2021}
  bank="N26"
  owner="Maxence Bouret"
  bgColor="#eeeeee"
  color="#222222" />
<CreditCard 
  type="Visa"
  number="0123456789016984"
  expirationMonth={12}
  expirationYear={2019}
  bank="Name of the Bank"
  owner="Firstname Lastname"
  bgColor="#ddbb55"
  color="white" />

  ///////////

  Components | Rating
Create a Rating component that displays 5 stars, some of them must be empty (☆), some must be full (★).

It takes 1 props:

children: A number between 0 and 5. Be careful, it can be a float number. If it's 3.9, it will display 4 stars.
Example

<Rating>0</Rating>
<Rating>1.49</Rating>
<Rating>1.5</Rating>
<Rating>3</Rating>
<Rating>4</Rating>
<Rating>5</Rating>


//////////////////


State | LikeButton
Create a component LikeButton that displays a button "0 Likes" and with a number increases when the user clicks on it.

As a bonus, you can change the background color and set it to one of these: ['purple','blue','green','yellow','orange','red']