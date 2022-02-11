# GIT BRANCH & MERGE


## Developer:
### 16521336 - Muhammad Fadhil Amri

<p>&nbsp;</p>

## Table of Contents

1. [Branching](#branching)
2. [Checkout](#checkout)
3. [Merging](#merging)
4. [Delete Branch](#delete-branch)


<p>&nbsp;</p>

###	**Branching**
<br>

1. 	Commit file
<br>
![](Assets/fotomisi1_6_1.png)

2.	Buat branch  
        ```git branch <nama_branch>```
    <br>![](Assets/fotomisi1_6_2.png)

3.	Cek branch tempat head berada
*	    git branch
    <br>![](Assets/fotomisi1_6_3.1.png) 
*	    git log 
    <br>![](Assets/fotomisi1_6_3.2.png)

*	    git log --all  --decorate  --oneline --graph
    <br>![](Assets/fotomisi1_6_3.3.png)

<p>&nbsp;</p>

###	**Checkout** 
<br>

     git checkout <nama_branch_checkout>

![](Assets/fotomisi1_6_4.png)

<p>&nbsp;</p>

###	**Merging**
<br>

1.	Fast forward merging
*	Kembali ke branch master
<br>
![](Assets/fotomisi1_6_5.png)
*	Merging menggunakan command:
`git merge nama_branch_yang_akan_dimerge`
![](Assets/fotomisi1_6_6.png)
2.	Three way merge
*	Pastikan berada di branch master
<br>![](assets/fotomisi1_6_7.png)
*	Merging menggunakan command:
`git merge nama_branch_yang_akan_dimerge`
![](Assets/fotomisi1_6_8.png)
*	Akan muncul message dan konfirmasi

###	**Delete branch**

    git branch -d <nama_branch>
<br> ![](Assets/fotomisi1_6_9.png)
atau untuk menghapus tanpa pengecekan 
    git branch -D <nama_branch>
<br> ![](Assets/fotomisi1_6_10.png)



