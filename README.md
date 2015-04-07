a)
 mysql> select area(4) as Area;
    +--------------+
    | Area(4) |
    +--------------+
    |           50 |
    +--------------+
    1 row in set (0.00 sec)

   mysql> select area(66);
    +---------------+
    |  area(7) |
    +---------------+
    |        153.9 |
    +---------------+
    1 row in set (0.00 sec)

    mysql> select area(44.5);
    +-----------------+
    | area(44.5) |
    +-----------------+
    |        6221.1	  |
    +-----------------+
    1 row in set (0.00 sec)

    mysql> select area(6);
    +----------------+
    | area(6) |
    +----------------+
    |            113|
    +----------------+
    1 row in set (0.00 sec)
	
	
	b)
    mysql> select  time(10800);
    +-----------------------+
    |  time(10800) |
    +------------- ----------+
    | 3 Hours, 0 Minutes, 0 Seconds                  |
    +------------- ----------+
    1 row in set (0.00 sec)

    mysql> select  time(7350);
    +----------------------+
    |  time(7350) |
    +----------- -----------+
    |  2 Hours, 2 Minutes, 30 Seconds   |
    +---------- ------------+
    1 row in set (0.00 sec)

    mysql> select time(8230);
    +----------------------+
    |  time(8230) |
    +----------------------+
    |  2 Hours, 17 Minutes, 10 Seconds |
    +----------------------+
    1 row in set (0.00 sec)

    mysql> select  time(7320);
    +----------------------+
    |  time(7320) |
    +----------------------+
    |  2 Hours, 2 Minutes, 0 Seconds   |
    +----------------------+
    1 row in set (0.00 sec)

	
	#############################################################################################
	
	PART #4
	
CALL get_name('Bouloucos');
+---------------+-----------+
| first_name    | last_name |
+---------------+-----------+
| Cristinel     | Bouloucos |
| Vishv         | Bouloucos |
| Kazuhide      | Bouloucos |
| Oguz          | Bouloucos |
| Gennady       | Bouloucos |
| Tiina         | Bouloucos |
| Marla         | Bouloucos |
| Perry         | Bouloucos |








CALL avg_salary('d009'); 
+-------------+
| AVG(salary) |
+-------------+
|  58770.3665 |
+-------------+
1 row in set (0.26 sec)

Query OK, 0 rows affected (0.26 sec)





CALL count_gender('M'); 
+---------------+
| COUNT(gender) |
+---------------+
|        179973 |
+---------------+
1 row in set (0.12 sec)

 call gender('F');
        
    +---------------+
    | count(gender) |
    +---------------+
    |        120051 |
    +---------------+
    1 row in set (0.07 sec)