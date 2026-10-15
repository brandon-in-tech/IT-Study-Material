IT Study Materials
Interactive IT study guides, certification masterclasses, hands-on labs, quizzes, and technical references.

Created and maintained by Brandon Stevenson as an independently developed learning collection for IT support, systems administration, networking, cloud infrastructure, endpoint management, and cybersecurity.
Launch Study Library → · View Repository · [Filename Mapping](./RENAMED-FILES.md)

About the collection

The dashboard organizes browser-based educational resources into six study categories. Select a category, browse the available material, or search by technology, certification, or skill. Individual guides can contain expandable lessons, flashcards, quizzes, troubleshooting exercises, commands, and hands-on labs, depending on the course.
Most learning pages run directly in a browser without installing software or signing in. Practical labs that involve operating systems, virtual machines, network hardware, or cloud services may require separate tools or accounts.

Study catalog

The Open guide links below use the intended GitHub Pages paths. A link will work once the corresponding HTML file has been committed to the published repository and deployment has completed. The Source links open the files in the repository.

IT Administration & Systems

Resource	What you'll study	Links

CompTIA A+ Core 1 (220-1201)	Mobile devices, networking, hardware, virtualization/cloud, hardware and network troubleshooting; interactive lessons, flashcards, questions, and labs.	[Open guide](./it-administration/A+-core-1.html) · [Source](./it-administration/A+-core-1.html)
CompTIA A+ Core 2 (220-1202)	Operating systems, security, software troubleshooting, operational procedures; interactive lessons, flashcards, questions, and labs.	[Open guide](./it-administration/A+-core-2.html) · [Source](./it-administration/A+-core-2.html)
System Administration Master Roadmap	Windows Server, Active Directory, Linux, networking, virtualization, Azure, PowerShell, and infrastructure security.	[Open guide](./it-administration/SysAdmin_Roadmap.html) · [Source](./it-administration/SysAdmin_Roadmap.html)
Linux+ Study Guide & Flashcards	Linux administration, command-line work, shell scripting, networking, storage, security, and troubleshooting.	[Open guide](./it-administration/linux+-study.html) · [Source](./it-administration/linux+-study.html)
IT Administration Glossary & Flashcards	Terminology spanning servers, storage, identity, endpoints, networking, cloud, and IT operations.	[Open guide](./it-administration/it-administration-glossary-and-flashcards.html) · [Source](./it-administration/it-administration-glossary-and-flashcards.html)


Networking & CCNA
Resource	What you'll study	Links
CompTIA Network+ (N10-009) Masterclass	Networking concepts, implementation, operations, network security, troubleshooting, flashcards, questions, and labs.	[Open guide](./networking/net+-study.html) · [Source](./networking/net+-study.html)
CCNA Master Class — Course, Labs & Practice Exams	Routing, switching, subnetting, network fundamentals, configuration labs, flashcards, and exam preparation.	[Open guide](./networking/ccna-master-class-and-exam.html) · [Source](./networking/ccna-master-class-and-exam.html)
Cisco IOS Commands & Theory Reference	Cisco CLI commands, configuration examples, protocols, verification, hardening, and operations concepts.	[Open guide](./networking/ccna-cisco-ios-commands-and-theory-reference.html) · [Source](./networking/ccna-cisco-ios-commands-and-theory-reference.html)
CCNA Troubleshooting Scenarios	Interactive foundational quizzes, guided troubleshooting, real-world networking tickets, and troubleshooting workflows.	[Open guide](./networking/CCNA_Troubleshooting_Scenarios.html) · [Source](./networking/CCNA_Troubleshooting_Scenarios.html)


Azure & Cloud
Resource	What you'll study	Links
AZ-900 Azure Fundamentals Study Guide	Cloud concepts, Azure services, pricing, governance, identity, and exam preparation.	[Open guide](./azure/az-900-azure-fundamentals-study-guide.html) · [Source](./azure/az-900-azure-fundamentals-study-guide.html)
AZ-900 Azure Fundamentals Flashcards	Quick-recall practice covering cloud fundamentals, Azure services, governance, and cost concepts.	[Open guide](./azure/az-900-azure-fundamentals-flashcards.html) · [Source](./azure/az-900-azure-fundamentals-flashcards.html)


