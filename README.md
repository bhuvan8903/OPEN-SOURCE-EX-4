# OPEN-SOURCE-EX-4


#### NAME : Bhuvaneshwaran H
#### REG NO : 212223240018

## AIM:
 To create a shared directory /common/admin with proper ownership, group access, and permissions, and to verify that the user harry belongs to the required group.
## ALGORITHM:
STEP 1 : sudo mkdir -p /common/admin
STEP 2 : sudo chown root:admin /common/admin
STEP 3 : sudo chmod 2770 /common/admin
STEP 4 : ls -ld /common/admin
STEP 5 : drwxrws--- 2 root admin ... /common/admin
STEP 6 : groups harry

## OUTPUT :
<img width="916" height="619" alt="image" src="https://github.com/user-attachments/assets/67883427-594a-46c0-8570-30997696edc1" />

## RESULT :
Thus the commands has been executed successfully in RedHat Lab(Terminal)

