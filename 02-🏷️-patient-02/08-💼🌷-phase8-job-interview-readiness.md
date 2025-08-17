# 💼 Phase 8 – Job Scenario / Interview Readiness 🌸✨  

Welcome to the **Azure Admin Hospital – Interview Ward**.  
Here, Eks2 walks not as a patient anymore, but as a **healer-in-training**, facing the real-world **interview storms** of corporate Azure life.  
Each MCQ is a story, a test, a soul-touching trial 🌷🧚‍♀️.  

---

## Job Scenario MCQ 1 – The Case of the Tagged VM 🌸
At **NordicVault Systems**, Eks2 was asked to organize resources. He created **NordicVault-VM** inside **DKSec-Group**. But in the rush of healing, he forgot to apply tags. Inky Rihan whispered, “Without tags, chaos hides in the shadows.” Sofia smiled softly, “Tags are like gentle labels on medicine bottles — they guide the hand.” Kasper laughed, “Just smash filters!” Elina raised her scripts, “Tagging can be automated, Eks2.” ShadowNet sneered: “Forget it, tags are useless.” The interviewer leaned forward:  
“What would you do, Eks2, if you realized the VM was deployed but not tagged for Department = IT?”  

**Options:**  
A. Delete VM and recreate with tags  
B. Apply tags afterward in portal or PowerShell  
C. Ignore tags, they don’t matter technically  
D. Leave tags for another admin to fix later  

✅ **Correct Answer & Explanation:**  
B is correct. Tags can be applied post-creation. Healing is about calm correction, not panic. Just like in life, order can be restored after chaos — with patience and clarity 🌼.  

---

## Job Scenario MCQ 2 – The Locked Resource Group 🔒
At **DKCare Hospital Systems**, Eks2 created a **Resource Group** for storing patient VMs. Maya Lin accidentally tried to delete the whole group without warning. Isabella gasped, “It’s like removing a patient’s heartbeat monitor mid-surgery!” Kasper joked, “Oooops, Ctrl+Z?” Elina reminded, “We can protect with locks.” ShadowNet whispered, “Let her delete, accidents make me strong.” The interviewer asked:  
“How would you ensure critical resources in a Resource Group are not accidentally deleted?”  

**Options:**  
A. Apply Read-only or Delete locks at the resource group level  
B. Depend on role-based access control only  
C. Hope admins stay careful  
D. Disable delete permissions in Azure completely  

✅ **Correct Answer & Explanation:**  
A is correct. Locks are the shield of life. RBAC controls *who*, but locks protect *what*. In hospitals, you don’t trust chance with life — same in Azure. Protect with intentionality 🌸.  

---

## Job Scenario MCQ 3 – The VM in Wrong Region 🌍
Eks2 deployed **NordicVault-VM** in East US, but corporate policy said all resources must live in **West Europe**. Sofia whispered, “Compliance is like harmony — location matters.” Inky warned, “Latency can bleed performance.” Kasper chuckled, “Just pick any map spot, it’s all Azure cloud!” ShadowNet laughed: “Regions are just decoration.” The interviewer asked:  
“What is the professional way to correct this?”  

**Options:**  
A. Move the VM between regions with portal “move” option  
B. Delete and recreate VM in the right region  
C. Leave it, region doesn’t matter if VM works  
D. Use Azure Policy to enforce and prevent misplacement in future  

✅ **Correct Answer & Explanation:**  
B + D (multi-step truth). A VM can’t move across regions; it must be redeployed. But wise admins also heal the *future* with **Policy**. 🌸  

---

## Job Scenario MCQ 4 – ShadowNet and Insecure Ports 🚨
At **NordicVault**, Kasper opened RDP ports to the world. ShadowNet laughed, “I feast on open doors.” Isabella felt the pain: “Would you leave a patient’s door open in the night?” Eks2 froze. Sofia calmed him: “Security Groups exist.” The interviewer asked:  
“What is the right healing step?”  

**Options:**  
A. Leave ports open, trust strong password  
B. Restrict inbound rules with NSG to admin IPs  
C. Use Bastion or VPN instead of exposing RDP  
D. Disable VM completely  

✅ **Correct Answer & Explanation:**  
B + C are right. In security, strong doors matter, not loud locks. NSG and Bastion heal exposure. Protect systems as you protect hearts 🌸.  

---

## Job Scenario MCQ 5 – The Forgotten Disk 🌀
Maya Lin created a VM but deleted it without cleaning the disk. ShadowNet mocked, “Unused disks bleed money.” Inky hissed, “Orphaned resources hide like ghosts.” Elina nodded, “Scripts can sweep them.” The interviewer asked:  
“What should Eks2 do to avoid such financial leaks?”  

