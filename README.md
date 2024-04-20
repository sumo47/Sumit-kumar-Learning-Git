# Sumit-kumar-Learning-Git

#https://sumo47.github.io/Sumit-kumar-Learning-Git/

# Creating a new repo with name - Sumit-Learning-git
![Screenshot (521)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/dbe5883f-99b5-46d7-87ad-5f27cf5f50e4)


# Cloned Repo
![Screenshot 2024-04-19 115151](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/e4bf1903-ed12-45b2-b948-cacc0c9490ce)

#  Create a new branch named "feature-branch" from the main/master branch.
![Screenshot 2024-04-19 115657](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/495e6d7f-89e1-4a83-9f09-b20a91ffab71)

checked using git status 
![Screenshot 2024-04-19 120653](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/9fc3d70e-6ebe-44e8-bba5-0d32842c3fc7)

#  Added changes to the staging area and Commit changes with a meaningful commit message.
![Screenshot 2024-04-19 130802](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/f14e4313-c50c-431f-8d2f-3c1e0c9a37b5)

# Pushed changes to the remote repository.
![Screenshot 2024-04-19 132217](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/fc3eca47-b7b2-42b5-be08-f39e356d27ee)


# Create a new branch named "collaborator-branch" from the primary/master branch.
![Screenshot 2024-04-19 131229](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/6ae9854f-a8e3-46ca-ab2e-ffb7cf205aa1)

created file in main branch ( in line 34 there is written card title)
![Screenshot (522)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/85af3c7a-edf2-4e09-bf0b-b9cc08ec7fda)

changed written word in line no 34 in collaborator-branch 
![Screenshot 2024-04-19 185357](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/489772d3-6c7f-4ed5-9864-b2bd64da4e6d)

Mergeed in Main from collaborator-branch 
![Screenshot (523)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/f4ad45fc-b8df-413d-a109-fa72efdec2cd)

going to feature-branch and changed in line 34 again
![Screenshot (524)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/8f859e9a-fcbd-4eec-80c4-e28c2edfba95)

added and commited in feature-branch
![Screenshot (525)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/27e25dc9-2257-48aa-8ee4-36a9a3e1ccc1)

pushed in feature-branch
![Screenshot (526)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/2df4beee-b569-4ed2-8e31-cbc7bb5861dc)

# Now come back to main branch and trying to merge in main branch from feature-branch
Clearly, we can see that there is a conflict occurring in the main branch. Now, I have to resolve the conflict manually.
![Screenshot (527)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/a6a5d8a7-30ff-4437-b3bf-066f887ecd9c)

# Resolved merge conflict that asised 
and added , committed in main branch
![Screenshot (529)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/c1fbb1f8-60dc-473d-b2c0-ea67fb25879b)

i have done some changes in main branch for switching previous commit
and used code - git checkout <hash> for switching to previous commit
![Screenshot (530)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/af46e677-4983-465f-b20e-0d1ae130aa42)
![Screenshot (531)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/ab64c736-9a58-4bf3-a80d-c4f3b94888a7)


after write command code - git reset --hard Head~1 i can able to undo the last commit
![Screenshot (533)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/dfa3a798-4cc9-4584-882b-6f8308cb4f06)

# revert
i have done 3 commit for revert
![Screenshot 2024-04-20 000604](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/7cd1cce1-22c0-479e-8e8a-9f72733efe7e)

now i want to come back first commit than i have to use some command like code - git revert <hash>
![Screenshot (543)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/6d1de340-46aa-4af5-9fe7-b9a32a09c621)
there is some conflict occur , have to resolve

After resolve conflict , revert has been successfully done
![Screenshot (544)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/b2186f9b-3472-46ef-8a72-668f99ec74e2)

# Created a pull request from "collaborator-branch" to main/master.
and after resolve conflict i have successfully pulled from collaborator-branch in main branch
![Screenshot (545)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/25e125c5-e6e7-497b-9f55-ea27c19d2ad7)
![Screenshot (546)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/36b75f88-05c7-46b1-9034-e71d4121f1e3)
![Screenshot (547)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/fe15ed20-27a7-4ad4-abbb-bf56ffcfaf62)
![Screenshot (548)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/1c1e68e9-4e07-4d78-87d4-85e79e00d096)
![Screenshot (549)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/de908d6b-e176-4640-8392-fbb756047a4a)
![Screenshot (551)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/79c5345a-3d9f-4083-b1fc-5504224bbd8f)


# Forked a repository from another user's account. (Fork this repo - https://github.com/Tanvi-Ambre/Movie_Search)
![Screenshot (553)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/1808169e-a3b4-4c21-899a-312fd0c311d0)
![Screenshot (554)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/2eacdb3f-a347-40e3-8e94-283a2b92d691)

# Created a new branch in the forked repository.
![Screenshot (555)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/cc84f0d2-e26a-4559-9e84-8473e22a32ad)
![Screenshot 2024-04-20 002725](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/7dc6e9a9-4c42-4b08-8029-b94f2efcdfd1)


# - Make changes and create a pull request to the original repository.
![Screenshot (562)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/56b55ec6-c2ce-420d-97b0-18798e3d01a9)
![Screenshot (563)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/4387f2eb-3c24-4714-91f2-5b75a0c0b869)
![Screenshot (564)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/bf868894-a69e-4c2f-bbb7-8a4c0966142f)

# - Use the Git Lens extension in Visual Studio Code to visualize Git history.
![Screenshot (565)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/c574ac3e-c67c-48f0-b16b-158ee7a1ba30)

# - Deploy a static website using GitHub Pages.
![Screenshot (556)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/a202f9f1-6a7b-4793-8293-75c79d3d9b96)
![Screenshot 2024-04-20 004509](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/b5acd077-cc9b-447e-b416-20e94cbe488c)
![Screenshot (561)](https://github.com/sumo47/Sumit-kumar-Learning-Git/assets/88192207/845e46c8-24e7-4c11-b38e-4e125e113189)




















