# Props Exercise: Movie & Actor Display

## Setup

Create a new React app with Vite.

---

## Assignment

Build a page that displays movies and actors using components and props.

---

## Requirements

### Components
Create:
- `Movie`
- `Actor`

---

### Data (in `App.jsx`)

Create:

- **3+ movies** as strings  
- **3+ actors** as objects with:
  - `name`
  - `age`

---

### Rendering

In `App.jsx`:

- Render the `Movie` component multiple times, passing each movie as a prop  
- Render the `Actor` component multiple times, passing each actor as a prop  

---

### Display

- `Movie` should display:
  - Movie title  

- `Actor` should display:
  - Name  
  - Age  

---

### Add Conditional Logic to Actors

Update your `Actor` component so that:

- If the actor is **50 or older**, display:  
  **"Veteran Actor"**

- If the actor is **under 50**, display:  
  **"Rising Talent"**

---

## Stretch Goal (Optional)

Add a second prop to `Actor` called `movies` (an array of movie titles).

- Pass a list of movies each actor is known for
- Display those movie titles inside the `Actor` component