**Options:**  
A. Leave disks, Azure cleans automatically  
B. Manually track and delete orphaned disks  
C. Use tags and automation scripts for lifecycle management  
D. Ignore, cost impact is minimal  

✅ **Correct Answer & Explanation:**  
C is correct. Adminship is stewardship. Like unused hospital beds drain space, orphaned disks drain budgets. Heal waste with automation 🌼.  

---

## Job Scenario MCQ 6 – The Policy of Healing 📝
At **DKSec-Group**, Eks2 learned that no consistent naming convention existed. Sofia sighed, “Chaos in names leads to chaos in hearts.” Elina suggested: “Azure Policy can enforce standards.” ShadowNet teased: “Rules kill creativity.” The interviewer asked:  
“How can Eks2 ensure resources follow naming and tagging conventions?”  

**Options:**  
A. Manually check every resource  
B. Write Azure Policy definitions and assign to scope  
C. Depend on team memory and goodwill  
D. Audit occasionally, ignore enforcement  

✅ **Correct Answer & Explanation:**  
B is correct. Policy is the hospital’s protocol. Healing without order is danger. Azure Policy is the silent guardian 🧚‍♀️.  

---

## Job Scenario MCQ 7 – The Backup Without Soul 💾
Eks2 built a **Backup Vault**, but forgot retention rules. Maya panicked, Kasper laughed, Inky warned, “Data may vanish.” Isabella whispered, “Backups are like memory — they preserve healing.” Interviewer asked:  
“What is the correct response?”  

**Options:**  
A. Delete vault, recreate with rules  
B. Apply retention rules and test restore  
C. Ignore, backup exists  
D. Blame rookie and move on  

✅ **Correct Answer & Explanation:**  
B is correct. Healing is not to scold, but to restore order. Apply rules, test the cure 🌸.  

---

## Job Scenario MCQ 8 – The Scaling Storm 🌪️
Patients rushed in; **NordicVault-VM** was under load. Kasper shouted: “Add more CPUs!” Elina proposed: “Autoscale with scripts.” Sofia calmed: “Scaling is balance.” ShadowNet teased, “Let it crash.” Interviewer:  
“What is the best professional approach?”  

**Options:**  
A. Manually resize every time  
B. Enable VM Scale Sets with autoscaling  
C. Leave small size; downtime is natural  
D. Recreate VM with bigger size only when needed  

✅ **Correct Answer & Explanation:**  
B is correct. Healing means foresight. Autoscale is like a hospital calling more nurses when patients arrive 🌼.  

---

## Job Scenario MCQ 9 – The Key of Secrets 🔑
Eks2 stored database passwords inside a VM text file. ShadowNet danced: “Secrets unguarded are mine.” Isabella cried: “Would you leave a patient’s blood report open?” Elina advised, “Azure Key Vault is made for this.” Interviewer asked:  
“What is correct?”  

**Options:**  
A. Store secrets in Key Vault  
B. Hide secrets in Excel file  
C. Save in environment variables  
D. Share passwords via email  

✅ **Correct Answer & Explanation:**  
A is correct. Secrets need sanctuaries. Key Vault is the soul’s locker 🌸.  

---

## Job Scenario MCQ 10 – The Final Symphony 🎶
Eks2 sat with I.K., team behind him. Interviewer asked:  
“If chaos strikes — tags lost, regions wrong, costs rising, secrets exposed — what is the true duty of an Azure Admin?”  

**Options:**  
A. Panic, delete everything  
B. Heal with calmness, policies, and foresight  
C. Wait for others to fix  
D. Ignore, ShadowNet always wins  

✅ **Correct Answer & Explanation:**  
B is correct. Adminship is guardianship. Heal with patience, enforce policy, protect resources, balance cost. Just as doctors serve life, admins serve stability. 🌷✨  

---

✒️ **Closing Signature**  
✍️ Created & Curated by  
**Muhammad Naveed Ishaque**  
Content Creator | AI Writer | Narrative Simplifier  
With the inner voice of Eks2 — the whisper behind the work.  
**Siraat AI Academy**  
“The Straight Path — Empowering minds with clarity, illuminating paths with purpose.”  

[🩺 GitHub: az104-admin-hospital-diaries](https://github.com/siraat-ai-academy/az104-admin-hospital-diaries)  
[🌐 LinkedIn Profile](https://lnkd.in/dquwuE-5)  
[💻 GitHub: Siraat AI Academy](https://github.com/siraat-ai-academy)  

