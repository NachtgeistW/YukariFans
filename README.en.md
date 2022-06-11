# YukariFans_MkDocs

## Wha's this?

Anything related to VOICEROID!

<br/>

## Structure

Generate static website from Markdown files with MkDocs.
Theme used: MkDocs-Material, [doc](https://squidfunk.github.io/mkdocs-material/).

#### Plugins 

See the config file (mkdocs.yml) for a description of the plugins' functionalities.

<br/>

## Installation

1.  Install Python 3.9
2.  Install required modules with <code>pip install -r requirements.txt</code>

* If a Python environment already exists, or if you want to start anew, you can use Miniconda/Conda for Python environment management
  * To create a new environment: `conda create -n name_of_this_environment python=3.9.5 `

<br/>

## Usage

#### View pages locally

1.  Enter directory <code>YukariFans_Mkdocs/YukariFans</code> (where <code>mkdocs.yml</code> is located)
2.  Start local server with <code>mkdocs serve</code>
3.  Access the address (default: <code>http://127.0.0.1:8000/</code>) with any browser 

#### Upload webpages

1.  Enter <code>YukariFans_Mkdocs/YukariFans</code>
2.  Run `mkdocs gh-deploy` to upload pages to gitee-page
