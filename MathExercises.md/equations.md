# 14. Equations of lines on a plane

1. **The line passes through points \( A(1,2) \) and \( B(3,4) \). Find the equation of the line.**

$$y - 2 = \frac{4 - 2}{3 - 1}(x - 1)$$  
$$y - 2 = x - 1$$  
$$y = x + 1$$

 <img width="694" alt="Adsız" src="https://github.com/user-attachments/assets/0fd1c809-9c98-4aaa-a989-67d54b88e37a" />





2. **The line passes through point \( A(1,2) \) and is parallel to the line \( y = 2x + 3 \). Find the equation of the line.**
   The slope of the given line is \( m = 2 \), so the parallel line has the same slope.
 $$y - 2 = 2(x - 1)$$  
$$y - 2 = 2x - 2$$  
$y = 2x$


3. **The line passes through point \( A(1,2) \) and is perpendicular to the line \( y = 2x + 3 \). Find the equation of the line.**
   The slope of the given line is \( m = 2 \). The slope of the perpendicular line is $m = -\frac{1}{2}$.

 

$$y - 2 = -\frac{1}{2}(x - 1)$$  
$$2y - 4 = -x + 1$$  
$$x + 2y = 5$$  
$${x + 2y = 5} $$





4. **We have two lines \( y = 2x + 3 \) and \( y = 3x + 2 \). Find the intersection point of these lines and calculate the angle between them.**
   
   The equation is $2x + 3 = 3x + 2$.  
Solving for $x$, we get $x = 1$, and substituting into the equation for $y$, we get $y = 2(1) + 3 = 5$.  
The intersection point is ${(1,5)}$.

- Calculate the angle between the lines:
  The slopes are $m_1 = 2$ and $m_2 = 3$.

  The formula for the tangent of the angle $\theta$ between the lines is
  $$
  \tan \theta = \left| \frac{m_2 - m_1}{1 + m_1m_2} \right| = \left| \frac{3 - 2}{1 + 2(3)} \right| = \frac{1}{7}.
  $$
  Then, $\theta = \arctan \left( \frac{1}{7} \right) \approx 8.13^\circ$.  
  The angle is $\{8.13^\circ\}$.


5. **Write the equation of the line passing through point $A(1,2)$ and parallel to the vector $\mathbf{v} = [2,3]$.**  
   The direction vector $\mathbf{v} = [2,3]$ gives the slope $m = \frac{3}{2}$.

The equation is $y - 2 = \frac{3}{2}(x - 1)$.  
Then, $2y - 4 = 3x - 3$.  
Next, $3x - 2y = -1$.  
Finally, the equation is ${3x - 2y = -1}$.




6. **We have the line \( y = 2x + 3 \). Find an example of a line perpendicular and parallel to it.**
  - Parallel line: Same slope $m = 2$:  
  The equation is $y - 1 = 2(x - 0)$.  
  Finally, ${y = 2x + 1}$.

- Perpendicular line: Slope $m = -\frac{1}{2}$:  
  The equation is $y - 1 = -\frac{1}{2}(x - 0)$.  
  Then, $2y = -x + 2$.  
  Finally, the equation is ${x + 2y = 2}$.


7. **We have the line \( y = 2x + 3 \) and point \( A(1,2) \). Find the distance from point \( A \) to the line.**
   The line equation is $2x - y + 3 = 0$. The distance from $A(1,2)$ is:  
$$d = \frac{|2(1) - 1(2) + 3|}{\sqrt{2^2 + (-1)^2}} = \frac{|2 - 2 + 3|}{\sqrt{5}} = \frac{3}{\sqrt{5}}$$  
Finally, the distance is $d = \frac{3\sqrt{5}}{5}$.



8. **The line intersects the coordinate axes at points \( A(2,0) \) and \( B(0,3) \). Find the equation of the line.**
   The slope is: $m = \frac{3 - 0}{0 - 2} = -\frac{3}{2}$.  
Then, $y - 0 = -\frac{3}{2}(x - 2)$.  
Next, $2y = -3x + 6$.  
Finally, the equation is $3x + 2y = 6$.


9. **Calculate the angle between the line \( y = x + 3 \) and the \( Ox \) axis.**
 The slope of the line is $m = 1$. The angle with the $Ox$ axis is:  
