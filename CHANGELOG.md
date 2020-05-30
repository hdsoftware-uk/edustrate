# Version History: Edustrate
We are documenting our web application updates and version history here. You can access the constantly updated version on GitHub.

## Our semantic system
* All of the first digits are distinctly major updates, for example a massive relocation and/or redesign.
* All of the second digits are less major updates, for example a new feature added to the existing app.
* All of the third digits are minor updates, for example a large bug fix or a new minor feature.
* All of the fourth digits are bug fixes or pre-release versions.

***

## Alpha Versions
These are pre-official release versions of Edustrate, up to date as of 9pm on May 26th 2020.

### v1
* Designed wireframed web application, showing index, task dashboard and other pages and their links in the sidebar
* Edited dropdowns and modified title bar

### v1.1
* Added official GitHub release
* Added about.html webpage listing details about the program and its design

### v1.1.0.1
* Added more HTML webpage (chatdash.html) which is the starting point for the Chat function.

### v1.1.2
* Created Teacher UI
* Edited structure: main folder is called `src`, subfolders are `.child`, `.teacher` and `icons`

**As of 26th May 2020, no other versions have been released. You can track updates via our GitHub repository.**


## Release Dates
| Version number | Release date        | Released on GitHub|
|-----------------|------------------|--------------------|
| < v1.0 | Multiple dates | ❌ |
| v1.0                     | April 2020 (date unknown) | ❌ |
| v1.1 | 26th May 2020 | ✔️ |
| v1.1.0.1 | 27th May 2020 | ✔️ |
| v1.1.2 | 28th May 2020 | ✔️ |


## Planned Folder Structure

Files are stored in a `.zip` file, with the syntax as follows:

```
edustrate [type: alpha, beta, stable, pre-release] v[number: 1.1.1.1].zip
```

<ul>
<li><code>src</code></li>
<li>README.md</li>
<li>CHANGELOG.md</li>
<li>LICENSE</li>
<ul>
<li><code>.child</code></li>
<li><code>.teacher</code></li>
<li><code>.parent</code></li>
<li><code>.tp</code></li>
<li><code>.pitstop</code></li>
<li><code>.globalassets</code></li>
</ul>
</ul>


### Bugs to be fixed & features to be added in `v1.1.3`
* A bug has been identified in the `.zip` file attached in the release v1.1.2 on GitHub. It means that the `.teacher` partition does not exist, and the UI cannot be viewed. Due to a storage fault, we can't now access the  original UI, but we are redesigning it for the occasion.
* We are now creating a parent UI in the zip file, in a new `.parent`partition. This will also feature a fix which allows you to view the child's dashboard.
