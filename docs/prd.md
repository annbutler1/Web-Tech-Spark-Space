# SparkSpace

### One-Sentence Goal  
SparkSpace helps artists overcome creative block by generating random sketch prompts, reference images, and color palettes, to reignite inspiration and flow.


## Core Features  

- **Random Object Prompt:**  
  Generates a tangible object for artists to sketch using the free **Roger Random Object API**.  
  Example output: *“Bicycle.”*

- **Reference Image Generator:**  
  Pulls a random or keyword-based image from the **Unsplash Source API** to provide visual inspiration.  
  Example: Enter “forest” will returns a random forest image.

- **Color Palette Generator:**  
  Creates a 1,2, or 3 color palette using **Colormind.io** and labels each color with a human-readable name from **Color.pizza**.  
  Example: Muted terracotta, ocean blue, linen white.


---

## Pages  

### 1. **Home Page**
- Simple home page with buttons to each of the 4 options
- A brief blurb about artists block
- A navigation bar at the top that has buttons to each other page and a small logo with the name on it

### 2. **Object Prompt Page**
- Displays a randomly generated object to draw.  
- Includes a large “New Object” button and copy-to-clipboard function.  
- API: [Roger Random Object API](https://roger.redevised.com/api/v1)  
- Fallback: A local list of objects if the API fails.

---

### 3. **Reference Image Page**
- Allows user to enter a keyword (e.g., “mountains,” “sunset”) or choose “random.”  
- Fetches a related image from the **Unsplash Source API**.  
- Features a “Shuffle” button to pull a new image and a “Download” option for saving.  
- API: [Unsplash Source](https://source.unsplash.com)

---

### 4. **Color Palette Page**
- Generates 3–8 color palettes (random or mood-based).  
- Uses **Colormind.io** for palette creation and **Color.pizza** for naming each color.  
- Users can copy hex codes or lock a favorite color before regenerating.  
- APIs:  
  - [Colormind API](http://colormind.io/api/)  
  - [Color.pizza API](https://api.color.pizza/v1/docs)

---

## Design / Interaction Notes  
- Space/ spark theme colors (navy blue, white stars, orange and red for spark like colors).  
- Minimalist layout with centered buttons and large text for accessibility.  
- Header font: elegant serif (e.g., Playfair Display or Walbaum).  
- Body font: simple sans-serif (e.g., Inter or Poppins).  
- Smooth transitions when new content loads.  
- All pages link back to a top navigation bar: *Home · Object · Image · Palette · Spark.*

---

## Summary  
**SparkSpace** is a compact, interactive website that helps artists reignite creativity with a click.  
By combining random prompts, visual references, and dynamic color palettes, it transforms artist’s block into inspiration in seconds — making it a fun, achievable, and visually engaging web project.

---

### APIs Used
These APIs are ones that I researched that are free and you shouldn't need to find any additonal ones. These should cover all the requirements listed above.   
- **Roger Random Object Generator** → https://roger.redevised.com/api/v1  
- **Unsplash Source API** → https://source.unsplash.com/  
- **Colormind API** → http://colormind.io/api/  
- **Color.pizza API** → https://api.color.pizza/v1/docs
