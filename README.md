# Notes

### Entry Template


__command__ - _Description_

__Examples:__

```
bash code in here
```
---

## File Management

__mv__ - _Move file or Rename file_

__Examples:__

```
mv sourceFile destinationFile
mv sourceFile destinationLocation
mv myFile.txt myFolder/
```
---

__cp__ - _Copy file or folder_

__Examples:__

```
cp filename.cpp myCopy.cpp
cp -r myFolder/ myNewFolder
```
---

__rm__ - _Remove file or directory_

__Examples:__

```
rm file1 file2
rm -r dir1 dir2
```
---

__rmdir__ - _Remove an empty directory_

__Examples:__

```
rmdir /cs210/stuff
```

__ln -s__ - _Soft link that refers to another file by its path_

__Examples:__

```
ln -s myfile mysoftlink
```

__scp__ - _Secure copy copies files and directories from one computer to another in batch_

__Examples:__

```
scp myfile remote.example.com:newfile
scp -r mydir remote.example.com:
```

__pwd__ - _Prints the absolute path of current working directory_

__Examples:__

```
pwd
```

__ls__ - _Lists attributes of files and directories_

__Examples:__

```
ls
ls dir1 dir2
ls file1 file2
ls -a
ls -l
ls *txt
```

__tar__ -_Packs multiple files and directories into single file for transport_

__Examples:__

```
tar -czvf myarchive.tar.gz mydir
tar -tzvf myarchive.tar.gz
tar -xzvf myarchive.tar.gz
tar -cf /dev/tape file1 file2
```

__curl__ - _Writes to standard output by default and duplicates the original page and file names by default_

__Examples:__

```
curl http://www.google.com > mypage.html
```

__wget__ - _Hits an URL and download the data to a file or standard output_

__Examples:__

```
wget http://www.google.com
```

__rsync__ - _Copies a set of files_

__Examples:__

```
rsync -a D1 D2
```

__cat__ - _Prints its files to standard output, concatenating them_

__Examples:__

```
cat filename.txt
cat * | wc
```

__sort__ - _Prints lines of text in alphabetical order or some other specified rule

__Examples:__

```
sort filename
```

__uniq__ -_operates on consecutive, duplicate lines of text_

__Examples:__

```
uniq filename
sort filename | uniq
```

__grep__ -_With one or more files, it prints all lines in those files that match a particular regular expression pattern_

__Examples:__

```
grep '\!$ filename
grep txt filename
```

* cp (folder and individual files)
* rm (file and directories)
* rmdir
* ln -s
* scp
* pwd
* ls (hidden files and files starting or ending with specific patterns like all files ending in txt or all files starting with the letter b)
* tar

## File Transfer

* curl
* wget
* scp
* rsync

## Pipe tools

* cat
* sort
* uniq
* grep
