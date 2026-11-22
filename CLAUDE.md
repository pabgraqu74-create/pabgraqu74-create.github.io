# Empleo Remoto Pablo V5.3
Owner: Pablo Granados. Respond in Spanish; write code and specs in English.

## Scope
Personal, single-user tool that searches for remote job opportunities, generates three daily
Excel reports and emails them only to the owner's own Gmail account, verifying in Sent that each
message exists once and that its attachment matches the generated file (SHA-256).
This repository hosts the public info and privacy pages required for the Google OAuth consent.
Stack: Excel (input/output and independent checks), Python (calculations and automation),
SQL (load to and extract from the database), Power BI (reporting), Tableau (option B).

## Hard rules
- Ask and wait for my explicit yes before ANY system change: installs, downloads, settings,
  security changes, writing outside this folder, deleting files.
- Read-only diagnostics may run after I approve the command.
- Never disable Defender, Controlled Folder Access, SmartScreen, UAC or the firewall.
- Use synthetic or anonymized data unless I approve otherwise in writing.
- Python owns the calculations; Excel reconciles them independently.
- Never claim a test passed without recorded output.
