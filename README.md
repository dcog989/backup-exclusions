# Backup Exclusions
A list of folders and files to be excluded from a backup strategy. 

These files are designed as a starting template for use with Windows 11 and [Kopia](https://github.com/kopia/kopia/) but can be adapted for other backup solutions.

Make sure you understand what the patterns mean before implementing, e.g.:

~~~
  **/*cache*
  **/*Cache*
  **/*temp*
  **/*Temp*
~~~
