Stochastic Gradient Descent
================================

尚未完成。

I managed to create a file-based hashtable, using raw byte encoding offsets to "instantly" 
find records in a text file. The original intent was to use this to randomize the order in 
which documents (single lines in a file) are read by the program, but file-based hashing 
has many applications.

Note that this is NOT extensively tested; it works on Mac OS X 10.8 using UTF-8 encoding 
(enforced by the program). It could change depending on the platform and available encodings.
