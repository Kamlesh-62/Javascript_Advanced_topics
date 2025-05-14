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
## 🌐 JavaScript in the Browser (Event Loop & Web APIs)
When JS runs in a browser, it's part of a larger event-driven system:
```
+-----------------+
|  JS Engine (V8) |
+-----------------+
         |
         v
+----------------------+
|  Call Stack          |
+----------------------+
         |
         v
+----------------------+
| Web APIs (DOM, Fetch)|
+----------------------+
         |
         v
+----------------------+
| Callback Queue       |
+----------------------+
         |
         v
+----------------------+
| Event Loop           |
+----------------------+
```
