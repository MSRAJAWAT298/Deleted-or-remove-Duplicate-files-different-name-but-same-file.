# Deleted-or-remove-Duplicate-files-different-name-but-same-file.
<ul>
    <li> ✅ The code starts by declaring a function called removeDuplicateFiles.</li>
    <li> ✅ This function takes in three parameters: $dirName, $distinationDirPath, and $recursiveCheck.</li>
    <li> ✅ The first two are required while the third is optional.</li>
    <li> ✅ The first parameter is an array that contains the names of all files in a directory or folders within a directory to be deleted.</li>
    <li> ✅ If this parameter is empty then it will delete all the file else it move duplicate file at your destination path If recursiveCheck is true then it will check inside folder file also else it will only check current dir. and skip child or inner dir. The second parameter defines where to save any duplicates found during the search for duplicates (if there are any).</li>
    <li> ✅ It can either be set to '', which means no destination, or specify another string value like '/path/to/destination'.</li>
    <li> ✅ The code will delete all the files in a directory if it is empty.</li>
    <li> ✅ If the $distinationDirPath parameter is not empty, then it will move duplicate files to the specified destination path.</li>
    <li> ✅ The code is trying to find all the files in a directory that have an excluding extension of .mp4 or .MOV.</li>
    <li> ✅ If it finds any (mp4 or mov files), it skips them and continues on with the rest of the code.</li>
    <li> ✅ The first line sets max_execution_time to 0 which means there is no limit on how long this script can run for.</li>
    <li> ✅ The next two lines create variables called $checksums and $moveFileNames which will be used later in the script.</li>
    <li> ✅ The third line creates a variable called $distination_path that will hold where we are moving our file to after we process it.</li>
    <li> ✅ The code is a loop that iterates through each of the files in the directory.</li>
    <li> ✅ The first line checks if the file extension matches any of the skipFilesExtenion array.</li>
    <li> ✅ If it does, then it continues to iterate through all of the remaining files.</li>
    <li> ✅ The code starts by checking if the destination directory exists.</li>
    <li> ✅ If it does not exist, then a new directory is created and given permissions of 777.</li>
    <li> ✅ The code then checks to see if the source file is a duplicate in directory or not.</li>
    <li> ✅ If it is duplicate, then all files in that directory are the destination folder using removeDuplicateFiles().</li>
    <li> ✅ The hash for each file in the source folder is checked against an array of hashes that was previously generated with sha1_file().</li>
    <li> ✅ If there are any duplicates, they will be deleted from the destination folder before renaming them to their new name.</li>
    <li> ✅ The next section checks whether or not this process should be run recursively on sub-directories within this path as well.</li>
    <li> ✅ This can be done by setting $recursiveCheck to true at line 3 above.</li>
    <li> ✅ The code checks if the destination directory exists and if it does not, creates a new one.</li>
    <li> ✅ If the destination directory already exists, then it will check to see if any files in that directory are duplicates of files in the source directory.</li>
    <li> ✅ If so, those duplicate files will be deleted from the Source directory.</li>
 </ul>
