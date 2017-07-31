# GitHub Avatar Downloader, by Jono Sue



## Problem Statement

Given a GitHub repository name and owner, download all the contributors' profile images and save them to a subdirectory, `avatars/`.



## Expected Usage

This program should be executed from the command line, in the following manner:

`node download_avatars.js <repo-owner-username> <repo-name>`



## Functional Requirements

As an open source project leader,<br />
I want a folder with the avatars of all of my github project's contributors<br />
so that I can use them in a website.<br />

Given

I have node installed<br />
I am in the shell<br />
I have your file in my current folder<br />


When

I execute your file using node, providing a github user and repository as command-line arguments<br />
For example:<br />
`$ node download_avatars.js nodejs node`


Then

I should find a folder called avatars in my current directory<br />
The avatars folder should contain images corresponding to the avatars of the contributors of the repo<br />
The name of each image file should be the contributor's name and the file extension (ex. johnny.png)<br />



## Implementation Requirements

uses 'request' library to make the HTTP requests<br />
uses git for version control