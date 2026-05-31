# 🏡 Welcome to the Design Team Pet Village! 🌸

The Pet Village is a cozy, digital sanctuary where designers can cultivate their own pet gardens, share joy, and practice the art of version control (Git & GitHub) in a fun, pressure-free environment! 

Rather than editing complex code, we use Git to gift each other cute animals, mythical beasts, and pixelated companions.

---

## 🌻 How the Village Works
Every designer on the team has their own designated garden space in the village. 
When you visit the website, you can view each designer's garden. If they have pets, they'll show up there with their name and a note showing who gifted them!

---

## 🎁 How to Gift a Pet
Gifting a pet is a fun way to practice the Git workflow. Here is the step-by-step guide to sending a furry (or feathery, or scaly) friend to a colleague's garden:

### 1. Fork the Repository 🍴
* To start, **fork this repository** to your own GitHub account. This creates your own copy of the project where you can make changes.

### 2. Create a Branch 🌿
* Create a new branch in your fork.
* **Name the branch** to describe who will receive the gift (e.g., `gift-for-daniel` or `monikas-new-puppy`).

### 3. Create or Find Your Pet Image 🎨
* Choose or create an image file (`.png`, `.jpg`, `.jpeg`, `.gif`, `.webp`, or `.svg`).
* You can design your pet using any image generation/editing tool — feel free to modify the prompt provided in our **FigJam board** to create your pet!
* **The Magic Naming Rule:** Name your file using the format `PetName_YourName.extension`.
  * *Example:* If Dagny wants to gift a bunny named "Fluffy" to Daniel, she would name the file: `Fluffy_Dagny.png`.
  * The site will automatically read this and display: **Fluffy** *gifted by Dagny*!

### 4. Add the Image to the Relevant Folder 🏡
* Place your named pet image inside the folder of the designer you want to gift it to:
  `src/assets/pets/<designer-slug>/`
  * *Example:* If gifting to Daniel, place the file in `src/assets/pets/daniel/`.
* ⚠️ **The Unspoken Rule of the Garden:** *Never gift yourself a pet!* It is an unspoken rule of the garden to never gift yourself pets. A garden's beauty comes from the generosity of your neighbors!

### 5. Create a Pull Request (PR) ✉️
* Commit your changes, push your branch to your fork, and open a **Pull Request (PR)** from your branch to the `main` branch of the **original repository**.
* In the PR description, write a nice note about the pet you're gifting!

### 5. Assign the PR to the Recipient 👑
* **Crucial step:** Assign the Pull Request to the designer who is receiving the gift.
* They will get a notification, review the incoming pet, and merge the PR to officially welcome the new companion to their garden!

---

## 🌿 Running the Village Locally
If you want to run the village locally on your machine to check the gardens, you can run the following commands in your terminal:

```bash
# Install the project dependencies
npm install

# Start the local development server
npm run dev
```

Happy gifting, and may your gardens flourish! 🚜🌾
