# Backup
Takes backup of files from any given valid path

Bash script

	1. That takes any path as input - checks validity of path
		1.1 if valid, take backup in a backup folder - (default backup directory)
		1.2 if not, show error message
	2. Each backup should have the backup timestamp as the directory filename
	3. Take backup -
		3.1 Only if the baackup doesn't already exist.
		3.2 If backup already exist, take backup if files are modified after last backup.
	4. Compression techniques are used for backup.
	
