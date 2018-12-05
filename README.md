git init - initialize git at local machine
Centralized systems: TFS, SVN 
Git - Distributed Version Control System
   -DVCS sotwares: GIT, Mercury, ARX, Bazzar, tortoise SVN, Bit bucket
   - Terminologies used:  Repo, trucnk, tags, Brnaches, working copy, commit changes
   -https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control
Git - stores data as key  value pair <commitid, contents>
Git commit id / checksum - Key uses SHA1 algorithum to generate hash uniuqw id 
Git - has stores as snapshot  not file based 
(same files same snapsot, diff files new snapshot)

Integration - gerrit , sonar cube , Jenkins
Docker - envirmant management (devops) 
   - for e.g. by using ip address - deploy script in all servers in network
Jenkins - automating build & deploy process (devops)
branching - parallel development

Git stages 
commited - store in local DB
modified - files changes but not commited yet in DB
staged - 

Git - client 
GitHub - hosting servers 

commit => Tree - blob - tag
$ git log

git cat-file 49f39ee2 -p

first File 
   commit -> commit e352938e9b1ee304fd4dfe96691ddfa329eef9a8 
             -> tree 4d028a7bcf58c422135d8e486120ca7a65e977fd
			 -> blob 49f39ee23dab4ef35bbce01b042b5e15aca2a7cf    file1
 
Second File2 - [master 71ed258] Adding file2
   commit -> tree 686af98e090b532dadd829236bc2e168e311d615
			- parent e352938e9b1ee304fd4dfe96691ddfa329eef9a8
			- author authorName 1543990339 +053
			
	Tree stores files 
blob stores - content in blob 
version : same files with diff tagging 

git add filename
git commit -m "sting"
git cat-file <first6charactersof treeorblob> -p
git branch develop - create branch
git checkout develop - switch branches 
git merge develop - add files into master brnach ( switch to master)
git checkout -b feature
	
git clone https://github.com/khairnaramol/OwnLearningCourses.git
cd OwnLearningCourses
git checkout git(branchName)
