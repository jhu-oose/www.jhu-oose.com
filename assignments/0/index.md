---
tools:
  - IntelliJ IDEA
  - Postman
  - Google Chrome
  - Git
  - GitHub
  - Paper & Pencil
  - Java
  - Gradle
  - Javalin
  - Jackson
  - JUnit
  - SQLite
  - JavaScript
  - Hypertext Markup Language (HTML) & Cascading Style Sheets (CSS)
  - React
  - JavaScript Object Notation (JSON)
  - Heroku
  - Travis CI
  - Markdown
---

# Assignment 0: Project Proposal

# Onboarding

**Welcome to OOSE!**

One of the points of this course is that we aren’t using only pedagogical tools, but tools actually used by software engineers. To bring this point home, we run the course similar to how a software project is run, using the tools that software engineers use to coordinate their work. You’ll use [GitHub](https://github.com) throughout the course to submit assignments, ask questions, collaborate with the other members of your group in the [group projects](/group-projects), and so forth. If you don’t have a GitHub account, [create one now](https://github.com/join). Then register for the course using the form below:

<video src="https://archive.org/download/jhu-oose/onboarding-and-assignment-submission.mp4" controls preload="none"></video>

<form method="POST" action="https://roboose.herokuapp.com/roboose/students">
<fieldset markdown="1">

<legend>Student Registration</legend>

<label>
**GitHub Identifier**  
<input type="text" name="github" required pattern="[A-Za-z0-9][A-Za-z0-9-]*[A-Za-z0-9]">  
</label>
<small>
For example, [`jhu-oose-example-student`](https://github.com/jhu-oose-example-student).  
Don’t include an `@` sign at the beginning—this isn’t a [mention](https://help.github.com/en/articles/basic-writing-and-formatting-syntax#mentioning-people-and-teams).  
GitHub identifiers **do not** start with `2019-student-`.  
</small>

<label>
**Hopkins Identifier**  
<input type="text" name="hopkins" required pattern="[0-9A-F]{6}">  
</label>
<small>
For example, `7B4EF0`.  
This is the 6-character “Hopkins ID” in [SIS](https://sis.jhu.edu/), **not** your email.
</small>

**<small>⚠️</small>  Don’t submit this form multiple times.**

<button>Register</button>

</fieldset>
</form>

If you run into problems, send an email to <student-registration@jhu-oose.com>. Include all the information from the form above.

After you register, you are invited via email to the GitHub organization for the course, [`jhu-oose`](https://github.com/jhu-oose), joining the team `jhu-oose/{{site.course}}-students`, which grants you access to the [Students Area](https://github.com/jhu-oose/{{site.course}}-students){:data-proofer-ignore="true"} <small title="You must be a registered student logged into GitHub to see this.">🔒</small>, where you may find a public forum (visible only to other students in the course), announcements, videos of the lectures, and so forth.

After you register, you are also invited via email to a repository at `https://github.com/jhu-oose/{{site.course}}-student-<identifier>`. This is your individual repository in which you’ll submit the [assignments](/#individual-assignments), receive grades, ask questions visible only to the staff, and so forth.

## Profile

<small>
**10 points**
</small>

<small>
Submit your profile as a [Markdown](/toolbox#authoring-language-markdown) document at `README.md` in the `master` branch of your personal repository at `https://github.com/jhu-oose/{{site.course}}-student-<identifier>`.
</small>

Fill in the template below (parts marked with `<!-- -->` are placeholders that you must fill in):

```
# <!-- Name -->

![Profile Picture](<!-- Show your face, because the purpose of the profile picture is to be able to recognize you, see for example the pictures at https://www.jhu-oose.com/staff -->)

**Personal Pronoun (Optional):** <!-- See https://www.mypronouns.org to understand more about this question. Answer (if you wish) in the form of a link, for example, [She/her](https://www.mypronouns.org/she-her) -->

# Background

<!-- Are you fresh out of a data structures course? Do you have years of experience in industry? What technologies do you usually work with? What are your interests? And anything else you want to share. -->

# Expectations

<!-- Why did you sign up for the course? What do you expect to learn? And anything else you want to share. -->
```
