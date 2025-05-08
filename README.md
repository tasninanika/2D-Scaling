# 2D Scaling in Computer Graphics

## 📌 Description

2D Scaling is a geometric transformation used to resize an object in the 2D plane. This is achieved by multiplying the coordinates of each point in the object with scaling factors along the X and Y axes.

The scaling factors determine how much the shape is stretched or shrunk:
- If the factor > 1, the object enlarges.
- If the factor < 1, the object shrinks.
- If the factor = 1, the object remains unchanged.

Scaling can change the shape's size but does not affect its position unless combined with other transformations. In this project, we visually demonstrate how a square changes when scaled using different X and Y scaling values.

---

## 📊 Algorithm: 2D Scaling of a Square

**Step 1:** Define the original square with its corner points `(x, y)`.  
**Step 2:** Set scaling factors:  
- `scale_x` → scaling along the X-axis  
- `scale_y` → scaling along the Y-axis  

**Step 3:** For each point in the square:  
- `new_x = x * scale_x`  
- `new_y = y * scale_y`  
Store these new coordinates as the scaled square.  

**Step 4:** To close the shape for plotting, add the first point at the end of both the original and scaled lists.  

**Step 5:** Extract x and y coordinates separately from both point lists for plotting.  

**Step 6:** Use Matplotlib to draw both the original and the scaled square on the same graph using different colors and labels.  

**Step 7:** Add axis lines, grid, labels, and legend, then show the output plot.

---

## 🖼 Output

The output displays both the original square and the scaled square, showing how the shape is resized horizontally, vertically, or both.

---

## 📁 Technologies Used

- Python
- Matplotlib

