# Testing Bipolar junction Transistors

---

#### Transistor information

| ------------------------      | 1                | 2                               | 3                             |
| ----------------------------- | ---------------- | ------------------------------- | ----------------------------- |
| **Part #**                    | 2N3904           | 2N3053                          | 2N3055                        |
| **Polarity**                  | NPN              | NPN                             | NPN                           |
| **Material**                  | Silicon          | Silicon                         | Silicon                       |
| **Description & Application** | Audio amp/switch | Power supplies/Power oscilators | Power supplies/switching      |
| **Case Style**                | TO-92            | To-205AD                        | TO-3                          |
| **H*fe***                     | 158              | 50 - 250                        | **-------------------------** |

---

#### Diagrams:


![[Transistors.jpg|519]]

---

#### Testing Transistors:


| + -       | 2N3904 | 2N3053 | 2N3055 |
| --------- | :----: | :----: | :----: |
| **E B**   |   0L   |   0L   |   0L   |
| **E C**   |   0L   |   0L   |   0L   |
| **B E**   | .672 V | .597 V | .509 V |
| **B C**   | .650 V | .487 V | .497 V |
| **C E**   |   0L   |   0L   |   0L   |
| **C B**   |   0L   |   0L   |   0L   |
| **Good?** |  Yes   |  Yes   |  Yes   |

---

#### Measured H*fe*

- 2N3904 = **158**
ㅤ
- 2N3053 = **80**
ㅤ
- 2N3055 = **50-250**

**Explanation for difference in measured H*fe*:**
ㅤ
The H*fe* finds the DC current gain in the common emitter within forward bias. The measured amount is different because real components will very from theoretical counterparts. Within the data sheets you can also find how much the H*fe* can vary too, which can explain why there is a difference. 

