## Getting involved in ACCESS-CM3

There are several ways we welcome feedback and contributions on ACCESS-CM3 development. **Contributions from people of all career stages and backgrounds are highly encouraged. Development is led by ACCESS-NRI and the ESM-working group.** We follow an open development workflow where possible building on the work of international modelling groups.

### Interact with developers in person

If you would like to interact in person with the development team, we have regular technical meetings that [are announced here](https://forum.access-hive.org.au/t/access-cm3-technical-meetings-announce/5418) (subscribe to this thread for notifications), the meetings are held on every second Wednesday 2-3pm. Meeting minutes are [also on the forum](https://forum.access-hive.org.au/t/access-cm3-technical-meeting-minutes/5429). Everyone is welcome to suggest agenda items and participate (see announce thread for agenda). If you'd like to come, best to get in touch on [the ACCESS-Hive forum](https://forum.access-hive.org.au/c/esm/coupled-model/71) or just join a meeting ([zoom link](https://anu.zoom.us/j/83117761719?pwd=DGwVcKiyoaoVJhRp5tc5rPWYD7ZlO5.1)).

We also manage most of our development openly on GitHub, we track CM3 work on a [GitHub project board here](https://github.com/orgs/ACCESS-NRI/projects/15/views/1). If you'd like to have your issue considered for CM3 development, please [open an issue](https://github.com/ACCESS-NRI/dev_coupling/issues/new).

### Help us evaluate and improve applications of CM 

We have a community based group the "CM3 Dev-Eval Working group" that are helping with CM3 evaluation and development. Contributions from people of all career stages and backgrounds are highly encouraged. To join the meetings follow the announcements [here](https://forum.access-hive.org.au/t/esm-working-group-announce/567/67).

There's agenda (before the meeting) and minutes (after) the meetings [here](https://forum.access-hive.org.au/t/cm3-dev-eval-working-group-meeting-minutes-2025/5393), anyone can share a figure or contribute to the agenda. 

All community members (and ACCESS-NRI staff) can get [write access to the CM3 evaluation repository](https://github.com/ACCESS-Community-Hub/access-cm3-paper-1/). To get write access, you need to create an issue and request access, [please use this issue template](https://github.com/ACCESS-Community-Hub/access-cm3-paper-1/issues/new?template=add-user-request-to--access-cm3-1-repository-.md). Evaluation figures are being coordinated [here](https://github.com/ACCESS-Community-Hub/access-cm3-paper-1/issues/1). Further instructions are [here](https://github.com/ACCESS-Community-Hub/access-cm3-paper-1/blob/main/README.md).

### Report a bug or make a suggestion

Technical issues related to CM3 are best posted to [github.com/ACCESS-NRI/dev-coupling/issues](https://github.com/ACCESS-NRI/dev_coupling/issues/new). If you would like to discuss the issue first, feel free to post it on the [ACCESS-HIVE forum](https://forum.access-hive.org.au/c/esm/coupled-model/71).

## ACCESS-CM3-config-docs documentation contributions welcome 🙏
This documentation is a work in progress, and we welcome any contributions, including corrections and suggestions.

All contributions are welcome but we would particularly appreciate text suggestions (below). Contributions can be made in a few ways:

### Quick contributions 
!!! tip
    This method has the advantage that it's *very quick* (<1 minute!). The caveat is that, unless you have write access to the `access-cm3-config-docs` repository, you will not be able to preview the changes rendered into a website or create whole new pages. <br>

The simplest and fastest way to make a change to an _existing_ page is to click the edit "pencil" on the top-right corner. This will go to the relevant GitHub markdown file and clicking the top-right pencil again on GitHub will allow you to edit the file. Once complete, click `Commit changes...`. There are then _two_ possibilities, depending on whether you have  write access to [`access-cm3-config-docs`](https://github.com/ACCESS-NRI/access-cm3-config-docs): 

1.  **No write access**: this will prompt you to make a fork and then a pull request (less than 1 minute!). 
1.  **You have write access**: please commit changes on a new branch and then use a pull request (this relates to the next option). 

### Larger contributions (online PR-previews)
!!! tip
    This method allows you create whole new pages, and to preview the changes rendered into a website. It does not require you to install any software, but is **only available for people with write access to [`access-cm3-config-docs`](https://github.com/ACCESS-NRI/access-cm3-config-docs)**.<br>

Create a new branch, e.g. `jblogs/doc-update`, make doc changes (the documentation sources are in [github.com/ACCESS-NRI/access-cm3-config-docs/tree/main/documentation](https://github.com/ACCESS-NRI/access-cm3-config-docs/tree/main/documentation)), then open a related PR and a GitHub preview will be made automatically. 

### Larger contributions (`mkdocs` offline)
!!! tip
    This method allows you create whole new pages and to preview the changes rendered into a website. It works whether or not you have write access to [`access-cm3-config-docs`](https://github.com/ACCESS-NRI/access-cm3-config-docs), but requires you to install `mkdocs` and takes the longest to set up.<br>

Following [these instructions](https://docs.access-hive.org.au/about/contribute/#lets-get-started) but noting the documentation sources are in [github.com/ACCESS-NRI/access-cm3-config-docs/tree/main/documentation](https://github.com/ACCESS-NRI/access-cm3-config-docs/tree/main/documentation). You'll need to [fork](https://docs.access-hive.org.au/about/contribute/#clone-the-forked-access-hive-docs-github-repository-locally) and clone [github.com/ACCESS-NRI/access-cm3-config-docs](https://github.com/ACCESS-NRI/access-cm3-config-docs) if you want to write your own content (`mkdocs serve` should be invoked from within the `documentation` directory).

