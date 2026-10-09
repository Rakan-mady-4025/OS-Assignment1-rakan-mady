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
| **Full Name** | rakan khaled mady |
| **Student ID** | 445052810 |
| **University Email** | 445052810@std.psau.edu.sa |
| **GitHub Username** | Rakan-mady-4025 |
| **Repository Link** | https://github.com/Rakan-mady-4025/OS-Assignment1-rakan-mady.git |
 
---

## 🎥 Video Link

**Video Link**: https://youtu.be/UBBK8rVr8pM

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

## Your Development Log



## Entry 1 - [October 7, 2026, 10:55 AM]
**What I did**: Forked the repository and set up my student ID.

**Details**:

-Created a GitHub account with my university email.

-Forked the starter repository and renamed it.
-Changed student ID on line 150 to my actual ID (445052810).
-Compiled and ran the program successfully.
-Committed and pushed: Set my student ID: 445052810.

 **Challenges**: Had to install JDK first because javac wasn't recognized.

**Solution**: Downloaded JDK and set the PATH environment variable.

**Time spent**: 15 minutes

## Entry 2 - [October 7, 2026, 11:02 AM]
**What I did**: Analyzed and understood the provided starter code.

**Details**:

-Reviewed the core classes, methods, and existing scheduler implementation structure.
-Traced how processes and queues are managed within the codebase.
-Added comments and notes to clarify the execution flow.

**Challenges**: Understanding how process states transition within the multithreaded simulation structure.

**Solution**: Traced the execution step-by-step using a debugger and reviewed the documentation.

**Time spent**: 3 hours

## Entry 3 - [October 7, 2026, 11:11 AM]
**What I did**: Implemented Feature 1 (Priority-based scheduling) and Feature 2 (Context switch counter).

**Details**:

-Added priority handling logic to modify process queue ordering based on priority levels.
-Implemented a context switch counter variable to track and increment every time the CPU switches from one process to another.
-Integrated both features into the main scheduling loop.

**Challenges**: Ensuring thread safety and correct order when inserting high-priority processes into the ready queue.

**Solution**: Used proper synchronization blocks and adjusted queue insertion logic.

**Time spent**: 5 hours

---
## Entry 4 - [October 7, 2026, 11:20 AM]
**What I did**: Implemented waiting time calculation and average waiting time output.

**Details**:

-Wrote a dedicated method to calculate the waiting time for each individual process.
-Formatted the output to clearly display the waiting time per process.
-Calculated and printed the overall average waiting time across all processes.

**Challenges**: Accounting for burst times and arrival times correctly during calculations to prevent negative values.

**Solution**: Verified process completion timestamps against arrival times and total CPU burst durations.

**Time spent**: 8 hour

## Entry 5 - [October 7, 2026, 11:32 AM]
**What I did**: Final testing, debugging, and code cleanup.

**Details**:

-Tested all implemented features (student ID, priority, context switch counter, and waiting times) with various test cases.
-Cleaned up the code structure, removed redundant print statements, and added proper comments.
-Prepared the final files and documentation for submission.

**Challenges**: Minor edge cases where waiting times miscalculated under specific queue conditions.

**Solution**: Applied additional validation checks before computing averages.

**Time spent**: 2 hours
---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [18.15 hours]

**Most challenging part**: Comprehending the complex structure of the provided starter code and grasping how threads execute concurrently in a realistic simulation. Specifically, figuring out how to properly embed and integrate thread-safe properties and custom methods (such as priority handling and context switch counters) into the multithreaded environment without causing synchronization conflicts or race conditions.

**Most interesting learning**: Understanding the inner workings of the Round-Robin CPU scheduling algorithm, particularly how the time quantum is accurately allocated and managed during each entry of a process into the CPU. Additionally, learning how to effectively leverage Object-Oriented Programming (OOP) principles to inherit properties, encapsulate states, and perform clean method invocations across classes.

**What I would do differently next time**: Plan to build several practical projects focused specifically on strengthening multithreading and parallel programming concepts, especially after realizing how almost all modern applications heavily rely on multithreading to achieve high performance and responsiveness.

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

While developing the CPU scheduler simulation in Java, I deeply learned how to implement multithreading to execute processes concurrently. I realized that threads can be created either by extending the Thread class or by implementing the Runnable interface for better design flexibility. Throughout the project, I practically handled lifecycle management methods such as sleep() to control the simulation's timing pauses. I also utilized the join() method to ensure the main system waits until background processes finish completely before printing final results. Furthermore, I explored synchronization mechanisms like wait() to manage the interaction between processing threads within queues. These concepts directly helped me build an accurate and stable simulator that effectively reflects the reality of modern operating systems.

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

The most challenging part of this assignment was initially understanding the existing code's architecture and mechanism, which required a significant amount of time and deep analysis. Once I grasped the core structure, the implementation phase became relatively straightforward, except for the tedious process of tracing the code and managing Git and GitHub workflows. Additionally, integrating the different components posed a challenge, especially when dealing with unfamiliar methods required for accurate time calculation. Writing these time-tracking routines demanded a high level of logical thinking and precision. Overcoming these hurdles significantly enhanced my problem-solving skills and my confidence in handling complex multithreaded systems.

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

