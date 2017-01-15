<h1>Getting Started</h1>
<h2>Getting the project files</h2>
First, you're going to need a way to pull down the Git project. If you like to type commands inside of a console window like a hacker, feel free to use the base version of <a href="https://git-scm.com/">Git</a>. Otherwise we recommend installing one of these GUIs.
<ul>
    <li>
        <b><a href="https://www.gitkraken.com/">GitKraken</a> (Windows, Mac, Linux)</b>
    </li>
    <li>
        <b><a href="https://desktop.github.com/">GitHub Desktop</a> (Windows, Mac)</b>
    </li>
    <li>
        <b><a href="https://www.sourcetreeapp.com/">SourceTree</a> (Windows, Mac)</b>
    </li>
    <li>
        <a href="https://git-scm.com/downloads/guis">Other possible GUIs</a>
    </li>
</ul>
The next steps will cover each of the top three GUIs...
<h4>GitKraken</h4>
Go to <b>File -> Clone Repo</b>. From <b>URL</b>, enter or browse to the place you want the project folder to reside on your machine. Then copy/paste the repo address (https://gitlab.com/Siggraph-AR/SCAR2017.git) into the <b>URL</b> field. A full path will appear showing you what the project path will look like; changing the folder name is optional. Hit <b>Clone the repo</b>, and it GitKraken should pull down the project files into that path.

<h4>GitHub Desktop</h4>
In the top-left, click <b>(+) -> Create a new repository</b>. On the left hand side, select the repo you just created, and at the top-right click the <b>Tools and Options</b> gear icon. Open <b>repository settings</b>. Under remote, paste in the field the repo address (https://gitlab.com/Siggraph-AR/SCAR2017.git), then hit <b>Sync</b> at the top right.

<h4>SourceTree</h4>
Click <b>Clone/New</b> button at the top-left. Under <b>Clone Repository</b>, copy/paste the repo URL (https://gitlab.com/Siggraph-AR/SCAR2017.git) into <b>Source Path/URL</b>. Fill in the <b>Destination Path</b> with the location of the project files. Leave <b>Bookmark this repository</b> checked, and customize the <b>Name</b> of the repo if you want. Then hit <b>Clone</b>.

<h2>Opening the project in Unity</h2>
Those that are actually going to be hooking things up in Unity will need to download <a href="https://store.unity.com/download?ref=personal">Unity 5.5</a>. It should be the latest release version at the time of this write-up.
<br/>
Launch Unity and <b>Open</b> a project. Select the folder you pulled down from GitLab, and Unity should start loading and autogenerating the extra project files.