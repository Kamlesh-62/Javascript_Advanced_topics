## JavaScript behind the hood
 ```
    +-----------------+
     |  JavaScript Code|
     +--------+--------+
              |
              v
+-------------+--------------+
| JavaScript Engine (e.g., V8)|
+-------------+--------------+
| 1. Parser (Tokenizer)       |
| 2. AST Generator            |
| 3. Interpreter (Ignition)   |
| 4. Profiler                 |
| 5. JIT Compiler (TurboFan) |
| 6. Garbage Collector        |
+----------------------------+
              |
              v
     +--------+---------+
     |   Machine Code   |
     +------------------+
```
