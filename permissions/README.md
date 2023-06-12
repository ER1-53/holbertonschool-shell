# change d'utilisateur vers betty
su betty
# current user
whoami
# user listing
w
# current groups
groups
#changes the owner
chown [option] user[groups] file
#permissions numerique
777 rwx   rwx    rwx
   owner  grps   other
   1 --x 2 -w- 3 -wx 4 r-- 5 r-x 6 rw-
#permissions alpha
u user g groups o other
ugo+rwx / ug-wx
#copy of permissions
chmod --reference=[fichier_de_ref] [fichier qui copie]