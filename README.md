The challenge for this week was to refactor code to make a website more accessibile.
To do this semantic elements had to be added to the HTML, which helps both
accessibility and organization (especially at a strictly visual level).
In addition the images all had alt attributes added. Finally, heading attributes
occur in sequential order (as a h3 was used just because it was small, so this was
edited so that it was an h2 element and the stylesheet changed the font size), and
the title was edited to include a descriptive title. I also edited the style sheet
to remove redundancy, and in doing this I also had to remove many of the redundant classes
in the index.html file, as they were no longer necessary. The style sheet was also
edited so that all the style occurs in decending order in respect to the cascade,
making everything a tad easier to find, organized (comments were added to seperate
stylized elements based on their section), and concice (several classes were defined
to provide style, that were not necessary as each class was implimenting the same style
so by getting rid of the class and calling the div tag instead, three elements were styled
with one statement vs three calls all doing the same thing). Also the p styling was gotten
rid of to remove redundancy, as it legitimately wasn't doing anything, as the default for
the p tag is 16px font size, so to eliminate redundancy again this code was removed. This
means that both the acceptance criteria, and the scout rule were upheld in this assignment.
(note: I accidentally broke my first repository that held my project so a screensot has been added of the past commits to the resources folder.)