# 🐍 Python OOP: Operator Overloading (Less Than <)

## 🎯 AIM

To write a Python program that demonstrates *operator overloading* by overloading the **less than (<)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class A**:
   - Define the __init__() method to initialize the object with a value a.

2. **Overload the < Operator**:
   - Define the __lt__() method with logic:
     - If self.a < o.a, return "ob1 is less than ob2"
     - Else, return "ob2 is less than ob1"

3. *Create Objects*:
   - Instantiate two objects ob1 and ob2 with values.

4. **Use < Operator**:
   - Use print(ob1 < ob2) to trigger the overloaded behavior.

---

## 💻 Program
```
class A:
    def _init_(self, a):
        self.a = a
    def _lt_(self, o):
        if self.a < o.a:
            return "ob1 is less than ob2"
        else:
            return "ob2 is less than ob1"
ob1 = A(10)
ob2 = A(20)
print(ob1 < ob2)
```

## Output
<img width="277" height="90" alt="image" src="https://github.com/user-attachments/assets/177551bc-d580-48d7-972e-b612a4b99d88" />


## Result
The program successfully demonstrates operator overloading by redefining the less than (<) operator in a custom class.
When comparing two objects, the overloaded method _lt_() executes, producing a descriptive comparison result instead of a boolean value.
