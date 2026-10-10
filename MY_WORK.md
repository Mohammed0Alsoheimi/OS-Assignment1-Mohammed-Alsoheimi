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
| **Full Name** | Mohammed Abdullah Alsoheimi |
| **Student ID** |  445050126 |
| **University Email** | 445050126@std.psau.edu.sa |
| **GitHub Username** | Mohammed0Alsoheimi |
| **Repository Link** | https://github.com/Mohammed0Alsoheimi?tab=repositories |
 
---

## 🎥 Video Link

**Video Link**: https://drive.google.com/file/d/1hdD1jju62fqZ-0c87qmyJzAH0JJwxJ5Q/view?usp=sharing

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

### Entry 1 - [October 6, 2026, 2:15 PM]
**What I did**:
Forked repository, setup development environment, and set student ID.

**Details**:
- Forked the starter repository on GitHub and cloned it locally to VS Code.
- Updated `studentID` in `SchedulerSimulation.java` to `445050126`.
- Compiled and executed the initial codebase to inspect output structure and trace `Random` generation behavior.
- Pushed initial setup commit to GitHub.

**Challenges**: Environment variable PATH was not pointing to JDK 17, causing `javac` command failure

**Solution**: Configured JAVA_HOME and updated environment variables manually in Windows system settings.

**Time spent**:  1 hour

---

### Entry 2 - [October 6, 2026, 11:30 PM]

**What I did**: Analyzed code workflow and prepared implementation strategy for Feature 1.

**Details**:
- Reviewed the process lifecycle, `Runnable` interface implementation, and queue management.
- Trace how thread synchronization operates via `Thread.join()` in the main scheduling loop.
- Drafted process priority field requirements and checked `Random` assignment logic.

**Challenges**: Understanding how process objects were mapped to thread instances in `processMap`.

**Solution**: Added temporary debug log statements inside `addProcessToQueue` to verify thread-process association.

**Time spent**: 1 hours

---

### Entry 3 - [October 7, 2026, 3:30 PM]
**What I did**:
Implemented Feature 1 (Process Priority) and updated logging.
**Details**:
- Added `priority` attribute to the `Process` class constructor and getters.
- Updated process creation loop inside `main` to assign priority generated via `random.nextInt(10) + 1`.
- Enhanced `addProcessToQueue` method to print process priority alongside burst time.
- 
**Challenges**: Ensuring priority values aligned with random seed output based on Student ID `445050126`.

**Solution**: Validated output logs against the random generation seed to ensure deterministic behavior.

**Time spent**: 1 hour

---

### Entry 4 - [October 7, 2026, 7:30 AM]
**What I did**: Implemented Feature 2 (Global Context Switch Counter).

**Details**:
- Declared `private static int totalContextSwitches = 0;` in `SchedulerSimulation`.
- Incremented `totalContextSwitches` at each scheduling iteration in `while (!processQueue.isEmpty())`.
- Added final context switch summary log formatted with ANSI colors at simulation end.

**Challenges**: Determining whether context switch should count process creation or only queue transitions.

**Solution**: Placed the counter increment right after popping a thread from `processQueue` to accurately capture CPU context switches.

**Time spent**: 1.5 hours

---

### Entry 5 - [October 8, 2026, 12:30 AM]
**What I did**: Implemented Feature 3 (Metrics calculation, summary table, and averages).

**Details**:
- Added `completionTime`, `turnaroundTime`, and `waitingTime` attributes to `Process`.
- Tracked global execution time `currentTime` inside scheduler loop and calculated metrics upon process completion.
- Formatted output table using `System.out.printf` to display all process metrics and computed average turnaround and waiting times.

**Challenges**: Encountered class scope/brace mismatch errors when adding getters/setters in `Process` class.

**Solution**: Re-aligned class closing brackets and structured method placement inside `Process` body before testing.

**Time spent**: 1.5 hours

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

**Total time spent on assignment**: [6 hours]

**Most challenging part**: Correctly tracking global CPU execution time across quantum preemption slices and multi-threaded execution loops.

**Most interesting learning**: Understanding how Java threads simulate OS process context switching and thread states using `Thread.sleep()` and `Thread.join()`.

**What I would do differently next time**: Plan class boundaries and brace structure more carefully prior to implementing new methods to prevent syntax scoping errors.

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

