```
                                              +--------------+
                                     Read     |              |
                                   +----------+ MySQL Server |
+--------------------+             |          |              |
|                    |             |          +-------+------+
|  React Native App  |             |                  ^
|                    |             |                  |
+---------+----------+             v                  |
          |               +--------+--------+         |
          |               |                 | Write   |
          +-------------->+ Kotlin REST API +---------+
                          |                 |
                          +--------+--------+
                                   ^                    +-----------------+
                                   |                    |                 |
                                   +--------------------+ Parks JSON File |
                                    Import on statup    |                 |
                                                        +-----------------+
```
