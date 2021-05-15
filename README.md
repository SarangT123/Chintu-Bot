# Chintu Bot

Chintu bot is a multi-purpose discord bot written in discord.py

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

* `Python` 3.x
* `pip`
* [`virtualenv`](https://virtualenv.pypa.io/en/latest/)
* Reddit API Client ID and Secret ([Reddit App](https://www.reddit.com/prefs/apps))
* A MongoDB database (preferably MongoDB Atlas)
* A JSON Blob at [jsonblob.com](https://jsonblob.com)
* A discord bot token ([How to get a discord bot token](https://gist.github.com/frank-dspeed/db39a021c1cb006ddc5b9b771667d273))

### Running the bot

* Clone the repository

```shell script
$ git clone https://github.com/Noob-Coders-Gang/Chintu-Bot.git
$ cd Chintu-Bot
```

* Create new virtual environment

```shell script
$ virtualenv venv
```
* Activate virtual environment

```shell script
# Windows (CMD.exe)
$ path\to\venv\Scripts\activate.bat
# Unix
$ source path/to/venv//bin/activate
```
* Install Dependencies
```shell script
$ pip install -r requirements.txt
```
* Create a copy of [`dummy.env`](dummy.env) file and name it `.env` in the project root

* Fill in the environment variables in the said `.env` file

* Run the bot 
```shell script
$ python main.py
```
* Output
```
loading extensions...
logging in...
updating databases...
Logged in as Chintu#2757
```
![Bot Online](https://cdn.discordapp.com/attachments/819532187820883968/843057699167535124/unknown.png)

####Note
If an extension is not working properly, you can turn it off by adding the extension file name to this line in [main.py](./main.py):
```python
load_extensions(bot, ["manage_commands.py", "Help.py", "Error_extension.py"])
```

## Built With

* [discord.py](https://github.com/Rapptz/discord.py) - API wrapper for Discord written in Python

## Contributing

If you want to contribute to a project and make it better, your help is very welcome. Contributing is also a great way to learn more about social coding on Github, new technologies and and their ecosystems and how to make constructive, helpful bug reports, feature requests and the noblest of all contributions: a good, clean pull request.

### How to make a clean pull request

Look for a project's contribution instructions. If there are any, follow them.

- Create a personal fork of the project on Github.
- Clone the fork on your local machine. Your remote repo on Github is called `origin`.
- Add the original repository as a remote called `upstream`.
- If you created your fork a while ago be sure to pull upstream changes into your local repository.
- Create a new branch to work on! Branch from `development` if it exists, else from `master`.
- Implement/fix your feature, comment your code.
- Follow the code style of the project.
- Add or change the documentation as needed.
- Squash your commits into a single commit with git's [interactive rebase](https://help.github.com/articles/interactive-rebase). Create a new branch if necessary.
- Push your branch to your fork on Github, the remote `origin`.
- From your fork open a pull request in the correct branch. Target the project's `development` branch if there is one, else go for `master`!
- If the maintainer requests further changes just push them to your branch. The pull request will be updated automatically.
- Once the pull request is approved and merged you can pull the changes from `upstream` to your local repo and delete
your extra branch(es).

And last but not least: Always write your commit messages in the present tense. Your commit message should describe what the commit, when applied, does to the code – not what you did to the code.

## Code of Conduct

### Our Pledge

In the interest of fostering an open and welcoming environment, we as
contributors and maintainers pledge to making participation in our project and
our community a harassment-free experience for everyone, regardless of age, body
size, disability, ethnicity, gender identity and expression, level of experience,
nationality, personal appearance, race, religion, or sexual identity and
orientation.

#### Our Standards

Examples of behavior that contributes to creating a positive environment
include:

* Using welcoming and inclusive language
* Being respectful of differing viewpoints and experiences
* Gracefully accepting constructive criticism
* Focusing on what is best for the community
* Showing empathy towards other community members

Examples of unacceptable behavior by participants include:

* The use of sexualized language or imagery and unwelcome sexual attention or
advances
* Trolling, insulting/derogatory comments, and personal or political attacks
* Public or private harassment
* Publishing others' private information, such as a physical or electronic
  address, without explicit permission
* Other conduct which could reasonably be considered inappropriate in a
  professional setting

### Our Responsibilities

Project maintainers are responsible for clarifying the standards of acceptable
behavior and are expected to take appropriate and fair corrective action in
response to any instances of unacceptable behavior.

Project maintainers have the right and responsibility to remove, edit, or
reject comments, commits, code, wiki edits, issues, and other contributions
that are not aligned to this Code of Conduct, or to ban temporarily or
permanently any contributor for other behaviors that they deem inappropriate,
threatening, offensive, or harmful.

### Scope

This Code of Conduct applies both within project spaces and in public spaces
when an individual is representing the project or its community. Examples of
representing a project or community include using an official project e-mail
address, posting via an official social media account, or acting as an appointed
representative at an online or offline event. Representation of a project may be
further defined and clarified by project maintainers.

### Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be
reported by contacting the project team at `noobcodersgang@gmail.com`. All
complaints will be reviewed and investigated and will result in a response that
is deemed necessary and appropriate to the circumstances. The project team is
obligated to maintain confidentiality with regard to the reporter of an incident.
Further details of specific enforcement policies may be posted separately.

Project maintainers who do not follow or enforce the Code of Conduct in good
faith may face temporary or permanent repercussions as determined by other
members of the project's leadership.

### Attribution

This Code of Conduct is adapted from the [Contributor Covenant][homepage], version 1.4,
available at [http://contributor-covenant.org/version/1/4][version]

[homepage]: http://contributor-covenant.org
[version]: http://contributor-covenant.org/version/1/4/

## Authors

* [**ProgrammerGaurav**](https://github.com/programmergaurav)
* [**swasthikshetty10**](https://github.com/swasthikshetty10)
* [**Devansh-bit**](https://github.com/Devansh-bit)

See also the list of [contributors](https://github.com/Noob-Coders-Gang/Chintu-Bot/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details

