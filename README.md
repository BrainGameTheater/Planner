# 📋 Task Management System with Claude

A free, interactive task management system that uses Claude AI to keep your weekly planner and master task list automatically synced.

## 🎯 Three Layout Options

This system includes **three different planner layouts** you can mix and match:

1. **Week At-A-Glance** - See your entire week on one page with a grid background (perfect for visual planners!)
2. **Daily Pages** - One full page per day with tons of space for notes (ideal for detailed planning)
3. **Master Task List** - Organize all your tasks by project/category (great for the big picture)

**Pro tip:** Use the Master Task List + your favorite weekly view together. Claude keeps them both synced automatically!

---

## 🚀 Quick Start Guide

### Step 1: Choose Your Layouts
Browse the HTML files in this repository and download whichever planner layouts you want to use.

### Step 2: Create Artifacts in Claude
1. Go to [Claude.ai](https://claude.ai) and start a new conversation
2. Copy the HTML code from your downloaded file
3. Paste it into Claude and say: **"Create an artifact from this code"**
4. Repeat for each layout you want
5. Done! You now have interactive planners

### Step 3: Add the Project Instructions
Copy the "Task Management System Instructions" (see below) and paste them into your Claude chat. This teaches Claude how to automatically manage your tasks.

### Step 4: Start Using It!
Just talk to Claude naturally:
- "Today is Monday. Add these tasks: grocery shopping, call dentist, finish report"
- "I finished the grocery shopping and dentist call"
- "Move the report to Friday and make it top priority"

Claude updates both artifacts automatically and keeps everything synced!

---

## 💡 Which Layout Should I Use?

**Week At-A-Glance**
- Best for: Visual people who want to see the whole week at once
- Perfect if: You like to plan your week on Sunday and track daily progress

**Daily Pages**
- Best for: Detailed planners who need lots of writing space
- Perfect if: You have many appointments, notes, or detailed tasks each day

**Master Task List**
- Best for: Project-based thinkers who organize by category
- Perfect if: You work on multiple projects and want to see all related tasks together

**My setup:** I use the Master Task List + Week At-A-Glance together!

---

## ⭐ Pro Tips

### Customize Your Categories
Tell Claude what categories fit your life:
- "Change the categories to: Work, Personal, Health, Side Projects"

### Keep Everything Synced
Always tell Claude when you complete tasks:
- "Finished the presentation and paid the electric bill"
- Claude marks them complete in both the master list and weekly planner

### Start Each Chat With the Date
Claude doesn't remember dates between conversations, so start with:
- "It's Wednesday, October 9th" 
- This helps Claude schedule tasks to the right day

### Bookmark Your Conversation
- ⭐ Star/favorite this conversation in Claude so you can find it easily
- Name it "Task Manager" or "My Planner"
- On mobile: Use the Claude app for the best experience

---

## 🛠️ Alternative: Use as Standalone HTML

Don't want to use Claude? You can still use these planners:

1. Download the HTML files from this repository
2. Open them directly in your browser
3. The checkboxes and text areas work without Claude

**Note:** Without Claude, you'll need to manually edit the HTML code to update tasks and dates. Using it with Claude is much easier!

---

## ❓ FAQ

**Q: Do the checkboxes save when I refresh?**  
A: No - that's why you tell Claude what you completed, and Claude updates the code permanently.

**Q: Can I bookmark the artifacts directly?**  
A: No, but you can bookmark/star the conversation and access the artifacts through it.

**Q: How do I update dates in the weekly planner?**  
A: Just tell Claude: "Update the weekly planner to show October 7-13" and it will change all the dates.

**Q: Can I add more weeks to the planner?**  
A: Yes! Tell Claude: "Add next week to the planner" and it will extend it.

---

## 📝 Task Management System Instructions

Copy and paste these instructions into your Claude chat to enable automatic task management:

```markdown
# Task Management System Instructions

## Core Principles
1. **Always maintain both artifacts:** When tasks are added, completed, or rescheduled, update both the Master Task List artifact and the Weekly Planner artifact to keep them in sync.

2. **Automatic scheduling:** When I mention tasks with specific dates or days (like "today," "Wednesday," "Friday"), automatically add them to the appropriate day in the Weekly Planner.

3. **Completion tracking:** When tasks are marked complete, check them off and gray them out in both artifacts. Keep completed tasks visible at the bottom of their respective sections/days.

4. **Priority marking:** When I indicate a task is top priority, move it to the top of the list and format it with underline and/or bold.

5. **Project categorization:** Organize tasks in the Master Task List under appropriate project categories (customize these to match your needs).

6. **Weekly Planner reference:** Always reference the Weekly Planner artifact when discussing daily schedules, task timing, or what needs to be done on specific days.

## Important Notes
- I will tell you the current day when starting conversations, as you don't have persistent memory of the date between chats
- When I say a task is "complete" or "done," mark it complete in both artifacts immediately
- Ask for clarification if you're unsure which day a task belongs to
```

---

## 📂 Files in This Repository

- `week-at-a-glance.html` - Single-page weekly overview with grid background
- `daily-planner.html` - Multi-page daily planner with one page per day
- `master-task-list.html` - Project-based task organization
- `README.md` - This file

---

## 📄 License

Free to use and modify. No attribution required.

---

## ✨ Why This System Works

✅ **Two-way sync** - Master list and weekly planner always match  
✅ **Visual progress** - See completed tasks in gray  
✅ **Flexible** - Customize categories and layout to fit your life  
✅ **Mobile-friendly** - Works on phones and tablets  
✅ **AI-powered** - Claude helps you stay organized and on track  
✅ **Free** - Just needs a Claude account  

---

**Questions?** Open an issue and I'll help troubleshoot!

**Want to share improvements?** Submit a PR - let's make this even better together!
