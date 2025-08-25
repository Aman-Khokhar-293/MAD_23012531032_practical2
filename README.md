# Practical – 2  
**Aim:** Create Android Application to demonstrate functions of Activity Life Cycle and Basic UI.  

---

## Output  
- App displays **“Hello World”** at the center of the screen.  
- Activity background → **Yellow** (`#FFFF00`).  
- TextView → Holo Blue Bright color, **27sp**, **Bold + Italic**.  
- All Activity Life Cycle methods (`onCreate`, `onStart`, `onResume`, `onPause`, `onStop`, `onRestart`, `onDestroy`) are shown using:  
  - **Log message** (Logcat)  
  - **Toast message**  
  - **Snackbar message**  

---

## Steps Performed  
1. Used **ConstraintLayout** in `activity_main.xml`.  
2. Placed a **TextView** in the center and set its properties (color, size, style).  
3. In **MainActivity.java**, overridden all Activity Life Cycle methods.  
4. Printed **Log messages** for each method in Logcat.  
5. Displayed **Toast** and **Snackbar** inside each method to show lifecycle changes.  

---

## Screenshots  
(Place your screenshots in a folder named `screenshots/` and link them here)  

- **UI Screen:** <img width="276" height="611" alt="image" src="https://github.com/user-attachments/assets/61283918-d813-4a26-a4a6-5132e149e720" />
- **Logcat Output:** <img width="1594" height="205" alt="image" src="https://github.com/user-attachments/assets/7472a11e-3cd3-4fc4-9412-f1795e1f10d2" />
- **Toast & Snackbar:** <img width="342" height="746" alt="image" src="https://github.com/user-attachments/assets/b265d4db-389c-4f63-8594-0741a58d9d61" />
  - <img width="342" height="741" alt="Screenshot 2025-08-25 220417" src="https://github.com/user-attachments/assets/6cbf6859-0aa8-448b-9b8c-337eb4789247" />

  
---

## Concepts Learned  
- TextView and its properties  
- Toast Message  
- Snackbar Message  
- Android built-in resources (colors)  
- Activity Life Cycle methods  
- Logcat usage  
- ConstraintLayout basics  
- Generating ID for views  
