# Files 

Files, which are also referred to as the integrated *Course File System (CFS)*, are a means of storing &mdash; and organizing into collections (folders) &mdash; blobs of data (files).

<img src="./files/teachers_files-page.png" style="text-align: center;display: block;min-width: 75%;width: 75%;margin: 0 auto;" />

## Files

Files can be uploaded and stored within a course on Platform. To add a file, click "Add File" and drag-and-drop it onto the box that appears; or click the upward arrow and select it in the upload window that appears.

CFS implements some limits on the files that can be added and stored on Platform:
   * The maximum size of a file is 1MB (or 1,048,576 bytes)
   * The file's entire path (represented as all the folders, with slashes &mdash; / &mdash; in between them) cannot exceed 64,000 characters (though, PLEASE do not go this high).
   * The following characters cannot appear in filenames: ~, #, %, ", *, :, <, >, ?, /, \, |, &, {, [, ], }, (, ), _, (a space), (a newline), (a tab), `, $, ^, +, ', ;, (a comma: ,).
   * Files with the following extensions (and matching MIME-types) are prohibited: lock, ini, apk, bat, cmd, cab, com, dll, dmg, exe, iso, js, php, jcp, pl, py, lib, vb, asp, bas, hta

## Folders

Folders are collections of files. Any folder can have an unlimited number of files and folders (but, remember no path can exceed 64,000 characters).

**NOTE**: There is a small known-issue regarding folders: A root-level folder (that is, a folder that is not in a folder) cannot contain a sub-folder (a folder within this root-level folder) that has the same name. *For example, folder "old" cannot contain folder "old".* Well, it can; but if you try to do certain things (like rename it) it will effect both. [View on Bug-Tracker](https://platformlms.org/support/bugs/view?id=1054106)

## File/Folder Altercations 

The following actions can be preformed against files/folders: 
   * **Download**: The file contents will be retrieved and downloaded onto your computer hard disk. (*File only*)
   * **Rename**: This changes the *internal* representation of the filename in CFS. When you download a file, it will still use the name it was uploaded with. (*File/Folder*)
   * **Move**: Move a file in CFS. *Does not effect the file stored on your computer*. (*File/Folder*)
   * **Hide**: Hides a file from students (not you). (*File only*)
   * **Delete**: Deletes a file or all the files/folders in a folder. (*File/Folder*)
   * **Open**: Double-clicking on a file will make Platform attempt to open it. This will *not* download the file, though you may be asked to if we cannot open it. (*File only*)
	   * Platform can open the following types of files: .mp4, .webm (dependent on browser), .ogg (dependent on browser), .docx, .pdf

---

Files and Folders on Platform can be powerful features, if used right. With this guide, we hope to help guide you into doing that. Good luck! Want to explore another powerful feature? [Pages](#/04-using_platform/03-courses/07-pages.md).