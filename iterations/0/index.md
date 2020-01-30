---
advisors:
  - name: 
    github: 
  - name: 
    github: 
  - name: 
    github: 
  - name: 
    github: 
  - name: 
    github: 
  - name: 
    github: 
  - name: 
    github: 
---

# Iteration 0: 

# Group Formation

Your first task in this iteration is to form a group of 5 or 6 students. You may form your group based on affinity if you already know people in the course, or you may form your group based on shared interests in theme and technology. An ideal group is motivated to work toward the same kinds of problems, but has a diverse background and expertise. A lot of what you learn in this course doesn’t come from the staff, but from the other members of your group.

You may form your group outside class time, or using the forum in the [Students Area](https://github.com/jhu-oose/{{site.course}}-students){:data-proofer-ignore="true"} <small title="You must be a registered student logged into GitHub to see this.">🔒</small>, or in person during Project Meeting 1, which is dedicated to group formation.

After having formed a group, you must register it using the form below:

<form method="POST" action="https://roboose.herokuapp.com/roboose/groups">
<fieldset markdown="1">

<legend>Group Registration</legend>

<label>
**Group Identifier**  
<input type="text" name="identifier" required pattern="[A-Za-z0-9][A-Za-z0-9-]*[A-Za-z0-9]">  
</label>
<small>
This must be a valid GitHub identifier: it may only contain alphanumeric characters or single hyphens, and cannot begin or end with a hyphen.  
Don’t include an `@` sign at the beginning—this isn’t a [mention](https://help.github.com/en/articles/basic-writing-and-formatting-syntax#mentioning-people-and-teams).  
You may choose an identifier related to your project if you already decided on one; for example, if your project were [TODOOSE](https://github.com/jhu-oose/todoose) then your group identifier could be `todoose`. Or you may just choose a name for your group, for example, `power-oosers`.
</small>

<label>
**Group Members GitHub Identifiers**  
<input type="text" name="members[]" required pattern="[A-Za-z0-9][A-Za-z0-9-]*[A-Za-z0-9]">  
</label>
<input type="text" name="members[]" required pattern="[A-Za-z0-9][A-Za-z0-9-]*[A-Za-z0-9]">  
<input type="text" name="members[]" required pattern="[A-Za-z0-9][A-Za-z0-9-]*[A-Za-z0-9]">  
<input type="text" name="members[]" pattern="[A-Za-z0-9][A-Za-z0-9-]*[A-Za-z0-9]">  
<input type="text" name="members[]" pattern="[A-Za-z0-9][A-Za-z0-9-]*[A-Za-z0-9]">  
<input type="text" name="members[]" placeholder="(Optional)" pattern="[A-Za-z0-9][A-Za-z0-9-]*[A-Za-z0-9]">  
<small>
These must be the GitHub identifiers of [registered students](/assignments/0#onboarding), for example, [`jhu-oose-example-student`](https://github.com/jhu-oose-example-student).  
Don’t include an `@` sign at the beginning—this isn’t a [mention](https://help.github.com/en/articles/basic-writing-and-formatting-syntax#mentioning-people-and-teams).  
GitHub identifiers **do not** start with `2019-student-`.  
Groups must have 5 or 6 members.  
</small>

**<small>⚠️</small>  Don’t submit this form multiple times. Your group must be registered by only one of your group members.**

<button>Register</button>

</fieldset>
</form>

If you run into problems, send an email to <group-registration@jhu-oose.com>. Include all the information from the form above.

After you register your group, the group members are invited to a GitHub Team called `jhu-oose/{{site.course}}-group-<identifier>`, which grants you access to a repository at `https://github.com/jhu-oose/{{site.course}}-group-<identifier>`. You’ll use this repository throughout the course to submit iterations, receive reviews, communicate with your advisor, and so forth.

By the end of Sprint 1, you’ll be assigned a permanent advisor.
