🧰 Lab: Manage a Support Ticket

Category: Helpdesk Operations / Documentation
Certification Objective: CompTIA A+ Core 2 – 4.1
Repo: Hardware_Ops

🧭 Scenario Overview

At the start of the workday, several helpdesk team members are out sick. With the supervisor in a management meeting, I was tasked with independently monitoring and resolving tickets in the queue, prioritizing urgent issues and maintaining accurate documentation.

🎯 Learning Goals

Apply ticket prioritization and escalation protocols.

Practice clear, standardized documentation for technical and customer-facing notes.

Reinforce time management and triage skills under reduced staffing.

Demonstrate understanding of knowledge base integration and resolution workflow.

🖥️ Environment / Tools

<img width="1275" height="961" alt="Screenshot 2025-10-14 143857" src="https://github.com/user-attachments/assets/a4d04df3-b508-4c79-a964-68caa248f72f" />


The Skillable platform had me use the open-source ticketing system "OSticket." Here it's being used by the fictional company 515Support. 

<img width="1280" height="945" alt="Screenshot 2025-10-14 143913" src="https://github.com/user-attachments/assets/701a6cfa-1c9d-40e8-b882-7e56ed054292" />


Ticket view: Queue filtered by priority (sometimes ticketing systems include filters such as SLA, category, etc.) 


🔍 Tasks Performed

<img width="1224" height="891" alt="Screenshot 2025-10-14 143947" src="https://github.com/user-attachments/assets/3744ff5a-8a53-4800-8e73-ba6ccf1f8a52" />


Reviewed open tickets and identified critical vs. low-priority issues (these tickets all showed a "normal" priority, but this lab in particular had me focus on one that was overdue).

<img width="1269" height="958" alt="Screenshot 2025-10-14 144258" src="https://github.com/user-attachments/assets/300e0cbc-b7e3-4f7e-9261-d7aee9feb444" />

Microsoft AD was the focus for this lab, but I noted how macOS could use MDMs like Mosyle or JAMF to support tickets or a different ticketing system entirely like Zendesk and Snow (Service Now).  

Checked for duplicate reports or recurring system alerts.

Added internal notes detailing troubleshooting actions and observations.

<img width="1273" height="951" alt="Screenshot 2025-10-14 144406" src="https://github.com/user-attachments/assets/09a017be-d8ae-4e84-9ed2-7d3b74fa953b" />


Documented user communication, including resolution or escalation steps.

Closed or escalated tickets per 515Support's company policy.

---

Out of curiosity, I wanted to see if I could resolve some of the other open tickets. I chose a very common one. 

🧩 Ticket Analysis

Subject: Printer Jam – Accounts Payable Department
User: Zuri
Status: Marked Overdue
Description:

“None of us can print to the big copier in Accounts Payable. It says paper jam but we can’t find it. Spencer opened all the trays and found a small paper stuck in the feeder but it still says paper jam.”


<img width="1278" height="965" alt="Screenshot 2025-10-14 144954" src="https://github.com/user-attachments/assets/49b8a518-f040-437b-93f7-5d890f1cf330" />


🧠 Troubleshooting Steps (Simulated / Documentation Focus)

Even if I couldn't access the printer remotely, I still noted the proper escalation workflow and hypothetical diagnostics I’d perform in this scenario (the actual A+ exam did have a PBQ asking me to handle a laser printer error!):

Checked device remotely:

<img width="1243" height="970" alt="Screenshot 2025-10-14 145437" src="https://github.com/user-attachments/assets/ab57bedf-b022-4f6e-8822-eece44d21463" />


I attempted to ping the printer's IP address or access its web management console (e.g., http://printer_IP_address). Spoiler alert: it was not accessible. 

In a real-world scenario, however, I would have done the following: 

Confirmed user actions:

I would reply to the user confirming Spencer’s steps were appropriate (checking trays, feeder).

I would request they power cycle the printer: unplug for 30 seconds, reconnect, and allow full reboot.

Physical inspection (if onsite):

I would first open the rear access panel or duplexer-—common hidden jam area.

Then I'd verify no paper fragments or curled sheets near rollers or fuser.

If still jammed:

I'd escalate to Facilities or Printer Vendor Support if under maintenance contract.

Afterwards, I'd mark the ticket as “Awaiting Vendor Response” and note escalation time.

🧾 Sample Ticket Note

Technician Note (Errol de Jesus):
Verified printer unreachable via remote management; requested user perform power cycle. Instructed to inspect rear duplexer panel for potential jam. Awaiting confirmation. If issue persists, will escalate to vendor for on-site maintenance.

💡 Reflection

Even when a device isn’t directly accessible, I think it's important to demonstrate strong diagnostic reasoning and user communication. A+ tested my knowledge of printer subsystems (feeders, duplexers, fusers).

I also showed that I can logically isolate the issue (mechanical jam vs. firmware vs. queue error). Finally, I demonstrated my ability to communicate clearly and keep the ticket moving forward, even under partial information.

💡 Reflection

This lab emphasized how documentation is as critical as technical skill. Clear ticket histories ensure seamless handoffs, accountability, and faster future resolutions.

Key takeaways:

Write for the next technician, not just yourself.

Use consistent formatting (issue → diagnosis → resolution).

Escalate early when priority is high and try to resolve overdue tickets as swiftly as possible. 
