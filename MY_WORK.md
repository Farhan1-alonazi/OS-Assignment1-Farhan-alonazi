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
| **Full Name** | [Farhan Hussein Alonazi] |
| **Student ID** | [446050414] |
| **University Email** | [446050414]@std.psau.edu.sa |
| **GitHub Username** | [your-github-username] |
| **Repository Link** | [Paste your repository link here] |
 
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

### Entry 1 - [ October 4 - 5:00 pm]
**What I did**: What I Did: Reviewed the assignment requirements and examined the starter code to understand how the Round-Robin scheduler and ready queue work and  Updated my student ID in SchedulerSimulation.java and committed the change to GitHub


**Details**: 
Reviewed the existing scheduler behavior before implementing the requested features.
Identified the changes needed to implement the requested features while preserving the original scheduler behavior.
Examined the existing process creation and ready queue logic.
Located the student ID in the source code.
Replaced it with my own student ID.
Committed the modification to the GitHub repository.

**Challenges**: 
Understanding the existing scheduler structure and determining where the new features should be implemented.
 Identifying the correct location of the student ID in the starter code.



**Solution**: 
Read the relevant parts of the source code and connected the assignment requirements to the existing implementation.
Located the relevant field and updated the student ID before committing the change.
**Time spent**: 4 Hours

---

### Entry 2 - [ October 6 - 9:00 pm ]
**What I did**:  Implemented Feature 1 by adding randomized process priorities from 1 to 10 and displaying each priority when a process enters the ready queue.
**Details**: 
  Added the priority field to the Process class.
  Added setPriority() and getPriority() to assign and retrieve the priority value.
  Generated the priority using 1 + random.nextInt(10).
  Updated addProcessToQueue() to display the process priority alongside its name and burst time.
  Kept processQueue in FIFO order so priority would not change the Round-Robin scheduling sequence.
  Committed the implementation using the Feature 1 commit.

**Challenges**: Adding randomized priorities while ensuring that the scheduler continued to process threads in FIFO order.

**Solution**: Used the priority field for display and tracking only, without using it to sort or reorder the ready queue.
**Time spent**: 2 days

---

### Entry 3 - [ October 7 - 1:38 am]
**What I did**: implemented Feature 2 by adding a static context-switch counter that increases whenever the scheduler starts the next process thread.

**Details**: 
Added the static variable contextSwitches to SchedulerSimulation.
Incremented the counter inside the scheduling loop before currentThread.start().
Kept the counter shared across the scheduler because it is declared static.
Added output to display the total context-switch count.
Committed the change using the Feature 2 commit.

**Challenges**: dentifying the appropriate point in the scheduling loop to increment the counter for each process start

**Solution**: laced the increment immediately before currentThread.start() so the counter increases whenever the scheduler starts the next thread.

**Time spent**: 18 hours 

---

### Entry 4 - [ October 7 - 2:35 am  ]
**What I did**: Implemented Feature 3 by adding waiting-time tracking and a final summary table containing each process's burst time, waiting time, and turnaround time

**Details**: 
Added readyQueueEntryTime and waitingTime fields to the Process class.
Used System.currentTimeMillis() to record the time associated with a process entering the ready queue.
Added markReady() to record the ready-queue timestamp.
Added updateWaitingTime() to accumulate elapsed time.
Added getWaitingTime() and getTurnaroundTime() to retrieve the timing results.
Added a final summary table displaying Process Name, Burst Time, Waiting Time, and Turnaround Time.
Committed the change using the Feature 3 commit.

**Challenges**: Tracking elapsed waiting time and calculating turnaround time for each process.

**Solution**: Added timing fields and methods to Process and used waitingTime + burstTime for the turnaround-time calculation required by the assignment.

**Time spent**: 2 hours

---

### Entry 5 - [October 8 - 8:00 pm ]
**What I did**: Tested the updated scheduler by running the program and checking the process priorities, context-switch counter, and waiting-time and turnaround-time summary.

**Details**: 
Ran the simulation with 13 processes and a time quantum of 2000 ms.
Checked that each process displayed a randomized priority between 1 and 10 when added to the ready queue.
Verified that the ready queue continued to follow FIFO order, while unfinished processes were returned to the queue after using their time quantum.
Checked the context-switch counter, which displayed a final total of 25.
Examined the process summary table containing process names, burst times, waiting times, and turnaround times.
Noticed that some process names appeared more than once in the summary table, so the final output needed further checking.


**Challenges**:The final process summary contained duplicate entries, and the waiting-time values needed to be checked to ensure that they accurately represented the time each process spent waiting in the ready queue.

**Solution**: Compared the summary table with the 13 processes created by the simulation and identified the duplicate entries as an issue to investigate. I also reviewed the waiting-time and turnaround-time calculations to determine whether the timing logic was producing accurate results.

**Time spent**: 4 days

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

**Total time spent on assignment**: [X hours]

**Most challenging part**:

**Most interesting learning**:

**What I would do differently next time**:

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

