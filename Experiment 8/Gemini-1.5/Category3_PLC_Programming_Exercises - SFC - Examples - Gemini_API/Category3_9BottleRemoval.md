```
(Start of Sequential Function Chart)

        +----------------------<------------------------+
        |                                               |
        |                                               |
+============+                                          |
||          ||                                          |
|| Initial  ||                                          |
||          ||                                          |
+============+                                          |
        |                                               |
        |                                               |
        + FullBottleSensor                      |
        |                                               |
        |                                               |
+---------------+   +------+------------+--------+      |
|    CheckEmpty |   |  N   |            |        |      |
|               |---|      |            |        |      |
|               |   |      |            |        |      |
+---------------+   +------+------------+--------+      |
        |                                               |
        |                                               |
        + NOT EmptyBottleSensor                 |
        |                                               |
        |                                               |
+---------------+   +------+------------+--------+      |
|    Packaging   |   |  N   |            |        |      |
|               |---|      |            |        |      |
|               |   |      |            |        |      |
+---------------+   +------+------------+--------+      |
        |                                               |
        |                                               |
        + EmptyBottleSensor                 |
        |                                               |
        |                                               |
+---------------+   +------+------------+--------+      |
|  RemoveBottle  |   |  N   | Cylinder    |        |      |
|               |---|      |            |        |      |
|               |   |      |            |        |      |
+---------------+   +------+------------+--------+      |
        |                                               |
        |                                               |
        +----------------------->-----------------------+

(End of Sequential Function Chart)
``` 
