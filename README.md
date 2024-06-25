# El78Upgrade
# Leapp upgrade el7 to el8

# Playbook for automatically Leapp Upgrade from Rhel7 to Rhel8.

# Simple usage: ansible-playbook -i dcex9002tzf0g8i, el78upgrade.yml --diff --vault-password-file=vaultkeyfile Tags: --before- execute preupgrade ans upgrade steps, including server reboot --after - steps needed after Upgrade (restart McAfee/ENS, reinstall Icinga2, reinstall F-secure)

# Simple usage with tags: ansible-playbook -i dcex9002tzf0g8i, el78upgrade.yml --diff --skip-tags before --vault-password-file=vaultkeyfile