[I now have a thorough understanding of how operating system schedulers control thread execution in a concurrent setting thanks to this assignment. I discovered how Java uses the `Runnable` interface and the `Thread` class primitives to implement multithreading. A thread can be put into execution by using `Thread.start()`, and CPU burst time processing can be efficiently simulated by using `Thread.sleep()`. Additionally, I was able to observe how the main scheduling loop blocks until an active thread finishes its allotted quantum slice by implementing `Thread.join()`. I also noticed that when thread states are switched in memory, context switching adds overhead. All things considered, this practical exercise clarified the lower-level workings of CPU resource allocation and thread synchronization.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[Correctly handling global CPU execution time (currentTime) across preemptive Round-Robin quanta was the most difficult aspect of this job. Tracking exact completion times needed careful reasoning because processes are often halted and re-queued when their burst time exceeds the quantum. It was challenging to coordinate between a process's last execution cycle and regular time-slice preemption. Structural obstacles were also generated by adding additional getters, setters, and attributes to preexisting class hierarchies while avoiding Java syntactic scoping issues. Careful, step-by-step logic checks were necessary to guarantee that metrics calculations were accurate across all preemptive transitions. In the end, coordinating thread execution states with precise timing variables demanded the most debugging effort.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[By using a methodical and gradual debugging strategy throughout development, I was able to overcome these obstacles. I implemented and verified each need step-by-step rather than developing all the features at once. Every scheduling cycle, I tracked queue transitions and global CPU time advancement using comprehensive ANSI-colored terminal logs. I used VS Code highlighting to methodically trace bracket pairings and method boundaries when I came across Java syntax or class scoping problems. I carefully checked process completion times against theoretical Round-Robin execution trace logs to guarantee metric computation accuracy. I was able to identify and fix logical errors thanks to the combination of active console recording and methodical testing.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[In order to provide high speed, non-blocking user experiences, multithreading principles are essential in current software engineering. Web browsers, for example, use separate background threads for rendering, network queries, and JavaScript execution to ensure UI responsiveness. In a similar vein, CPU scheduler-managed thread pools receive inbound HTTP connections from enterprise web servers such as Apache or Netty. In gaming engines, distinct worker threads manage audio processing, graphics rendering, and physics computations concurrently across several CPU cores. Additionally, mobile apps use asynchronous background threads to retrieve API data without causing the main user interface loop to freeze. Developers can create reliable, parallel apps that optimize multi-core hardware consumption by understanding thread scheduling.]

### Optional: What would you like to learn more about?

[I would like to learn more about advanced synchronization primitives like Semaphores, Mutex locks, and lock-free data structures in high-concurrency OS design.]

### Optional: How confident do you feel about multithreading concepts now?

[Confident. I now clearly understand thread lifecycles, execution states, preemptive scheduling, and synchronization using Java primitives.]

### Optional: Feedback on the assignment

[The assignment was very practical and well-structured. Building a visual Round-Robin simulation helped connect theoretical operating system concepts directly with real Java code execution.]

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

[A process is an autonomous running program with its own memory space, whereas a thread is the smallest unit of CPU execution that resides inside a process and shares its resources. SchedulerSimulation.java made use of our custom Process class to simulate operating system processes, but each was executed by a real Java thread created by new Thread(process) in addProcessToQueue(). We decided to use lightweight threads instead of separate operating system processes since they offer far lower creation costs, faster context switching, and seamless memory sharing across shared data structures like processQueue and processMap.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In Round-Robin scheduling, if a process's execution time exceeds the time quantum, it is preempted at the end of its time slice and reinserted into the tail of the ready queue. For example, the initial burst period of process P1 in my simulation run with Student ID 445050126 was longer than the quantum (Quantum = 3000ms, Burst = 5400ms). After completing its first 3000ms quantum, P1 was re-queued into processQueue using addProcessToQueue(). There, it completed its final 2400 milliseconds after waiting for other processes to conclude. Re-queueing is essential for system fairness because it prevents longer processes from robbing shorter processes of CPU time.]

Example from my output:
```
▶ P1 executing quantum [3000ms]
  ⏸ P1 remaining time: 2400ms
  ➕ P1 (Priority: 7) added to ready queue | Burst: 5400ms

```

**Explanation of example:**
"Process P1 had 2400ms of burst time left after running for the entire quantum (3000ms). In order to give other processes equitable CPU access, the scheduler preempted P1 and executed addProcessToQueue(process, processQueue, processMap), appending P1 to the rear of the queue."

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [ P1 enters the **New** state when a new thread instance is created in memory via `Thread thread = new Thread(process)` inside the `addProcessToQueue()` method. ]

2. **Runnable**: [P1 transitions to **Runnable** when `currentThread.start()` is called inside the primary scheduling loop in `main`, making it eligible for CPU scheduling.]

3. **Running**: [P1 enters the **Running** state when the JVM thread scheduler allocates CPU core execution time to it, triggering the execution of its `run()` method logic.]

4. **Waiting**: [P1's thread enters **Timed Waiting** when `Thread.sleep(runTime / 2)` is called inside `run()`, while the `main` scheduler thread enters **Waiting** when calling `currentThread.join()` to await the process thread's completion.]

5. **Terminated**: [P1 transitions to **Terminated** when its `run()` method finishes execution or when its `remainingTime` reaches 0 and the thread exits cleanly.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [CPU Process Scheduler in Desktop OS (e.g., Linux / Windows)]

**Description**:
[Modern desktop operating systems use preemptive Round-Robin scheduling (or multi-level feedback queues with time slicing) to distribute CPU execution time among multiple running user applications like text editors, web browsers, and music players.]

**Why Round-Robin works well here**:
[Round-Robin ensures strict fairness and high system responsiveness; no single background task can freeze the system interface because every application receives guaranteed CPU time slices sequentially.]

### Example 2: [Web Server Request Handling (e.g., Apache HTTP Server or Nginx Thread Pool)]

**Description**:
[Web servers process thousands of incoming HTTP client requests concurrently by distributing worker threads across a scheduled thread pool.]

**Why Round-Robin works well here**:
[Applying Round-Robin time-slicing among thread pool workers ensures predictable response times and prevents long database queries or heavy file downloads from starving smaller API requests.]

## Summary

**Key concepts I understood through these questions:**
1.The memory and overhead differences between OS heavy processes and Java lightweight threads.
2.Thread lifecycle transitions triggered by method calls such as `start()`, `sleep()`, and `join()`.
3.Preemptive Round-Robin scheduling mechanics, context switching, and performance metrics calculation.

**Concepts I need to study more:**
1. Advanced inter-thread synchronization primitives like Semaphores, Mutex locks, and Monitors.
2. Dynamic priority adjustment algorithms in Multilevel Feedback Queue (MLFQ) scheduling.

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
