# Observable Input-Output

Open a terminal in the "observable" repo and build a static site for self hosting:

	yarn build

You can edit the README.md and add subfolders with files here in the "io" folder:
[localhost:8887/observable/io](http://localhost:8887/observable/io/)

## Notes on Initial Install

You won't need to re-run the install steps on the current repo.
These are a summary of the [Observable Install Steps](
https://observablehq.com/framework/getting-started#3.-publish)

In the webroot, we ran yarn because it's faster and more secure than: npm init @observablehq

	yarn create @observablehq

Yarn may prompt you to upgrade node. Check where you have node.

	where node

If you have two node locations, use both cmds to update. The second is for node version manager:

	n latest
	nvm install node --reinstall-packages-from=node

Include sample files to help you get started?
│  Yes, include sample files
│
◇  Install dependencies?
│  Yes, via yarn
│
◇  Initialize git repository?
│  Yes

Open a new terminal in the repo.
And build a static site for self hosting:

	yarn build

To preview your built site locally, you can use a local static HTTP server such as [http-server](https://github.com/http-party/http-server):

	npx http-server dist

Or if the folder resides in your existing webroot, view it at:
[localhost:8887/observable/dist](http://localhost:8887/observable/dist/)

You can edit the README.md and add subfolders with files here in the "io" folder:
[localhost:8887/observable/io](http://localhost:8887/observable/io/)


If you are self hosting on GitHub, turn on Github Pages.