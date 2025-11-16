# Boot Record Infector

## Definition

A boot record infector is a type of malicious software (malware) that targets the boot sector of a storage device, such as a hard drive, floppy disk, or USB stick. By embedding itself in the boot record, this malware ensures it is executed before the operating system loads, giving it control over the system at the earliest possible stage.

## How It Works

When a computer is powered on, the system BIOS or UEFI firmware looks for a boot record to load the operating system. A boot record infector replaces or modifies this record with its own code. As a result, the malware is loaded into memory and can execute its payload—such as installing other malware, hiding itself, or compromising system files—before any security software is active.

## Real-World Application

Boot record infectors were especially prevalent in the era of floppy disks, spreading rapidly between computers. Famous examples include the "Michelangelo" and "Stoned" viruses. Today, similar techniques are used in rootkits and advanced persistent threats (APTs) to evade detection and maintain persistence. Modern operating systems and hardware use secure boot mechanisms to defend against such attacks.

Imagine a spy sneaking into a building before the security guards arrive, setting traps and disabling alarms before anyone else is awake.

## Entertaining Example

Picture a magician who rewrites the script for a play before the actors arrive, ensuring the show goes exactly as they want—no matter what the director intended.

## Why It Matters

Boot record infectors highlight the importance of securing the earliest stages of system startup. They remind us that security must begin before the operating system even loads.

---
Contact: Cosmos Knowledge Base — SolveForce  
Email: contact@solveforce.com  
For corrections or suggestions, please open an issue in the repository.
---
