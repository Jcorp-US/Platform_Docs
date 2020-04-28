# Gradebook

The grade book is a convenience. It helpfully compiles a list of all assignments, quizzes, and other grade-able content in a course, along with a list of participating students &mdash; and their grades.

***
## Gradebook Setup

<img src="./files/teachers_gradebook.png" style="text-align: center;display: block;min-width: 75%;width: 75%;margin: 0 auto;" />

The grade book, as is common, is a table. The top row of the table detonates columns. It contains a list of assignments, quizzes, and other grade-able content. Each heads a column in which all scores belong to that assignment. On the leftmost column (the first row of which reads *Students*), is a list of participating students (students who have submitted at least one piece of grade-able content are considered *participating*). Each leads a row in which all scores belong to that student.

*  In summary, each score belongs to the *assignment (or quiz, etc)* that it is in the same *column* as, and the *student* that it is in the same *row* as. 

Each score in the grade book is editable. To override a score (which you may have provided, or which may have been automatically generated), click on it and type in the new score. When you click off of it, it will be updated. **NOTE**: You can edit all scores that have a percent (e.g. 92.9%) and all scores that have been submitted (assignments and quizzes), but not yet graded (ungraded assignments appear as *&#x5f;&#x5f;.&#x5f;&#x5f;%* and, when hovered, have a yellow background); however, you _may not_ change scores that do not have a record (unsubmitted assignments and quizzes that have not been taken). They, for reference, are grayed out, and also appear as *&#x5f;&#x5f;.&#x5f;&#x5f;%*.

**NOTE**: For assignments and quizzes that have been submitted multiple times (if allowed), only the most recent score is shown.

On one last note, scores *must* be numbers. They can contain a percent symbol (%, though it will be automatically added), and a decimal point (**.**, for floating point numbers), but no other letters or special characters.

***
## Exporting the Gradebook

The gradebook is a table; and, it can be exported as a table. Gradebook exports can be used for record keeping, printing (a physical copy, for instance), or transferring grades to a dedicated gradebook (with more features, surely, and likely containing physical grades created in class).


Gradebooks can be exported to multiple formats, as described below:
### Export Options
* **CSV**: *This is the preferred option.* CSV files, or Comma Separated Value files, are widely understood and enjoy expansive compatibility. CSVs can be opened by Microsoft Excel and the likes &mdash; where they can be edited or printed &mdash; or imported into a variety of gradebook management systems. CSVs can handle a near-unlimited amount of data.
* **PDF**: PDFs (or Portable Document Format files) are also popular. However, they are more popular for printed documents. A gradebook, when exported as a PDF, appears as a table on a portrait page. PDFs can be printed or saved, but cannot be imported into other systems. The amount of data they can store is also limited. After all, only ~20 assignments or quizzes (et cetera) can fit on a PDF (though, the length of the assignment/quiz/etc. names play a big factor). An unlimited number of students can fit, though. If the gradebook cannot reliably fit on a PDF, our systems may not display it correctly. This is a [known issue](https://platformlms.org/support/bugs/view?id=77987).


To get a gradebook export, click either the _.pdf_ or _.csv_ link on the top-right corner of the gradebook page.

***

All in all, the gradebook is a great way of organizing all of the grade-able content in a course by teacher. Additionally, it provides a means of communication between Platform and other dedicated gradebooks.

Now that you've read about the gradebook, maybe take a look at [assignments](#/04-using_platform/03-courses/03-assignments/01-about_assignments.md) or [quizzes](#/04-using_platform/03-courses/04-quizzes/02-information.md)? If you've already seen those and want to move on, try reading about [files](#/04-using_platform/03-courses/06-files.md).
