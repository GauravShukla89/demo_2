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

