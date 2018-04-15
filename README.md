# bash_scripts

This is a list of useful commands

# Delete history
for h in `seq last_command_number_plus_one -1 first_command`; do history -d $h; done
