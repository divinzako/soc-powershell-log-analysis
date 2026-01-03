# SOC L1 – Detecting Suspicious PowerShell Activity

## Project Overview
This project demonstrates basic SOC L1 skills by analyzing Windows Event Logs to detect suspicious PowerShell activity and process creation events. It covers log analysis techniques, identifying potential threats, and documenting findings in a structured way.

## Objectives
- Analyze Windows PowerShell logs (Event ID 4103 and 4104)
- Analyze Windows Security logs for process creation (Event ID 4688)
- Identify and document suspicious activities
- Showcase SOC L1 analytical skills for portfolio purposes

## Repository Structure
- `logs/` → contains `.evtx` files
  - `powershell-operational.evtx` (Event IDs 4103 + 4104)
  - `security-4688.evtx` (Event ID 4688)
- `analysis/` → Markdown files to explain your findings
  - `event-4104-analysis.md`
  - `event-4103-analysis.md`
  - `event-4688-analysis.md`
- `screenshots/` → screenshots of events for reference

### Folders Description
- **logs/** : contains exported `.evtx` files from Windows Event Viewer  
- **analysis/** : contains Markdown files with analysis of specific events  
- **screenshots/** : contains screenshots of events for visualization and reference  

## Skills Demonstrated
- Log analysis for Windows PowerShell and Security events  
- Understanding of SOC L1 monitoring processes  
- Ability to detect suspicious commands or process creation  
- Structured documentation for security investigations  

## How to Use This Repository
1. Open the `.evtx` files using Windows Event Viewer.  
2. Examine the events (4103, 4104, 4688) for suspicious activity.  
3. Review the Markdown analysis files for examples of investigation and reasoning.  
4. Screenshots provide visual context for each type of event.  

## Notes
- Only safe, lab-generated events are included.  
- No personal or sensitive data is used.  
- This project is intended for portfolio demonstration purposes only.  

