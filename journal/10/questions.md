# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > | a namespace is a set of signs (names) that are used to identify and refer to objects of various kinds |

02. What is the difference between a `class` and an `interface`?

  > | Interfaces specify what a class must do and not how. |

03. What is the method that returns an instance of a class, yet it has no return type?

  > | The method that returns an instance of a class, yet it has no return type, is usually called a constructor |

05. In the Car example what is the access modifier of the `Start()` method?

  ```c#
  abstract class Car
  {
    public string Start()
    {

      return "Vroooom";

    }
  }
  ```

  > | There is a function stored on class car that is called by a public string |

06. In the Car example what is `string` an indication of?

  > | the modifier of start() |

07. In the Car example what is `abstract` preventing?

  > | used as a basis for creating specific objects that conform to its protocol, or the set of operations it supports.  |

08. In a SQL table, what is the difference between information in a row and information in a column?

  > | unique record, and each column represents a field in the record |

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

  > |  |

10. In SQL how can you query more than a single table? Provide an example.

  > | To query multiple tables in SQL, you can use a simple SELECT statement that calls more than one table |
