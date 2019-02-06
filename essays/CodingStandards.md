---
layout: essay
type: essay
title: Enforcing Standards
# All dates must be YYYY-MM-DD format!
date: 2019-02-04
labels:
  - Software Engineering
  - Learning
  - Coding Standards
---

## Why I (sometimes) Enjoy Standards
Coding standards often receive extremely mixed reviews. Many who are beginning to learn coding absolutely hate having to conform to a very specific set of rules regarding things like spacing and rules. I, on the other hand, almost always enjoyed having coding standards. While they can be frustrating to deal with, they do help to clean up code and especially help new coders to not make spaghetti code. Code that follows rules will look nicer and will be much easier to read and follow in comparison to code that doesn't. When working with an IDE that can import rules, often coding standards are an afterthought as everything is done for the programmer, but my dislike for standards comes when working in a text editor. Having to format code in VIM is a nightmare, even with all of the shortcuts that it has. UH Manoa's ICS 212 course imposed a strict set of coding standards that required exactly 4 spaces instead of tabs as an indent, all braces to have their own line, and many other things. This made me absolutely hate working in text editors and realize how helpful a good IDE is.

### Normal Nested If Statements
```
if() {
  if() {
    if() {
      if() {
      }
    }
  }
}
```
### ICS 212 Nested If Statements
```
if()
{
    if()
    {
        if()
        {
            if()
            {
            }
        }
    }
}
```


## Standards As A Learning Tool
While standards definitely help readers (and the programmer) to understand code, they are also a very useful learning tool. Imposing a set of rules on yourself, especially in regards to how the code actually functions and what types of things are allowed can force creativity out of the programmer. For example, one of the rules for the ICS 212 standards was that only one return statement was allowed per function. These kinds of restrictions force students to think a little out of the box in order to come up with a solution that both works and follows rules.

## The Elusive Green Check Mark
ESLint is one of the major coding standards for the JavaScript language. It requires the code to be formatted very specifically with spaces before open curly braces, having a blank line at the very end of the code, etc. At first, due to my experience with ICS 212, I didn't think I would enjoy having to format code by hand. However, the IntelliJ IDE makes things incredibly simple when dealing with a coding standard. As long as the specific rules are imported beforehand, I don't really have to do anything! The IDE just does all of the editing and formatting for me by letting me know what needs to be changed. All I really need to do is click the button that asks if I want to fix the error and I'm done. The magic green check mark shows that no rules are broken and I have nice code without having to do any extra work.
