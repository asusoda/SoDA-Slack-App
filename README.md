# Software Developers Association Slack Application

This is a Slack application written in Python, for the purpose of helping users adjust to the Software Developers Association Slack at Arizona State University.

## Getting Started

This application requires Python version 3.6.7 or later to be installed, as well as virtualenv

### How to install

After installing Python 3.6.7 or later and virtualenv, you'll need to install all of the necessary dependencies using this command:
```
pip install -r requirements.txt
```
### Things to note

* I made this as an excuse to learn Python and as such, I have no knowledge of standard conventions for Python. I would recommend running the code through a linter before creating a pull request.
* The application must be running in order for people on the SoDA slack to use it. At the time of writing, SoDA has no dedicated host for the application.

## Contributing

To contribute, just remember to add any additional packages to [requirements.txt](/requirements.txt)

## Resources

* [Slack API Documentation](https://api.slack.com/#read_the_docs)
* [Python Slack Developer Kit](https://slack.dev/python-slackclient/index.html)
* [Python Slack app Tutorial](https://github.com/slackapi/python-slackclient/tree/master/tutorial#table-of-contents) - What this app was built off of

## Authors

* **Randy Ngo** - *Initial Work*