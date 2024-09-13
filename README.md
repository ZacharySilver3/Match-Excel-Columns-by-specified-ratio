Values for function augments should be as follow:
file_path = path where your excel file is saved
sheet = sheet name
c1 = column name for column you want compared
c2 = second column name for column you want compared
output path = defaults to None which is later changed to current directory. Can also specify where you want saved
match_ratio = the ratio you want the strings to be matched on. Can use whatever. Be wary the lower you get
mode = defaults to 0 which does not alter the strings in the columns. any other value will have the match strip the strings of punctuation and white spaces, put all in lower case and sort alphabetically. This is useful when trying to compare, for example, names where the middle name isnt included in one. You may have to lower the match ratio for this to work.