I learned how Java uses the Runnable interface and the Thread class to execute tasks. I understood that the Process class represents a simulated process, while a Java Thread executes its run() method. I learned that Thread.start() starts a new thread, whereas Thread.join() makes the calling thread wait for that thread to finish. I also learned how Thread.sleep() can simulate execution time in a scheduling simulation. The Round-Robin algorithm helped me understand how a ready queue can give processes turns to use the CPU. Finally, I learned that tracking waiting time requires recording when a process enters the ready queue and when it starts executing.

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*
The most challenging part of this assignment was understanding how to calculate the waiting time of each process accurately. A process may execute for one time quantum and then return to the ready queue if it still has work to complete. This means that its total waiting time can include several separate waiting periods. I had to distinguish between the time a process spends waiting in the queue and the time it spends executing. I also needed to understand how re-queuing affects the final statistics displayed by the scheduler. This challenge helped me realize that the order of method calls is important when implementing scheduling algorithms.

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

I approached the challenges by reviewing the assignment instructions and studying the scheduler code carefully. I focused on how processes are added to the ready queue, started using threads, and checked after each time quantum. I used the roles of Thread.start(), Thread.join(), and Thread.sleep() to understand how execution is coordinated. For waiting-time tracking, I examined how System.currentTimeMillis() could be used to measure elapsed waiting periods. I also identified the importance of checking the final output for duplicated process entries and incorrect counter placement. These steps helped me develop a clearer understanding of the program and how to test its behavior.
## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

Multithreading is useful in many applications that need to perform several tasks while remaining responsive. One example is an operating system, which schedules runnable tasks and shares CPU time among them according to its scheduling policy. Round-Robin scheduling can help provide fairness by allowing each eligible task to receive a time slice. Another example is a music player, which can play audio while downloading music or responding to user interactions. In this case, different tasks can execute using separate threads without requiring the user interface to stop responding. The concepts of scheduling, coordination, and execution time from this assignment help explain how such applications manage concurrent work.
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

A process is a program in execution with its own memory space and resources, while a thread is a unit of execution within a process. Separate processes generally have separate memory spaces, whereas threads within the same process can share memory and resources. Communication between threads usually has less overhead than communication between separate processes. In this assignment, the Process class represents a simulated process and implements Runnable. The statement new Thread(process) creates a Java thread that can execute the simulated process.

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*
Round Robin scheduling gives each process a fixed time quantum to execute. If a process does not finish within this time, it is returned to the end of the ready queue with its remaining burst time. The scheduler then selects the next process in the queue. This continues until all processes finish executing.

Example from my output:
 P2 executing quantum [2000ms] 
  ? Quantum progress: [███████████████] 100%
  ? P2 completed quantum 2000ms │ Overall progress: [████████░░░░░░░░░░░░] 44%
     Remaining time: 2463ms
  ? P2 yields CPU for context switch

  ? P2 added to ready queue │ Burst time: 4463ms │ Priority: 5
Total context switches: 2
┌─ Ready Queue ─────────────────────────────────────────────────────────────────
│ [P4 ? P5 ? P6 ? P7 ? P8 ? P9 ? P10 ? P11 ? P12 ? P13 ? P1 ? P2]
└─────────────────────────────────────────────────────────────────```
[Paste a relevant snippet from your program output here showing a process being re-queued]
```

**Explanation of example:**

P2 initially needs 4463 ms of CPU time, which is longer than one 2000 ms time quantum. After each of its first two turns, it has unfinished work, so the scheduler places it back in the ready queue. On its third turn, P2 uses the remaining 463 ms and finishes. This demonstrates how Round-Robin shares CPU time fairly among processes.

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

 1. New: P1's thread is created using new Thread(process) inside addProcessToQueue().

2. Runnable: P1's thread becomes runnable when the scheduler calls currentThread.start().

3. Running: P1 executes its run() method to simulate process execution.

4. Waiting: P1 enters timed waiting when Thread.sleep() is called inside run(). Meanwhile, the main thread waits for P1 to finish when currentThread.join() is called.

5. Terminated: P1's thread enters the terminated state after its run() method finishes
and its execution ends.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Name of scenario]

Application 1: Operating System CPU Scheduling

Operating systems use CPU scheduling to manage multiple processes that need processor time. Round-Robin scheduling assigns each process a fixed time quantum to execute. If a process does not finish within its time quantum, it returns to the ready queue. This allows other processes to execute and helps distribute CPU time fairly. My assignment simulates this behavior using a FIFO queue and Java threads.

### Example 2: [Name of application/scenario]

Application 2: Background Tasks in Desktop Applications

Desktop applications use multithreading to perform background tasks while keeping the user interface responsive. For example, a music player can play audio while downloading files or processing user input. Background tasks can run separately so that one task does not unnecessarily block the entire application. Scheduling techniques help manage access to processing resources when multiple tasks need execution time. This relates to my assignment because it demonstrates thread execution, coordination, and sharing CPU time.

## Summary

**Key concepts I understood through these questions:**
1. A simulated Process object is executed by a Java Thread through the Runnable interface.
2. Round-Robin uses a FIFO ready queue and returns unfinished processes to the queue after each time quantum.
3. start(), sleep(), and join() have different roles: starting a thread, pausing that thread temporarily, and making another thread wait for it.

**Concepts I need to study more:**
1. How Java thread states relate to the simplified New/Runnable/Running/Waiting/Terminated lifecycle.
2. How to measure ready-queue waiting time accurately and avoid duplicate process rows in a summary table.

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
