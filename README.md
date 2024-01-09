Updating VCG website instructions

1. Pull Github repo with most recent website (https://github.com/kotrynav/vcgsite.git)
    1. First person to pull, make a personal copy and create a new GitHub repo for your semester.
    2. Second+ people, pull from that semester’s repo.
2. Make and save changes locally to folder (this means, if multiple people working, always need to sync everyone’s local changes to change the actual website)
3. Using the following link (https://www.ocf.berkeley.edu/docs/services/shell/#h2_sftp), scroll to the SFTP section where you find a link to download FileZilla and go ahead it.
4. Open FileZilla and at the top enter the following information and click Quickconnect
    1. Host name: ssh.ocf.berkeley.edu
    2. Username: vcg
    3. Password: valleyconsultinggroup
    4. Port: 22
5. Once logged in, you fill find your local file system on the left and remote OCF server filesystem on the right. Double click public_html on the right where you fill find a folder identical to our local vcgsite folder.
6. Drag and drop in any updated files and click ok when prompted to overwrite existing file. 
7. Wait for transfer to queue and finish at the bottom and after a few minutes the website should be updated.
8. Regularly commit changes to GitHub to maintain website.


