Lecture Contents
• Generalization
• Sub typing (extension)
• Specialization (restriction)
• Overriding
• Abstract classes
• Concrete classes 

## 🔁 Recap – Inheritance

- Derived class, base class ki **saari characteristics inherit karti hai**  
- Inherited characteristics ke ilawa, derived class ki apni **unique characteristics bhi ho sakti hain**  
- Inheritance ka sab se bada faida **reuse (dobara use karna)** hai  

---

# 🔹 04.1 Inheritance se Related Concepts

- Generalization  
- Subtyping (extension)  
- Specialization (restriction)  

---

# 🔹 04.2 Generalization

OO (Object-Oriented) models mein kuch classes ki **common characteristics** hoti hain.

Hum in common features ko ek **nayi class** mein extract karte hain aur phir original classes ko us se **inherit** kar dete hain.

Object model mein bohat se objects hote hain jin mein **common characteristics** hoti hain. In sab ki **attributes aur behavior** ko combine karke ek **single general class** bana di jati hai.

👉 Base class asal mein ek **general class** hoti hai jo derived classes ke common behavior ko represent karti hai.

Is concept ko **Generalization** kehte hain.

---

## 🔹 Benefits of Generalization

- Yeh **redundancy (repeat hone wali cheezon)** ko kam karta hai  
- **Reusability** provide karta hai  
- System ko **simple (less complex)** banata hai  

---

## 🔹 Important Relationship

Generalization mein base aur child classes ke darmiyan:

👉 **“Is a Kind of Relationship” (ya “Is-A relationship”)** hona zaroori hota hai  

---

## 🔹 Final Simple Definition

👉 Generalization = Common features ko ek general class mein combine karna aur reuse karna  


# Example: Line, Circle and Triangle

+------------------+     +------------------+     +------------------+
|       Line       |     |      Circle      |     |     Triangle     |
+------------------+     +------------------+     +------------------+
| color            |     | color            |     | color            |
| vertices         |     | vertices         |     | vertices         |
| length           |     | radius           |     | angle            |
+------------------+     +------------------+     +------------------+
| move()           |     | move()           |     | move()           |
| setColor()       |     | setColor()       |     | setColor()       |
| getLength()      |     | computeArea()    |     | computeArea()    |
+------------------+     +------------------+     +------------------+

   Line is shape           Circle is shape        Triangle is shape


                         +------------------+
                         |      Shape       |
                         +------------------+
                         | color            |
                         | vertices         |
                         +------------------+
                         | move()           |
                         | setColor()       |
                         +------------------+
                                /|\
                               / | \
                              /  |  \
                             /   |   \
                            /    |    \
                           /     |     \
                          /      |      \
                         /       |       \
                        /        |        \

       +------------------+   +------------------+   +------------------+
       |      Circle      |   |       Line       |   |    Triangle      |
       +------------------+   +------------------+   +------------------+
       | radius           |   | length           |   | angle            |
       +------------------+   +------------------+   +------------------+
       | computeArea()    |   | getLength()      |   | computeArea()    |
       +------------------+   +------------------+   +------------------+

       