Questions
1.Return ALL the data in the 'movies' table.

''' SQL
SELECT * FROM movies
'""

2.Return ONLY the name column from the 'people' table

''' SQL
SELECT name FROM people
'''

3.Oops! Someone at CodeClan spelled Keith's name wrong! Change it to reflect the proper spelling.
Return ONLY your name from the 'people' table.

''' SQL
UPDATE people SET name = 'Keith' WHERE id = 22;
'''

4.The cinema is showing 'Batman Begins', but Batman is DC, not Marvel! Delete the entry from the 'movies' table.

'''SQL
DELETE FROM movies WHERE title = 'Batman Begins';
'''

5.Create a new entry in the 'people' table with the name of one of the instructors.

'''SQL
INSERT INTO people (name) VALUES ('Craig Morton');
'''


6.Pawel has decided to hijack our movie evening, Remove him from the table of people.

'''SQL
DELETE FROM people WHERE name = 'Pawel'
'''


7.The cinema has just heard that they will be holding an exclusive midnight showing of 'Avengers: Infinity War'!! Create a new entry in the 'movies' table to reflect this.

'''SQL
INSERT INTO movies (title, year, show_time) VALUES ('Avengers: Infinity War', 2018, '12.00');
'''

8.The cinema would also like to make the Guardians movies a back to back feature. Find out the show time of "Guardians of the Galaxy" and set the show time of "Guardians of the Galaxy 2" to start two hours later.

'''SQL
UPDATE movies SET show_time = '18.20' WHERE title ='Guardians of the Galaxy 2';
'''

9.Extension
Delete multiple entries from your table in a single command.

'''SQL
DELETE name FROM people;
'''

10.Select all the movies ordered by year in descending order

'''SQL
SELECT * FROM movies ORDER BY year DESC
'''
