
#Permission denied(public key).

- Problem--------------------------

$ git push origin dev
git@github.com: Permission denied(public key).
fetal: could not read from remote repository.

please make sure you have the correct access right and the repository exists.

- Solution ----------------



open git bash and type

	* ssh keygen
		-> hit enter enter
	then go to location ->  C:\Users\Mr_Rahul\.ssh\id_rsa(pub file) and copy all the genrated key.
 
 ![Screenshot 1](https://user-images.githubusercontent.com/65692565/179895314-d40379bb-686c-4f7f-a049-1f9a7b9bf07f.png)




 
    Now open your Git-hub account 

    - go to -> https://github.com/settings/profile and Go to SSH and GPG keys 
    


![Screenshot 2](https://user-images.githubusercontent.com/65692565/179895381-b2ca7d8a-b212-492c-9f35-c76f0e654ee8.png)






and click on SSH key




![Screenshot 3](https://user-images.githubusercontent.com/65692565/179895399-32dc5059-6450-4cfa-aef0-917fb101cb95.png)





- now, set title -> windows-key
- Paste copied key in key box 
- click add SSH.

Yeehhhh - it will done.......

Now, go to git bash and type  
- $ git push origin dev  
-            -> Hit enter ......

Problem Solved.........

https://github.com/rahulrkms 

