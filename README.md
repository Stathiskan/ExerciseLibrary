# ExerciseLibrary
Exercise Library  You have the following relations between entities:  There is a Library that has a collection of Books and a list of authorized Users. Each Book has an Author, title and a unique id (isbn in real life). The Library is operated by a Librarian The User can make request regarding Authors and Book availability only by asking the Librarian. No direct contact to the other entities should be attempted! Create all the necessary classes as much independent from each other as possible (loose coupling). The rest of the logic should be in class Program. In main() we want to call a static function Program.AsksForBook(user, librarian, book) which prints whether the user can access the book if the book exists in the library.
