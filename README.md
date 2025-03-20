# Task-Scheduling-and-PowerShell-Scripting-SVAN-Part-4

**Overview**

This project builds on the previously configured savn.local domain network by introducing task automation and PowerShell scripting. The objective is to configure and schedule automated tasks within the savn.local domain, focusing on remote task execution and PowerShell scripting.

**Objectives**

Create and schedule a remote task that launches Notepad on EPS-SP24-S22-2 when domainUser01 logs in.  
Task Name: StartNotePad  
Create and schedule a PowerShell script to display a welcome message and timestamp when any user logs into EPS-SP24-S22-1.  
Script Name: get-datemessage.ps1  
Task Name: displayDateMessage

**Key Components**

Domain Controller: EPS-SP24-S22-1 (Windows Server 2022)  
Member Server: EPS-SP24-S22-2 (Windows Server 2022)  
Client Machine: EPS-SP24-W10-1 (Windows 10 Education)  

**Files**

Task Scheduling & Powershell Scripting Documentation
