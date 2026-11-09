# Testing Field effect transistors 

---

#### Transistor information

| ------------------------      |             1              |        2         |            3             |
| ----------------------------- | :------------------------: | :--------------: | :----------------------: |
| **Part #**                    |           2N5457           |      2N3904      |          2N5459          |
| **Polarity**                  |            JFET            |       NPN        |        N Channel         |
| **Material**                  |         N channel          |     Silicon      |           JFET           |
| **Description & Application** | General purpose amp/switch | Audio amp/switch | High freq amp/pscillator |
| **Case Style**                |           TO-92            |      TO-92       |          TO-92           |
| **H*fe***                     |             9e             |       158        |           N/a            |



---

#### Diagrams:

![[PXL_20261104_183901371.RAW-01.jpg|438]]


---

#### Testing Transistors:


| + -       | 2N5458 | 2N5459 |
| --------- | :----: | :----: |
| **S G**   |   0L   |   0L   |
| **S D**   | .219 V | .221V  |
| **G S**   | .683 V | .674 V |
| **G D**   | .676 V | .668 V |
| **D S**   | .224 V | .239V  |
| **D G**   |   0L   |   0L   |
| **Good?** |  Yes   |  Yes   |

| + -       | **2N3904** |
| --------- | :--------: |
| **E B**   |     0L     |
| **E C**   |     0L     |
| **B E**   |   .692 V   |
| **B C**   |   .618 V   |
| **C E**   |     0L     |
| **C B**   |     0L     |
| **Good?** |    Yes     |

*A good Bipolar junction transistor should have 4 0L readings while JFETS should have 2 0L readings.*


