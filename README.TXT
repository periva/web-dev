# Installation
Follow [this guide](https://gohugo.io/hosting-and-deployment/hosting-on-github/#step-by-step-instructions) to set up this repository with the [GitHub Pages repository](https://github.com/periva/periva.github.io) nested within.
1. Clone this repository.
  `git clone https://github.com/periva/web-dev.git Periva_Source`
2. Enter the project directory.
  `cd Periva_Source`
3. Clone the [GitHub.io Repo](https://github.com/periva/periva.github.io) into the `public` directory:
  `git clone https://github.com/periva/periva.github.io.git public`
4. Clone the [hugo-theme-learn](https://github.com/matcornic/hugo-theme-learn) theme into the `themes` directory:
  `cd themes && git clone https://github.com/matcornic/hugo-theme-learn.git`

HUGO GUIDE

To create a chapter:

	hugo new --kind chapter title/_index.md

To create content within a chapter:

	hugo new title/content.md
	hugo new title/subsection/_index.md

To run a simulation server:

	hugo server -D

To publish the content:

	./deploy.sh "commit message"
