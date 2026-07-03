# How to Add Content to Quizly Four

This guide helps you add tutorials, textbooks, videos, and exercises to each course.

## 📁 Folder Structure

Each course has this organization:

```
courses/
└── [course-name]/
    ├── README.md (course overview)
    ├── tutorials/
    ├── textbooks/
    ├── videos/
    └── exercises/
```

## ➕ How to Add Content

### 1. Adding Textbooks

**Where:** `courses/[course-name]/textbooks/`

**File Format:**
- PDF files for formal textbooks
- Markdown (.md) files for web-based content
- Word documents (will be converted to PDF)

**Naming:** `Week1_Introduction.pdf` or `Module1_Basics.md`

**Example Structure:**
```
textbooks/
├── Week1_Introduction.pdf
├── Week2_MainConcepts.pdf
├── Module1_Basics.md
└── Bibliography.md
```

### 2. Adding Tutorials

**Where:** `courses/[course-name]/tutorials/`

**File Format:**
- Markdown (.md) files (recommended - easy to read online)
- Google Docs (shared link)
- PDF guides

**Naming:** `Tutorial_1_GettingStarted.md`

**Markdown Template:**
```markdown
# Tutorial 1: Getting Started

## Objective
What students will learn

## Steps
1. Step one with explanation
2. Step two with screenshots/images
3. Step three with examples

## Summary
Key takeaways

## Practice Exercise
Try this...
```

### 3. Adding Videos

**Where:** `courses/[course-name]/videos/`

**Format:**
- YouTube links (recommended - no uploads needed)
- Embedded video content
- Links to educational video platforms

**How to Add a Video:**

Create a file: `video_list.md`

```markdown
# Course Videos

## Week 1: Introduction
- [Introduction Lecture](https://youtube.com/video-link)
- [Concept Explained](https://youtube.com/video-link)
- Duration: 45 minutes

## Week 2: Main Topics
- [Topic Deep Dive](https://youtube.com/video-link)
- [Q&A Session](https://youtube.com/video-link)
```

### 4. Adding Exercises & Quizzes

**Where:** `courses/[course-name]/exercises/`

**Format Options:**

**Option A: Markdown Quiz**
```markdown
# Quiz 1: Topic Understanding

## Question 1
What is...?
- A) Answer 1
- B) Answer 2
- C) Answer 3
- D) Answer 4

**Correct Answer:** C

**Explanation:** ...

## Question 2
...
```

**Option B: Google Forms**
1. Create quiz on Google Forms
2. Share the link in `exercise_list.md`:
```markdown
# Exercises

## Quiz 1: Topic Understanding
[Take Quiz →](https://forms.google.com/quiz-link)
Time: 15 minutes | Points: 10
```

**Option C: PDF Worksheet**
- Create in Word/Google Docs
- Export as PDF
- Save in exercises/ folder

## 📝 Step-by-Step: Adding Your First Tutorial

1. **Create the file:**
   - Go to: `courses/ethics/tutorials/`
   - Create: `Tutorial_1_EthicsBasics.md`

2. **Write content using this template:**
```markdown
# Tutorial 1: Ethics Fundamentals

## Learning Objectives
- Understand what ethics means
- Learn the three main ethical frameworks
- Apply ethics to real situations

## What is Ethics?
Ethics is... [your explanation]

### Key Terms
- **Ethics:** Definition
- **Morality:** Definition
- **Values:** Definition

## Three Main Frameworks

### 1. Deontological Ethics
[Explanation and examples]

### 2. Consequentialism
[Explanation and examples]

### 3. Virtue Ethics
[Explanation and examples]

## Real-World Example
[Case study or example]

## Key Takeaways
- Point 1
- Point 2
- Point 3

## What's Next?
Move on to Tutorial 2 for deeper analysis...
```

3. **Save and commit** to GitHub

## 🎯 Best Practices

✅ **Do:**
- Use clear, simple language
- Include examples and real-world applications
- Add images/diagrams when helpful
- Break content into small, digestible sections
- Link between related materials
- Provide learning objectives at the start

❌ **Don't:**
- Use very technical jargon without explanation
- Create files that are too long (break into parts)
- Forget to cite sources
- Leave broken links
- Use copyrighted material without permission

## 📊 Content Checklist

Before publishing content, ensure:

- [ ] Follows CC BY 4.0 license
- [ ] Is properly attributed (if adapted from another source)
- [ ] Has clear learning objectives
- [ ] Includes examples
- [ ] Is well-organized and easy to follow
- [ ] Has no broken links
- [ ] Uses accessible language
- [ ] Includes quiz/exercise related to content

## 🔄 Updating Content

To update existing materials:

1. Open the file on GitHub
2. Click the edit button (pencil icon)
3. Make changes
4. Click "Commit changes"
5. Add a brief description of what you changed

## 📞 Need Help?

- Questions about adding content? Contact the Quizly Four team
- Need format advice? Check existing course materials
- Want feedback? Share drafts in the team channel

---

**Happy Teaching! 🎓**

*Last Updated: July 2026*