Cybersecurity & Network Security
Resource	What you'll study	Links
CompTIA Security+ Interactive Study	Security concepts, threats, architecture, operations, security controls, and governance.	[Open guide](./networking/security+-interactive-study.html) · [Source](./networking/security+-interactive-study.html)
Palo Alto NGFW / PAN-OS Study Guide & Labs	Security policies, NAT, App-ID, User-ID, VPNs, high availability, Panorama, and firewall administration exercises.	[Open guide](./network-security/palo-alto-ngfw-pan-os-study-guide-and-labs.html) · [Source](./network-security/palo-alto-ngfw-pan-os-study-guide-and-labs.html)


Endpoint Management
Resource	What you'll study	Links
Microsoft MD-102 Endpoint Administrator Field Guide	Microsoft Intune, Windows deployment, Windows Autopilot, Entra ID, compliance, protection, updates, and app management.	[Open guide](./endpoint-management/md-102-endpoint-administrator-field-guide.html) · [Source](./endpoint-management/md-102-endpoint-administrator-field-guide.html)


Systems & Cloud Architecture
Resource	What you'll study	Links
IT Systems Design & Architecture Masterclass	Architecture decisions, capacity planning, scalability, high availability, resilience, distributed systems, and design exercises.	[Open guide](./it-administration/sys-design.html) · [Source](./it-administration/sys-design.html)
Azure Cloud Systems Design	Cloud architecture patterns, reliability, security, availability, cost, and guided design exercises.	[Open guide](./cloud-architecture/azure-cloud-systems-design-study-guide.html) · [Source](./cloud-architecture/azure-cloud-systems-design-study-guide.html)


Recommended study paths
Starting in IT: CompTIA A+ Core 1 → A+ Core 2 → IT Administration Glossary → System Administration Roadmap.

Networking: CompTIA Network+ → CCNA Master Class → Cisco IOS Commands & Theory → CCNA Troubleshooting Scenarios.

Systems administration: System Administration Roadmap → Linux+ → MD-102 → IT Systems Design & Architecture.

Cloud infrastructure: AZ-900 Study Guide → AZ-900 Flashcards → Azure Cloud Systems Design → IT Systems Design & Architecture.

Security: Security+ Interactive Study → Palo Alto NGFW / PAN-OS Labs → relevant networking and systems hardening material.
Run locally

1. Clone or download this repository.
2. Open index.html in a web browser.
3. Choose a study category and open any course.
4. 
You may also open individual HTML guides directly. Some pages use browser storage for progress and preferences; others keep quiz results only for the active session. Local progress is not synchronized between devices. External links, fonts, and practical cloud labs can require an internet connection.

Add a new study guide
1. Save the standalone .html file in the relevant topic directory (such as networking/ or it-administration/).
2. Add an entry to the const resources = [ array in the root index.html, using the exact filename and capitalization in its href.
3. If the filename changed, update [`RENAMED-FILES.md`](./RENAMED-FILES.md).
4. Add the resource to this README catalog.
5. Commit your changes and wait for GitHub Pages to deploy.
6. 
Filename accuracy matters. GitHub Pages links are case-sensitive. Keep special characters such as + exactly as they appear in the file name. If a link shows 404, confirm that the file exists in the publishing branch and folder and that the latest deployment succeeded.
GitHub Pages

To publish from a branch, go to Repository Settings → Pages, choose Deploy from a branch, and select the repository's configured publishing branch and root folder. Your index.html should be at that root. Check the Actions tab for deployment status.

Official GitHub Pages setup documentation
Important notes
- Materials are independent educational resources, not official CompTIA, Cisco, Microsoft, or Palo Alto training products.
- Exam objectives and vendor interfaces change. Verify exam versions, objectives, and operational procedures against the relevant vendor documentation.
- Guided scenarios and illustrative configurations are not live network emulators. Test commands only in equipment or environments you're authorized to use.
- This catalog reflects the intended course filenames discussed for the study dashboard; it does not certify that every file has already been uploaded or that every hosted link is live.

- 
Created by Brandon Stevenson · Independent IT learning resources · Study Dashboard
