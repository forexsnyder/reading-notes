Jeff Snyder

26OCT2020

BREAKING THE KILL CHAIN: A DEFENSIVE APPROACH

Seven parts of the kill chain:
1.	Reconnaissance
2.	Weaponization
3.	Delivery
4.	Exploitation
5.	Installation
6.	Command and Control
7.	Actions on Objectives

Reconnaissance

The two different stages of reconnaissance are passive and active.
Defending against passive reconnaissance means limiting the level of detail we expose publicly.
The entire goal of the reconnaissance phase is to find a weakness that can be exploited.

Weaponization

Some examples of commonly used weapons during this phase include:
Metasploit or exploit-db for publicly available exploits
The Veil framework is commonly used to generate evasion code for malware
Social Engineering Toolkit, if they’ve decided they will deliver the malware through a Social Engineering campaign.

How they deliver the attacker is as critical as what they choose for a weapon.

Delivery

Now, the delivery stage is where they try one or multiple avenues to deliver the weapon. The delivery of the attack varies by the type of attack.

DKIM and SPF are email authentication method to detect spoofed emails. SPF makes sure that emails are coming from the authorized IP of the domain while DKIM uses digital signatures. Both techniques help to make sure emails are coming from legitimate, authorized channels.

Exploitation

The actual exploit could come in the form of a buffer overflow, a SQL injection, malware that was undetected by our AV solution, an client side exploit that was executed on an older version of javascript, or many others.

The reality is when an attacker gets to this point you’re relying on post-infection tools like a sandbox, EDR or a SIEM to find indicators of compromise (IoC).

Installation

Some common payloads and techniques during this stage involve:
DLL hijacking
Injecting Meterpreter or other similar payloads
Installing Remote Access Tools (or RAT)
Registry changes to make my program automatically start up
Executing Powershell in fileless attacks

Fortunately, we have some post infection tools we could use at this stage that can monitor system files and registry for unusual changes and behavior. A good EDR solution should flag any new unauthorized program that was installed, as well as detect any changes to registry and system process.

Once a system is determined to be infected, you can then begin the process of restoring the system to a known good state.

Command and Control

The infect device could be used immediately for carry out the mission, or it could sit back and wait for further instructions from it’s command and control server

Limiting the damage of a breach starts with segmentation. Segmentation will make it harder for the attacker to move laterally, and easier to detect using audit logs. 

Actions on Objective

The action is predicated by the motivation of the attacker, so understanding the type of attacker that could be targeting your organization is crucial.

Dwell time is the length of time an attacker is active inside the network before being detected. For CISOs or Security Directors, this is a critical metric to follow. According to a report by Ponemom Institute and IBM, the average dwell time is 191 days.

from “https://thecisoperspective.com/index.php/2020/03/27/breaking-the-kill-chain-a-defensive-approach/”
