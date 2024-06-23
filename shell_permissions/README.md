

0. My name is Betty

mkdir -p alx_be_shell/shell_permissions
vim alx_be_shell/shell_permissions/0-iam_betty
# (In vim, add the following lines)
# #!/bin/bash
# su betty
# (Save and exit vim with :wq)
chmod +x alx_be_shell/shell_permissions/0-iam_betty
tail -1 alx_be_shell/shell_permissions/0-iam_betty | wc -c



1. Who am I

mkdir -p alx_be_shell/shell_permissions
vim alx_be_shell/shell_permissions/1-who_am_i
# (In vim, add the following lines)
# #!/bin/bash
# whoami
# (Save and exit vim with :wq)
chmod +x alx_be_shell/shell_permissions/1-who_am_i


2. Empty!

mkdir -p alx_be_shell/shell_permissions
vim alx_be_shell/shell_permissions/4-empty
# (In vim, add the following lines)
# #!/bin/bash
# touch hello
# (Save and exit vim with :wq)
chmod +x alx_be_shell/shell_permissions/4-empty


3. Execute

mkdir -p alx_be_shell/shell_permissions
vim alx_be_shell/shell_permissions/5-execute
# (In vim, add the following lines)
# #!/bin/bash
# chmod u+x hello
# (Save and exit vim with :wq)
chmod +x alx_be_shell/shell_permissions/5-execute


4. Multiple permissions

mkdir -p alx_be_shell/shell_permissions
vim alx_be_shell/shell_permissions/6-multiple_permissions
# (In vim, add the following lines)
# #!/bin/bash
# chmod ug+x,o+r hello
# (Save and exit vim with :wq)
chmod +x alx_be_shell/shell_permissions/6-multiple_permissions


5. John Doe

mkdir -p alx_be_shell/shell_permissions
vim alx_be_shell/shell_permissions/7-set_permissions
# (In vim, add the following lines)
# #!/bin/bash
# chmod 751 hello
# (Save and exit vim with :wq)
chmod +x alx_be_shell/shell_permissions/7-set_permissions
