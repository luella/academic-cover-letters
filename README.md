# academic-cover-letters

Need to read file from the input source: cover_letter.tex , school.csv

cover_letter.tex: the format of your cover letter. Variables in the cover letter are %(Address), %(Position), %(Department), %(School), %(Materials), %(References) 

school_details.csv: it contains the details you want to add for the variables you want to change

Script finds and replaces the variables in a template cover letter

Creates PDF with CoverLetter-SchoolName.pdf

Run script from command line using python gencovletter.py cover_letter.tex school_details.csv

