## 1. What is the difference between git reset and git revert. When would you use one over the other?
Git reset merupakan mengembalikan comit ke versi sebelumnya dan menghilangkan commit terbaru. Nah jika git revert, dia bisa mengembalikkan lagi commit yg terakhir ke commit sebelumnya tanpa menghilangkan commit terakhir. 
Git revert, ketika mau menggabungkan commit yang awal ke commit yang terakhir. dan tidak menghilangkan commit terakhir.

## 2.  What is the difference between git merge and git rebase. When would you use one over the other?
Git Merge dalam penggabungannya terdapat commit baru untuk menggabungkan branch yang lain. Pada Git Rebase memindahkan semua branch baru ke cabang utama. Namun, seperti bercabang dalam branch utama yang baru.
Ketika memberikan pull request terhadap orang lain. Dan orang tersebut menambahkan branch baru dan mau menggabungkan branch milik kita dan bisa menggunakan Git Merge / Git Rebase.

## 3. What is the difference between git stash pop and git stash apply.When would you use one over the other?
Perbedaan dari git stash pop dan git stash apply. Ketika kita menggunakan git stash apply stash yang baru di restore ke sumber dan tidak akan dihapus dari stack, sementara ketika menggunakan git stash pop, stash akan hilang.
Ketika terdapat masalah di branch lain dan project di branch yang kita kerjakan belum selesai maka kita bisa menggunakan git stash.

## 4. What kinds of things can you do in interactive mode when rebasing?
Dapat mengubah commit di berbagai cara seperti editing, deleting, dan squashing.