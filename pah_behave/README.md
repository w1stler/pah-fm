# Download Chromedriver

1. go to the `http://chromedriver.chromium.org`
1. download the latest version of Chromedriver
1. move it to /usr/local/bin

You can repeat these steps for Geckodriver or other.

# Creating virtual environment

Create separate folder for your virtual environment, eg. in home directory:

`mkdir selenium`
`cd selenium`

python3 -m venv pah_behave

source pah_behave/bin/activate

pip install -r requirements.txt

# Working with virtual environment

From home directory:

`cd selenium`
`source pah_behave/bin/activate`

Go to the directory with PAH website, eg.

`cd codeforpoznan/pah_fm/pah_behave`

# Running behave tests

Make sure, that virtual environment is active, so the prompt will look like:

`(pah_behave) ~/codeforpoznan/pah-fm/pah_ccbehave`

`behave pah_ccbehave/features/`
