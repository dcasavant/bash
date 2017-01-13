# Does the remote profile exist?
if [ -r ~/git/custom-bash ] 
       then
                #Copy it to ~
                if [ -r ~/.bash_profile_local_copy ] 
                        then
                                mv ~/.bash_profile_local_copy ~/.bash_profile_local_copy.bak
                fi
                cp ~/git/custom-bash/custom_bash ~/.bash_profile_local_copy
                echo "Loading remote bash profile..."
        else
                echo "Remote bash profile not found.  Loading local copy... "
fi

# Load from the local copy
. ~/.bash_profile_local_copy || echo "***  Unable to load bash profile. Profile settings are offline."
