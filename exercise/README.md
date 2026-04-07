# Props Assignment: Movie & Actor Display

## Assignment

Create a new React app with Vite. Build a page that displays movies and actors using components and props.

---

## Requirements

### Components
Create the following components:
- `Movie`
- `Actor`

---

### Data

- **3 or more movies** as objects with:
  - title: string
  - year: number
  - rating: number (1-5 stars)   
- **3 or more actors** as objects with:
  - `name`: string
  - `age`: number
  - `awards`: number (how many awards they've received)
---

### Rendering

Pass the data as props to their respective components. 
The Movie component should utilize the `props` object directly while the Actor component should utilize destructuring.  
You can display the information however you want while also taking into acount the following:

- If the movie has a rating of **4.2 or higher**, display:  
  **"Critically Acclaimed"**

- If the actor is **50 or older**, display:  
  **"Veteran Actor"**

- If the actor is **under 50**, display:  
  **"Rising Talent"**

---
