# DemoRepo
This is my first demo project.
### Adding SSH key to the GitHub:

######`These are the commands for adding SSH key to windows:`

- `BurraKishoreKumar@DESKTOP-NV0EHRS MINGW64 /f/Git_Workspace/gitTest (master)`
`$ ssh-keygen -t rsa -b 4096 -C "burrakishorekumar@gmail.com"
Generating public/private rsa key pair.`
`Enter file in which to save the key (/c/Users/Burra Kishore Kumar/.ssh/id_rsa):` click on the enter button
`Enter passphrase (empty for no passphrase):` enter your system/laptop pwd
`Enter same passphrase again:`enter your system/laptop pwd
`Your identification has been saved in /c/Users/Burra Kishore Kumar/.ssh/id_rsa.
Your public key has been saved in /c/Users/Burra Kishore Kumar/.ssh/id_rsa.pub.
The key fingerprint is:
SHA256:GnuYry4G5VSJEHyAdXuAcN5PK0Db6tLF+U5LPqe5CMY burrakishorekumar@gmail.com
The key's randomart image is:
+---[RSA 4096]----+
|.=B=o. .         |
|.+o=ooo          |
|  +.+.o          |
|   +o= .         |
|  .+= + S        |
| +...o *         |
|. E.  O .        |
| o .o*.=.        |
|   ..oX*.        |
+----[SHA256]-----+
`

######Generating the Agent id by using this cmd:
- `$ eval $(ssh-agent -s)` click on the enter button.
- `Agent pid 1383` This is the Agent id.

######Adding the SSH key:
- `$ ssh-add ~/.ssh/id_rsa` click on the enter button.
- `Enter passphrase for /c/Users/Burra Kishore Kumar/.ssh/id_rsa:` enter the password
- `Identity added: /c/Users/Burra Kishore Kumar/.ssh/id_rsa (burrakishorekumar@gmail.com)`: we got this Identity.

######Now add both of SSH key and GitHub.
- For Window Users: `$clip ~/.ssh/id_rsa.pub`
- For Mac Users: `$ pbcopy < ~/.ssh/id_rsa.pub`
- After entered the cmd then click on the enter button
- Open the GitHub account and go to `setting -> SSH and GPG keys` click on the `New SSH key` then paste `(ctrl+v)` on the public key.
- Click on the `Add SSH key`. 

###### You caan successfully added the Public key to your GitHub.
