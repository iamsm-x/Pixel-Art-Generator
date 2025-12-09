# 🎨 **Pixel Art Generator**

The **Pixel Art Generator** is an interactive web application that allows users to create pixel-based artwork using a customizable grid, color picker, paint/erase tools, and full mouse + touch support.  
Created using **HTML, CSS, and JavaScript**, this project runs entirely in the browser and requires no installation.

---

## ✨ **Overview**

This tool enables users to:

- Generate grids of various sizes  
- Pick custom colors  
- Draw pixel art with mouse or touch  
- Erase specific cells  
- Clear the entire canvas  
- Toggle between paint and erase modes  

It provides a fun and creative way to explore pixel-style art directly in the browser.

---

## ⭐ **Features**

- 🧩 **Adjustable Grid Size** — set grid width & height (1–35)  
- 🎨 **Color Picker** — choose any color to paint with  
- 🖌️ **Paint Mode** — draw freely on the grid  
- 🧽 **Erase Mode** — erase selected pixels  
- 🔄 **Clear Grid** — remove all artwork instantly  
- 📱 **Touch + Mouse Support** — works on phones, tablets, and desktop  
- ⚡ **Lightweight & Fast** — no external libraries needed  

---

## 🛠️ **Tech Stack**

- 🌐 **HTML** – structure  
- 🎨 **CSS** – styling and layout  
- ⚡ **JavaScript** – dynamic grid creation, drawing logic, event handling  

---

## ▶️ **How to Use**

1. Use sliders to set **Grid Width** and **Grid Height**  
2. Click **Create Grid**  
3. Select a color from the **color picker**  
4. Hold and drag to paint on the grid  
5. Click **Erase** to switch to erasing mode  
6. Click **Paint** to return to drawing mode  
7. Click **Clear Grid** to remove everything  

---

## 🧠 **How It Works**

### 🔹 Grid Creation  
The JavaScript dynamically generates rows and columns using nested loops based on slider input.

### 🔹 Drawing Logic  
- User actions trigger **touch/mouse events**  
- When drawing mode is active, selected cells are filled with the chosen color  
- When erase mode is active, cells are set to transparent  

### 🔹 Device Detection  
The script detects whether the user is using a **mouse** or **touchscreen**, ensuring correct behavior on all devices.

---

### 📂 **Running the Project**

Simply open the HTML file in any browser:

```bash
index.html

```
**You can also view the live hosted version here:**

🔗 https://pixel-generator-webapp.netlify.app/

### 🚀 **Conclusion**

The Pixel Art Generator is a simple yet fun project that demonstrates dynamic DOM manipulation, event handling, and responsive UI design.
Perfect for creative exploration, learning JavaScript fundamentals, or using as a base for more advanced art tools.
