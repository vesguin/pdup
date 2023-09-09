Hello, I made a little Bash script that you can use to upload files to https://pixeldrain.com/ from the terminal. This is very useful for showing log files to developers or making quick backups of remote files through SSH.

To install it you can execute this command:

    wget https://raw.githubusercontent.com/Fornax96/pdup/master/pdup && chmod +x pdup

Explanation: The wget command downloads the script from github and saves it to /usr/local/bin/pdup so you can run it from the terminal. Then chmod makes it executable

Then you can upload files from anywhere in the system using

    ./pdup file.txt

If you want to uninstall pdup you can run

    rm -rf pdup

Be careful for typos! You don't want to accidentally remove your [/usr](https://github.com/MrMEEE/bumblebee-Old-and-abbandoned/issues/123) ;)
