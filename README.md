# CxDataRetention

This was developed in Product Backlog Item 41903 Data Retention: Cx retention - Delete scans by Last X scans OR Date range from CLI

Might need to change your execution policy (Set-ExecutionPolicy Unrestricted) or use the "Bypass" Execution Policy Flag

This is a nice flag added by Microsoft that will bypass the execution policy when you're executing scripts from a file. When this flag is used Microsoft states that "Nothing is blocked and there are no warnings or prompts". This technique does not result in a configuration change or require writing to disk.

PowerShell.exe -ExecutionPolicy Bypass -File .runme.ps1

Other methods can be found in - https://blog.netspi.com/15-ways-to-bypass-the-powershell-execution-policy./

