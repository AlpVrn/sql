CRETAE TABLE employee(
    id INTEGER PRIMARY KEY,
    name VARCHAR(50) NOT NULL,
    birthday DATE,
    email VARCHAR(50)
);

INSERT INTO employee (id, name, birthday, email) VALUES
(1, 'Kaeya', 1996-02-01, 'kaeya@alberich.com'),
(2, 'Diluc', 1994-06-14, 'diluc@batman.com'),
(3, 'Zhongli', 1460-01-19, 'zhongli@grandpa.com'),
(4, 'Childe', 1999-08-21, 'tartaglia@murdurer.com'),
(5, 'Ayato', 1990-10-10, 'ayato@kamisato.com'),
(6, 'Thoma', 1998-11-07, 'thoma@malewaifu.com'),
(7, 'Itto', 1949-12-31, 'itto@bestoni.com'),
(8, 'Al-Haitam', 1992-03-29, 'alhaitam@charisma.com'),
(9, 'Kaveh', 1997-04-12, 'kaveh@arcitecht.com'),
(10, 'Baizhu', 1988-10-27, 'baizhu@doctor.com');

UPDATE employee 
SET name = 'my love'
WHERE id = 1;

DELETE FROM employee
WHERE id = 10;