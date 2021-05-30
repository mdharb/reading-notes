# **Domain Modeling**

* **the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain.**

### **Object-oriented**

**Object-oriented programming:**

1. The `new` keyword instantiates (i.e. creates) an object.
2. The constructor function initializes properties inside that object using the `this` variable.
3. The object is stored in a variable for later use.

### **Calculate daily Likes:**

* Popularity of a video is measured in `Likes`. And the formula for calculating Likes is the ***number of viewers times the percentage of viewers*** who'll Like a video. In other words, **`viewers times percentage`**.

> ### **Tips for building domain models:**

* When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
* Model its attributes with a constructor function that defines and initializes properties.
* Model its behaviors with small methods that focus on doing one job well.
* Create instances using the `new` keyword followed by a call to a constructor function.
* Store the newly created object in a variable so you can access its properties and methods from **outside**.
* Use the this variable within methods so you can access the object's properties and methods from **inside**.



# **HTML**

### **Tables**

* Represents information in a grid format. ***Grids*** allow us to understand complex data by referencing information on two axes.

* A table is drawn out row by row. Each row is created with the `<tr>` element

* Inside each row there are a number of cells represented by the `<td>` element ***(or `<th>` if it is a header)***.

* You can make cells of a table span more than one row or column using the **rowspan** and **colspan** attributes.

* For long tables you can split the table into a **`<thead>`**, **`<tbody>`**, and **`<tfoot>`**.


# **JavaScript**

### **Objects** 
* A series of variables and functions that represent something from the world around you.

Ways to create objects:

* LITERAL NOTATION.
* OBJECT CONSTRUCTOR NOTATION.

> In an object, **variables** are known as `properties` of the object; **functions** are known as `methods` of the object. 

### **Built-in objects:**

* String.
* Number.
* Math.
* Date.

> **`Arrays` and `objects` can be used to create complex data sets (and both can contain the other).**



