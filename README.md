# Lock-Disk-Surface

### **📌 What is the Lock Disk Surface?**  
The **Lock Disk Surface** is a type of **parametric surface** in three-dimensional space. It is a special mathematical structure that resembles a **twisted ring or torus-like shape**. The surface is generated using two parameters \( u \) and \( v \), which are mapped to **\( x, y, z \)** coordinates.

It is called a **"Lock Disk"** because of its **symmetry and closed structure**, somewhat resembling a lock washer or a Möbius-like twisted disk.

---

### **📜 The Parametric Equations**
In your code, the surface is defined by the parametric equations:

\[
x = \frac{\sin(u)}{\sqrt{2} + \sin(v)}
\]
\[
y = \frac{\cos(u)}{\sqrt{2} + \sin(v)}
\]
\[
z = \frac{2 \cos(u)}{3 + \sqrt{2}}
\]

where:  
- \( u \) and \( v \) range from \( 0 \) to \( 2\pi \).  
- \( u \) determines the position around the ring.  
- \( v \) influences the curvature and twisting effect.

---

### **🧠 Understanding Each Term**
1. **\( x = \frac{\sin(u)}{\sqrt{2} + \sin(v)} \)**  
   - The \( x \)-coordinate is controlled by \( \sin(u) \), which gives an oscillating pattern around the circle.
   - The denominator \( \sqrt{2} + \sin(v) \) acts like a scaling factor, making the surface curve smoothly.

2. **\( y = \frac{\cos(u)}{\sqrt{2} + \sin(v)} \)**  
   - Similar to \( x \), but using \( \cos(u) \) instead of \( \sin(u) \), ensuring a circular pattern in the \( xy \)-plane.

3. **\( z = \frac{2 \cos(u)}{3 + \sqrt{2}} \)**  
   - This keeps the surface within a certain height range, controlled by \( \cos(u) \).
   - The denominator \( 3 + \sqrt{2} \) ensures the surface doesn't stretch infinitely in the \( z \)-direction.

---

### **🌍 Geometric Meaning**
- The **denominators** ensure the surface remains smooth and continuous, preventing sharp edges or singularities.  
- The **\( u \)** parameter moves the surface around in a circular fashion, while **\( v \)** creates variations that add depth and complexity.  
- The shape looks similar to a **twisted torus or Möbius-like surface** but has unique curvature properties.
