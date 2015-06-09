# exam
LaTeX exam git project

This takes my document class for exams and wraps it into a git project. The idea being for a specific class, there isn't much I actually want to change in an exam. To use simply git clone this repo; Edit the exam_header.sty and instructions.tex, then commit and your class is setup for the semester. 

For each exam I do the following picking EXAMNAME's that make sense to me:
0) git checkout master
1) git branch EXAMNAME
2) git checkout EXAMNAME
3) Edit exam.tex and compile and commit changes.

Then if I have to create an alternative makeup exam I can branch from the EXAMNAME branch to ensure it looks someting like the original exam.

I have pdf files added to the .gitignore so you'll have to recompile whenever you switch branches to get the correct pdf.

Copyright 2015 Nate Iverson

This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

