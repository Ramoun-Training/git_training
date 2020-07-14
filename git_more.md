### Introduction

In this lesson, we'll cover common Git commands used to manage your projects and to upload your work onto GitHub. We refer to these commands as the **basic Git workflow**. When you're using Git, these are the commands that you'll use 70-80% of the time, so if you can get these down, you'll be more than halfway done mastering Git!

### Questions

<details>
<summary>how to copy an existing repository from Github onto your local machine?</summary>
<ul><ul>
    <li>using the <code>clone</code> command.</li>
    <li>Use <code>git clone git@github.com:&lt;your-github-username&gt;/&lt;your-respository-name&gt;</code> </li>
</ul></ul>    
</details>

<details>
<summary>Explain the two-stage system that Git uses to save files.</summary>
<ul><ul>
   <li>A <strong>save</strong> in Git is divided into two terminal commands: <code>add</code> and <code>commit</code>. The combination of these two commands gives you control of exactly what you want to be remembered in your snapshot.</li>
  <li><strong>Staging:</strong> Think of <code>add</code> as adjusting the number of people or elements to be included in a photo. With Git, you can select the changes you want to save with <code>git add</code>. Imagine a project that contains multiple files where changes have been made to several files. You want to save some of the changes you have made and leave some other changes to continue working on them.</li>
  <li><strong>Committing:</strong> Think of <code>commit</code> as actually taking a photo, resulting in a snapshot. For example, to commit a file named README.md, type <code>git commit -m "Add README.md"</code>. The <code>-m</code> flag stands for "message" and must <strong>always</strong> be followed by a commit message inside quotation marks. In this example, the commit message was <code>"Add README.md"</code>.</li>
</ul></ul>
</details>

<details>
<summary>Describe how to upload your work to GitHub using Git</summary>
<ul><ul>
    <li>using the <code>push</code> command</ul>
</ul></ul>
</details>

<details>
<summary>Describe how to check the status of your files</summary>
<ul><ul>
    <li>Use <code>git status</code> to see any changes made since your last commit.</ul> 
</ul></ul>
</details>

<details>
<summary>how to view your commit history?</summary>
<ul><ul>
    <li>using the <code>git log</code> command</ul>
</ul></ul>
</details>

<details>
<summary>What is the Git command used to track files with Git?</summary>
<ul><ul>
    <li>Use <code>git add</code> to track files.</ul>
</ul></ul>
</details>

<details>
<summary>Explain what <code>origin</code> is in <code>git push origin master</code>.</summary>
<ul><ul>
    <li>In Git, <code>origin</code> is a placeholder name for the URL of the remote repository. Git sets up the origin by default when it clones a remote repository. You can use <code>origin</code> to access the remote repository without having to enter a full URL every time. <strong>This also means that you can have multiple remotes for a repository by giving each a unique name.</strong></li>    
    <li>If there is only one remote to the repository, you can use <code>git push</code> directly.</li>
</ul></ul>
</details>


<details>
<summary>Explain what <code>master</code> is in <code>git push origin master</code>.</code>.</summary>
<ul><ul>
    <li>In Git, <code>master</code> is the branch of the remote repository you want to push your changes to. We will get more into branches in a later lesson, but the main thing to remember is that <code>master</code> is the official branch in your projects where production-ready code lives.</li>
</ul></ul>
</details>

### Important Notes
- The basic Git syntax is `program | action | destination`.
- For further content about Git & GitHub --> [Click Me]("https://github.com/MrRamoun/curriculum/blob/master/web_development_101/git_basics/git_basics.md")
- see this article : [github in plain english](https://blog.red-badger.com/2016/11/29/gitgithub-in-plain-english)
- learn Git with [Bitbucket](https://www.atlassian.com/git/tutorials/git-lfs)
- for more help:
    * Local Git Manuals: `man git`, `git --help`.
    * for a specific command: `git remote --help`.