$\theta = \arctan(m) = \arctan(1) = 45^\circ$.  
Finally, the angle is $45^\circ$.



10. **Provide a vector perpendicular to the line \( x + y + 1 = 0 \).**
   The normal vector of the line is:  
$\mathbf{n} = (1, 1)$.  
Finally, the normal vector is $(1, 1)$



    # Equations of Second-Order Curves (Conic Sections)

1. **Find the equation of a circle with center at point $A(1, 2)$ and radius $r = 3$.**
   
   \[
   (x - 1)^2 + (y - 2)^2 = 9\]

2. **Find the equation of a parabola intersecting the $Ox$ axis at points $x = 2, x = 4$, and passing through $y(3) = 1$.**

   General equation: $y = a(x - 2)(x - 4)$.

   Solve for $a$:  
$1 = a(3 - 2)(3 - 4)    $a \Rightarrow -1$




   Equation: $y = -(x - 2)(x - 4)$.

3. **Find the center of the ellipse with the equation $x^2 + 4y^2 - 4x - 16y + 16 = 0$.**

   Complete the square for $x$ and $y$:
   \[
   (x - 2)^2 + 4(y - 2)^2 = 36\]
   Center: $(2, 2)$.

   4. **Find the slope $(m > 0)$ of the line $y = mx - 5$ that is tangent to the circle with the equation $x^2 + y^2 = 1$.**

Condition for tangency: $|c| = \sqrt{1 + m^2}$ and $m = \sqrt{5}$.



5. **Find the intersection points of the hyperbola $x^2 - y^2 = 1$ with the ellipse $x^2 + 4y^2 = 6$.**

  Solve simultaneously:  
$x^2 - y^2 = 1$ and $x^2 + 4y^2 = 6$.  
Subtract the equations to solve.


6. **For the given hyperbola $x^2 - y^2 = 1$, find the distance between its branches.**

   Distance = $2a = 2$.

---

# 16. Equations of planes in space

1. **The plane passes through points \( A(1,2,3) \), \( B(3,4,5) \), and \( C(2,1,4) \). Find the equation of the plane.**
  Given:

$(\mathbf{AB}) = (3-1, 4-2, 5-3) = (2, 2, 2)$

$(\mathbf{AC}) = (2-1, 1-2, 4-3) = (1, -1, 1)$

The normal vector $\mathbf{n}$ is obtained by the cross product of $(\mathbf{AB})$ and $(\mathbf{AC})$:

$\mathbf{n} = (\mathbf{AB}) \times (\mathbf{AC})$



$(\mathbf{AB}) = (3-1, 4-2, 5-3) = (2, 2, 2)$

$(\mathbf{AC}) = (2-1, 1-2, 4-3) = (1, -1, 1)$

$\mathbf{n} = (\mathbf{AB}) \times (\mathbf{AC}) = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 2 & 2 & 2 \\ 1 & -1 & 1 \end{vmatrix}$


$= (4 - (-2), -2 - (2), -2 - 2)$

$= (6, -4, -4)$


The equation of the plane is:

$6(x - 1) - 4(y - 2) - 4(z - 3) = 0$

Finally, the equation is **$6x - 4y - 4z = -8$**.





2. **The plane passes through point \( A(1,2,3) \) and is parallel to the plane \( 2x + 3y + 4z = 5 \). Find the equation of the plane.**
- A parallel plane has the same normal vector
$ {n} = (2,3,4) $:
   $ 2(x-1) + 3(y-2) + 4(z-3) = 0 $
   $ 2x - 2 + 3y - 6 + 4z - 12 = 0 $
   $ 2x + 3y + 4z = 20 $




3. **The plane passes through point \( A(1,2,3) \) and is perpendicular to the normal vector \( \mathbf{n} = [2,3,4] \). Find the equation of the plane.**
 - The normal vector is $n = (2,3,4)$:
   $2(x-1) + 3(y-2) + 4(z-3) = 0$
   $2x + 3y + 4z = 20$



