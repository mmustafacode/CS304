# 1.Information Hiding:

- "Showing only those details to the outside world which are necessary for the outside world and hiding all other details from the outside world."
- we have objects with their attributes and behaviors that are hidden from other classes,
- All information related to an object is stored within the object
- It is hidden from the outside world
- It can only be manipulated by the object itself

# 02.1 Information Hiding

Information hiding OOP ka ek bohat important principle hai jo real life se inspired hai. Iska matlab hai ke har information har kisi ke liye accessible nahi honi chahiye. Private information sirf uske owner tak hi limited honi chahiye.

## Information Hiding ka matlab hai:
**“Sirf wohi details bahar ki duniya ko dikhana jo zaroori hoon, aur baqi sab details chhupa lena.”**

* Real Life Examples of Information Hiding 

1. Ali ka naam aur uski personal information uske brain mein hoti hai, hum usay directly access nahi kar sakte.
Agar humein yeh information chahiye ho to humein Ali se poochna padega, aur yeh Ali par depend karta hai ke wo kitni information share kare.

2. Email server ke paas millions logon ki account information hoti hai, lekin jab hum request karte hain to wo sirf hamara apna account data hi share karta hai.
Agar hum kisi aur ka data maangein to request reject ho jati hai.

3. Phone ki SIM card mein kai phone numbers save ho sakte hain, lekin hum directly SIM se numbers read nahi kar sakte.
Phone-set yeh kaam karta hai, aur agar owner ne permission nahi di ho to hum numbers nahi dekh sakte.

## OOP mein Information Hiding

Object Oriented Programming mein objects hote hain jinke apne attributes (data) aur behaviors (functions) hote hain, jo dusri classes se hidden hote hain.

Is liye hum kehte hain ke OOP, information hiding ka principle follow karta hai.

## OOP ke perspective se definition:
**“Object ki details (state aur behavior) ko users se chhupa dena Information Hiding kehlata hai.”**

## Yahan users se murad hai:

- Kisi doosri class ka object jo is class ke functions ko call karta hai
- Ya koi aur program jo is class ko use karta hai

## Information Hiding kaise achieve hoti hai?

OOP mein information hiding yeh principles use karke achieve hoti hai:

- Har object ki sari information us object ke andar store hoti hai
- Yeh information outside world se hidden hoti hai
- Isay sirf woh object khud hi manipulate (change/use) kar sakta hai

## Advantages of Information Hiding

1. Yeh OOP Model ko simple banata hai

Jab implementation details hidden hoti hain to sirf objects aur unki interaction nazar aati hai, jis se system samajhna easy ho jata hai.

2. Change ka effect control karta hai

Function ki implementation sirf class ke andar hoti hai.
Agar hum function ke andar changes karein to bahar ke system par koi effect nahi padta.

Conclusion

Hum Information Hiding ko achieve karte hain:

Encapsulation ke through
Abstraction ke through