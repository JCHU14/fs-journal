# A bit more CSharp and SQL
1. What does ***inheritance*** accomplish for us in C#?

  > | Makes it easier by using reusable code and other elements take in said methods |

2. How does ***member inheritance*** work in C#? Does a `Class` inherit all members of the base `Class`?

  > | The class does inherit the members of the class because they are children of the parent class |

3. How does ***accessibility*** affect inheritance?

  > | It can cause road blocks because of the lack of accessibility |

4. What is the difference between a `PRIMARY KEY` and a `FOREIGN KEY`

  > | The primary key is the main key while a foreign key is a different objects id |

5. What is an ***alias***?

  > | used to indicate that a named person is also known or more familiar under another specified name |

6. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

  ```SQL
  CREATE TABLE doctors (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patients (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patient_doctors (
    id INT NOT NULL AUTO_INCREMENT,
    doctorId INT NOT NULL,
    patientId INT NOT NULL,

    FOREIGN KEY (doctorId)
      REFERENCES doctors(id),
    FOREIGN KEY (patientId)
      REFERENCES patients(id),
  )

  ```

  > | string sql = @"SELECT pat.* FROM doc.*; JOIN pat ON doc.id " |