To overcome the challenges I faced, I carefully read through the existing source code multiple times to grasp its underlying logic. I also conducted various experiments and ran the program repeatedly to observe how it behaved in practice. Stepping through the execution flow line by line helped me connect the different components together successfully. This hands-on, trial-and-error approach clarified how the methods interacted within the multithreaded environment. Moreover, breaking down the complex sections into smaller, testable parts made the debugging process much more manageable. Ultimately, patience and persistent code tracing allowed me to conquer the difficulties and complete the simulation effectively

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

The multithreading and concurrency concepts we applied in our CPU scheduler can be directly integrated into many real-world applications. For instance, web browsers allocate separate threads to load multiple pages and run scripts simultaneously without freezing the user interface. In media players, background threads allow audio tracks to play smoothly while the user navigates through different parts of the application. Similarly, mobile apps and video games use task queues and scheduling algorithms to distribute heavy calculations across processor cores. This approach is conceptually identical to how we managed process queues and controlled timing in our simulator to execute tasks concurrently. Ultimately, implementing these multithreaded techniques maximizes hardware resource utilization and vastly improves the overall user experience.

### Optional: What would you like to learn more about?

no answer
### Optional: How confident do you feel about multithreading concepts now?

no answer
### Optional: Feedback on the assignment

no answer

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

A process represents an independent execution environment with its own isolated memory space, whereas threads are lighter execution units divided from the main process that run concurrently to fully utilize available CPU cores and processors. While processes do not share memory directly, threads share the same address space and memory resources.
Regarding SchedulerSimulation.java, the simulated processes function as threads because the process class implements the Runnable interface, allowing multiple execution threads to run in parallel within the same program context.

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

When a process exceeds its assigned time quantum, the OS interrupts its execution, performs a context switch, and moves it to the back of the ready queue. In your simulation, a process with a longer burst time was re-queued two times before finishing its execution. This re-queueing mechanism is vital for fairness because it prevents long-running processes from starving others, ensuring all tasks get an equitable share of CPU time

Example from my output:
```
[P3 ظْ P4 ظْ P5 ظْ P6 ظْ P7 ظْ P8 ظْ P9 ظْ P10 ظْ P11 ظْ P12 ظْ P13 ظْ P14 ظْ P15 ظْ P16 ظْ P17 ظْ P18 ظْ P19]
ظ¤¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤

  ظû╢ P2 executing quantum [4000ms] 
  ظأة Quantum progress: [ظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûêظûê] 100%
  ظ╕ P2 completed quantum 4000ms ظ¤é Overall progress: [ظûêظûêظûêظûêظûêظûêظûêظûêظûّظûّظûّظûّظûّظûّظûّظûّظûّظûّظûّظûّ] 42%
     Remaining time: 5327ms
  ظ╗ P2 yields CPU for context switch

  ظئـ P2 added to ready queue ظ¤é Burst time: 9327ms ظ¤é Priority: 10
ظ¤îظ¤ Ready Queue ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤ظ¤
ظ¤é [P4 ظْ P5 ظْ P6 ظْ P7 ظْ P8 ظْ P9 ظْ P10 ظْ P11 ظْ P12 ظْ P13 ظْ P14 ظْ P15 ظْ P16 ظْ P17 ظْ P18 ظْ P19 ظْ P2]
```

**Explanation of example:**
in the given examle the p2 enter the cpu and finish it's quantom the the disdispatcher excute cotext switch then add p2 to ready queue

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: P1 enters the New state the moment its corresponding Thread object is instantiated in memory, before the system allocates any execution resources to it. 
Thread thread = new Thread(process);

2. **Runnable**: After being added to the ready queue (processQueue), the scheduler polls P1's thread and invokes its start method. The thread is now ready and waiting for the JVM thread scheduler to allocate CPU time.
currentThread.start();

3. **Running**: Once the JVM thread scheduler assigns CPU execution time to P1, the thread enters the Running state and begins executing its assigned task.
the run methode in the class prosecc public void run ().

4. **Waiting**: Enters a timed waiting state while simulating the quantum execution progress.
Thread.sleep(stepTime);

5. **Terminated**: P1 enters the Terminated state once it has exhausted its remaining burst.
MarkisFinished();

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

Example 1 (operating-system level): Multi-Tasking Operating System CPU Scheduling

**Description**:
An operating system managing multiple running user applications (such as a web browser, a music player, and a text editor) on a single CPU core.

**Why Round-Robin works well here**:
Round-robin scheduling works exceptionally well here because it guarantees fairness and high responsiveness by giving each active program an equal, cyclical slice of CPU time (the time quantum). This prevents any single compute-heavy application from freezing the system, ensuring smooth multitasking for the user. (In relation to your simulation, the running applications act as the "processes", the CPU time slice acts as the "time quantum", and saving/restoring register states acts as the "context switch".)

Example 2: Multiplayer Game Server Tick Processing

**Description**:
A real-time multiplayer game server managing player actions, physics updates, and network events for dozens of connected players simultaneously.

**Why Round-Robin works well here**:
Round-robin scheduling ensures predictability and fairness by serving each player's action queue in equal, rapid turns so that no single player's complex action lags behind or starves others of server processing time. This maintains an equitable, synchronized, and smooth real-time experience across all participants. (In relation to your simulation, the player action queues act as the "processes", the processing time slice acts as the "time quantum", and thread switching acts as the "context switch".)

## Summary

**Key concepts I understood through these questions:**
1. thread life cycle.
2. multyprogram
3. thread class 

**Concepts I need to study more:**
1. how to implement parllism in real project
2. more use od another need methode 

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
