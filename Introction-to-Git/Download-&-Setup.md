To fully utilize Git, especially for collaborating and hosting repositories, you need an account on a Git hosting platform.
create an account trough  this link Website: https://github.com

# Download and Setup Git on Ubuntu                                                                                                                              Update the Package List:

        sudo apt update

# Install Git:

        sudo apt install git -y

# Verify Installation:
# Check the installed version to confirm Git is set up.

     git --version

## Configure Git (One-Time Setup):
## Set your username and email for commit history.

        git config --global user.name "Your Name"
        git config --global user.email "your.email@example.com"

# Check Configuration:
# Verify the configuration settings.

        git config --list