4. **We have two planes \( 2x + 3y + 4z = 5 \) and \( 3x + 4y + 2z = 6 \). Find the line of intersection of these planes.**
   - Solve for the parametric equation:
  $ 2x + 3y + 4z = 5 $ and $ 3x + 4y + 2z = 6 $
  Eliminate $ z $ and solve for $ x $ and $ y $. 
  $ r(t) = (1, 1, 0) + t(1, -2, 1) $




5. **Write the equation of the plane passing through point \( A(1,2,3) \) and parallel to vectors \( \mathbf{v}_1 = [1,0,1] \) and \( \mathbf{v}_2 = [0,1,-1] \).**
The normal vector $ n $ is $ v_1  v_2 $:
$ n = (i \ j \ k) (1 \ 0 \ 1, 0 \ 1 \ -1) = (1-0, -1-0, 1-0) = (1, -1, 1) $
 


The equation of the plane is:
$ 1(x-1) - 1(y-2) + 1(z-3) = 0 $
$ x - y + z = 2 $



6. **We have the plane \( 2x + 3y + 4z = 5 \) and point \( A(1,2,3) \). Find the distance from point \( A \) to this plane.**
   The formula for the distance is:


$d = \frac{|2(1) + 3(2) + 4(3) - 5|}{\sqrt{2^2 + 3^2 + 4^2}} = \frac{|2 + 6 + 12 - 5|}{\sqrt{4 + 9 + 16}} = \frac{15}{\sqrt{29}}$
$d = \frac{15\sqrt{29}}{29}$


7. **The plane intersects the coordinate axes at points \( A(2,0,0) \), \( B(0,3,0) \), and \( C(0,0,4) \). Find the equation of the plane.**
  - Using the intercept form of the plane equation:
$ \frac{x}{2} + \frac{y}{3} + \frac{z}{4} = 1 $
$ 6x + 4y + 3z = 12 $



8. **Calculate the angle between the plane \( x + y + z = 1 \) and the plane \( z = 0 \) (i.e., the \( xy \) plane).**
  - The angle $ \theta $ is calculated using the dot product of their normal vectors:

$ \cos \theta = \frac{n_1 \cdot n_2}{|n_1||n_2|} $

$ = \frac{|1(0) + 1(0) + 1(1)|}{\sqrt{1^2 + 1^2 + 1^2}\sqrt{0^2 + 0^2 + 1^2}} $

$ = \frac{1}{\sqrt{3}} $

$ \theta = \arccos\left(\frac{1}{\sqrt{3}}\right) \approx 54.74^\circ $

$ 54.74^\circ $



9. **Find the vector perpendicular to the plane \( x + y + z = 1 \).**
   - The normal vector of the plane is \( \mathbf{n} = (1, 1, 1) \).
   \[
   \boxed{(1, 1, 1)}
   \]

10. **Find the vector perpendicular to the plane \( 2x + y + z = 1 \).**
    - The normal vector of the plane is \( \mathbf{n} = (2, 1, 1) \).
    \[
    \boxed{(2, 1, 1)}
    \]



---

# Equations of Second-Order Surfaces

1. **Write the equation of a sphere with center at point $P = (1, 2, 3)$ and radius $r = 3$.**
   \[
   (x - 1)^2 + (y - 2)^2 + (z - 3)^2 = 9\]

2. **Do the spheres $x^2 + y^2 + z^2 = 1$ and $x^2 + y^2 + z^2 = 2$ have any common points?**
   
   No, their radii are different, and they are centered at the origin. They do not intersect.

3. **What curve in space is formed by the intersection of the sphere $x^2 + y^2 + z^2 = 1$ with the sphere $(x - 1)^2 + y^2 + z^2 = 1$?**
   
   Solve $x^2 + y^2 + z^2 = 1$ and $(x - 1)^2 + y^2 + z^2 = 1$ simultaneously. This forms a circle.

4. **Write the equation of a tangent plane to the paraboloid $z = (x - 1)^2 + y^2 + 1$ at point $P(1, 0, 1)$.**

   Gradient of $z$:
   \[
   \frac{\partial z}{\partial x} = 2(x - 1), \; \frac{\partial z}{\partial y} = 2y\]
   At $P(1, 0, 1)$, the gradient is $(0, 0, -1)$. Equation:
   \[
   0(x - 1) + 0(y - 0) - 1(z - 1) = 0 \implies z = 1\]
