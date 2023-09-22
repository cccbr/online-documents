---
title: Publication
weight: 50
---

# Publishing a Document

The eventual aim for all CCCBR online documents is that the code will be held in a GitHub repository and published from there. The details of this will be described [below](#publishing-from-github). In developing an online document, however, you may find it convenient to work on your own device, generating the output on a local server. This is not essential but we have found it very  useful and we will describe it first. The workflow involved in producing an online document is discussed in more detail [here](../060-workflow).

{{< hint info >}}
Publishing documents can involve a level of computer experience which may be a deterrent to some otherwise quite competent authors. For that reason, we just give a brief description of these parts of the process, assuming that an author will be able to obtain further assistance if needed. (It would be useful if the Central Council could set up an 'Online Publishing Group' to assist here.)
{{< /hint >}}

## Publishing on Local Server

{{< hint info >}}
We assume here:
 - The user has set up a folder on their device with the name of the repository to be created containing at least some of the required [files and folders](../015-files-and-folders).
 - All content files are in Markdown format, see [here](../020-markdown).
 - This has been initialised as a git repository.
 - The Hugo application is installed on the user's device.
{{< /hint >}}

In a terminal window, with the user's repository set as the present (sometimes, 'current') working directory, run the command 'Hugo server'. If there are no errors in the Markdown files, this will report a successful build and say something like: *'Web Server is available at http://localhost:1313/online-documents/'* (That is what appears when building this document). Entering that url into a browser will show the document.

{{< hint warning >}}
We have found it useful to work with the editor and browser both open - ideally with the browser on a second screen.
{{< /hint >}}

The server will also report that it is 'watching' a number of files, including the 'content' folder. If any of the files are modified and saved, the change will appear immediately in the browser. This is very useful when developing a new document.

## Publishing from Github

CCCBR online documents are usually held in GitHub under the 'Central Council of Church Bellringers' Organisation - see [here](https://github.com/cccbr). A user will need permission to host a document within this Organisation. The responsibility for giving that permission is not currently clear - another case for a recognised 'Online Publishing Group'.

Setting up a repository is not difficult, although advice is recommended. Once set up, files can be uploaded from the user's device. But, again, advice is needed - GitHub has some tricks. 

When the repository is set up, it is fairly easy to navigate the files and folders and to edit the Markdown code if needed. When the edit is complete, the user must 'Commit' the changed file - GitHub stores all changes. There is an option (recommended) to supply a brief reason for the change.

A 'Commit' triggers an action to rebuild the published website, also held within GitHub. This is similar to the way the site is rebuilt with a local server, but there may be some minutes delay before that happens.

----

{{<hint info>}}
**[Previous Chapter](../040-navigation-menus/)** - **[Next Chapter](../060-workflow)**
{{</hint>}}

----

## Disclaimer
 
*Whilst every effort has been made to ensure the accuracy of this information, neither contributors nor the Central Council of Church Bell Ringers can accept responsibility for any inaccuracies or for any activities undertaken based on the information provided.*

Version 0.1, September 2023

© 2023 Central Council of Church Bell Ringers
