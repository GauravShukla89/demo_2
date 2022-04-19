# demo_2
This is a testing repo
CREATE TABLE movie (

    mov_id INT IDENTITY (901,1) PRIMARY KEY,

    mov_title VARCHAR(50) NOT NULL,

    mov_year INT NOT NULL,

    mov_time INT NOT NULL,

    mov_lang VARCHAR(50) NOT NULL,

    mov_dt_rel DATE,

    mov_rel_country VARCHAR(5)

);



INSERT INTO movie (mov_id, mov_title, mov_year, mov_time, mov_lang, mov_dt_rel, mov_rel_country) VALUES (901, 'Vertigo', 1958, 128, 'English', '1958-08-24', 'UK');


