# TheHiveInternProject
Python Hive Mail changes documentation

creating case--
looks for template name definition defined in config
i;e testTemplate-"Critical Incident",testTemplate2-"Strange Incident"
if critical incident in subject field, use testtemplate
also searches body for albert id as custom field
creates case automatically based off any email unless update in subjectfield

updating case--
if "Update" in subjectfield
---Updated Information
Case ID: 91
Resolved: No
Resolution Status: Yes
Impact Status: No
Summary: Being Gay
Tags: test,test2,greenbag
Title: RyanMearsSucks
TLP: 1
Description: Snoopy
Albert ID: 666
Severity: 2
ReplaceTags: No
---
ReplaceTags can be yes or no, if yes, replaces all tags with specified, if no, adds the unique ones from list and appends them.
