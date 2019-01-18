# JDBC_Assignment2
Uppgift med SQL-kod och JAVA-kod

SQL-code:

MANAGE DATABASE sqlandjava;

CREATE TABLE `sqljava`.`cars`(
`car_id`INT NOT NULL,
`brand`VARCHAR(45)NOT NULL,
`color`VARCHAR(45)NOT NULL,
PRIMARY KEY(`car_id`));

INSERT INTO `sqljava`.`cars`(`car_id`,`brand`,`color`)VALUES('1','Volvo','Black');
INSERT INTO `sqljava`.`cars`(`car_id`,`brand`,`color`)VALUES('2','Saab','Blue');
INSERT INTO `sqljava`.`cars`(`car_id`,`brand`,`color`)VALUES('3','Audi','Red');
INSERT INTO `sqljava`.`cars`(`car_id`,`brand`,`color`)VALUES('4','Ford','Green');
