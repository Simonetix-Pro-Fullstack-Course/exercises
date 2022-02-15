Ex 1 | Component: IdCard
Create and render an IdCard component with 6 props:

lastName: A string
firstName: A string
gender: A string, 'male' or 'female'
height: A number
birth: A date
picture: A string

//

Example:

<IdCard
  lastName='Doe'
  firstName='John'
  gender='male'
  height={178}
  birth={new Date("1992-07-14")}
  picture="https://randomuser.me/api/portraits/men/44.jpg"
/>

<IdCard
  lastName='Delores '
  firstName='Obrien'
  gender='female'
  height={172}
  birth={new Date("1988-05-11")}
  picture="https://randomuser.me/api/portraits/women/44.jpg"
/>


/////////

Ex 2 | Component: Greetings
Create a Greetings component with 2 props:

lang: A string that can have values: "de", "en", "es" or "fr"
children: A text
The component should display a greeting text in the chosen language.

Example:

<Greetings lang="de">Ludwig</Greetings>
<Greetings lang="fr">François</Greetings>


////////////////////////////

Ex 3 | Component: Random
Create a Random component with 2 props:

min: A number
max: A number
The component should display a random integer in the range between the min and the max number.

Example:

<Random min={1} max={6}/>
<Random min={1} max={100}/>