# 🦂 Scorpio Cursor Game

Hey everyone! This is my **Scorpio Cursor Game** project. I built a cool mechanical scorpion that lives on your screen and follows your mouse around.

It’s mostly an experiment in **Procedural Animation**—which means I didn't use any pre-made videos or GIFs. All the leg movements and body bending are calculated in real-time using math (JavaScript) while you play with it!

## 🎮 Features

* **Real-time Following:** The scorpion chases your cursor naturally.
* **Walking Logic:** The legs don't just slide; they actually step and plant on the ground.
* **Custom Graphics:** I drew the body parts using code (Canvas API) to make them look like shiny metal armor.
* **Lighting:** It has glowing eyes and a glowing red stinger!

## 🛠️ Tech Used

* **HTML5 Canvas** (for drawing everything)
* **Vanilla JavaScript** (for the physics and logic)
* **Inverse Kinematics** (the math that makes the legs move correctly)

## 🚀 How to Run It

It's super simple to run this on your own computer:

1. Download this folder.
2. Make sure you have the background image `scorpion_bg.png` in the same folder as `index.html`.
3. Double-click `index.html` to open it in Chrome, Edge, or Firefox.
4. Move your mouse and watch it go!

## 💻 Commands

If you want to update the code and push it to GitHub, here are the commands I use:

```bash
# Add all new changes
git add .

# Save the changes with a message
git commit -m "Updated background and fixed leg logic"

# Push to GitHub
git push origin main
