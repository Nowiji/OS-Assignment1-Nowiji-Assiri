# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** |nowiji ali assiri|
| **Student ID** | [446050923] |
| **University Email** | [446050923]@std.psau.edu.sa |
| **GitHub Username** | [nowiji] |
| **Repository Link** | [https://github.com/Nowiji/OS-Assignment1-Nowiji-Assiri] |
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [09/10/2026 , 5:00am]
**What I did**: make account in github

**Details**: add university email and pass and user name

**Challenges**: Nothing is difficult

**Solution**: now i have account

**Time spent**: maybe 30 min

---

### Entry 2 - [09/10/2026 , 5:30am]
**What I did**: rename the file 

**Details**:rename the file to my name 

**Challenges**: Nothing is difficult

**Solution**: completed

**Time spent**: 15 min

---

### Entry 3 - [09/10/2026 , 5:45am]
**What I did**: started file SchedulerSimulation.java

**Details**: i read the entrie code and started to understand it

**Challenges**: At first, I had trouble with the code, but I understood it after analyzing it

**Solution**: i understand the code 

**Time spent**: 30 min

---

### Entry 4 - [09/10/2026 , 6:15am]
**What I did**: I added the features as required in the file and finished parts 3 and 4

**Details**:I added the three points to the third part, along with the details and the required time; then I reviewed the fourth part and finished its file

**Challenges**: I encountered significant difficulty adding features, particularly regarding the process priority aspect

**Solution**:After numerous attempts, I added the features and fine-tuned the code.

**Time spent**: 2 hours and 30 in maybe or maybe more

---

### Entry 5 - [09/10/2026 ,2:00pm]
**What I did**:I recorded a video about the entire project

**Details**: I recorded a video about the project, approximately 2 minutes and 30 seconds long.

**Challenges**: I was worried the video would run longer than three minutes, but I finished it ahead of schedule.

**Solution**: finish the video

**Time spent**: 5 min

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [5 hours]

**Most challenging part**: Part 2: I didn't understand it correctly at first, but then I analyzed the code and the requirements, and figured out the answer.

**Most interesting learning**: Every step I started without understanding, I eventually began to grasp.

**What I would do differently next time**: I could try it out in other ways to learn more about it.

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

[Working on this project helped me understand how threads can be used to simulate process execution. I learned that the `Runnable` interface defines the task, while a `Thread` is used to run it. I also learned how `start()` begins a thread and `join()` makes the main thread wait for it to finish. The ready queue helped me understand how processes can wait for their turn to use the CPU. Using `Thread.sleep()` also helped simulate the time spent executing each process. Overall, this project made multithreading and CPU scheduling easier for me to understand.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[One challenging part was managing the ready queue and making sure each process got its turn. A process may need more than one time quantum to finish, so it cannot always be removed permanently after running once. I had to understand how the remaining time changes after each execution. The program also needs to check whether a process has finished before adding it back to the queue. Understanding the relationship between the process objects and their threads was important too. These parts helped me understand the logic behind the scheduling algorithm.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I worked through the scheduling logic step by step and looked at how each part of the code was connected. I focused on how processes enter the ready queue, execute for a time quantum, and either finish or return to the queue. I also reviewed how the program uses `start()` and `join()` to control execution. Reading the remaining time after each quantum helped me understand when a process should run again. Breaking the program into smaller parts made the overall logic easier to follow. This approach helped me understand the purpose of the main methods.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[CPU scheduling is important because a computer often has many tasks that need processing time. Round-Robin scheduling gives each ready process a limited time slice before moving to another process. This can help make a system feel more responsive when several tasks are waiting. The ready queue represents tasks waiting for CPU time, while the time quantum limits each turn. Multithreading is also useful in applications that need to handle different tasks without blocking everything else. Learning these concepts helped me understand some of the ideas behind how operating systems manage work.]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

[The ready queue stores the threads that are waiting for their turn to execute. In this project, a FIFO queue is used, which means the thread at the front of the queue is selected first. The time quantum defines the maximum amount of simulated execution time a process receives during one turn. If a process still has remaining time and other processes are waiting, it is added back to the end of the queue. This gives other processes a chance to execute instead of allowing one process to use the CPU for its entire burst time. In the code, the time quantum is selected randomly from 2000, 3000, 4000, or 5000 milliseconds.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[The ready queue stores the threads that are waiting for their turn to execute. In this project, a FIFO queue is used, which means the thread at the front of the queue is selected first. The time quantum defines the maximum amount of simulated execution time a process receives during one turn. If a process still has remaining time and other processes are waiting, it is added back to the end of the queue. This gives other processes a chance to execute instead of allowing one process to use the CPU for its entire burst time. In the code, the time quantum is selected randomly from 2000, 3000, 4000, or 5000 milliseconds.]

Example from my output:
```
[Paste a relevant snippet from your program output here showing a process being re-queued]
```

**Explanation of example:**
[Explain what is happening in the output snippet you pasted.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1 is in the New state when addProcessToQueue() creates a thread using new Thread(process).]

2. **Runnable**: [P1 becomes Runnable when the scheduler calls currentThread.start()]

3. **Running**: [P1 executes its run() method and simulates CPU execution for its time quantum.]

4. **Waiting**: [P1 enters Timed Waiting when Thread.sleep() pauses its execution. The main thread waits for P1 to finish by calling currentThread.join()]

5. **Terminated**: [P1's thread reaches the Terminated state when its run() method finishes.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [CPU Scheduling]

**Description**:
[An operating system uses CPU scheduling to give different processes a chance to use the CPU. In Round-Robin scheduling, each process gets a fixed time quantum. If a process does not finish, it goes to the end of the ready queue, like P4 in my simulation.]

**Why Round-Robin works well here**:
[ound-Robin is fair because each process gets a turn to use the CPU. It also improves responsiveness because one process cannot use the CPU for a long time without giving other processes a chance. The time quantum controls how long each process runs before a context switch.]

### Example 2: [Multithreaded Web Server]

**Description**:
[A web server can use multiple threads to handle requests from different users. Each thread can represent a task, such as processing a user's request. A Round-Robin-like approach can give each ready task a short time to execute before another task gets a turn.]

**Why Round-Robin works well here**:
[This approach can improve fairness by giving different tasks a chance to run. It can also help the system respond to several requests without allowing one CPU-bound task to use all the CPU time. The time quantum determines each turn, and a context switch happens when the CPU changes from one task to another.]

## Summary

**Key concepts I understood through these questions:**
1. I learned how Round-Robin scheduling uses a time quantum to share CPU time between processes.
2. I understood how an unfinished process returns to the end of the ready queue.
3. I learned how Java threads use methods such as start(), sleep(), and join()

**Concepts I need to study more:**
1. I need to understand context switches and how they affect CPU scheduling.
2. I need to learn more about Java thread states and how threads are scheduled by the operating system.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
