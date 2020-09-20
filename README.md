# Git-Github-Demo
This repository contains guide to demonstrate the practical demo of Git and GitHub.

### Steps to create a new repository (Git and GitHub Fundamentals - Day 1 Activity)

1. ➕ Create a new repository on www.github.com under your github account. Check the **initialize with readme** option during the creation process.
2. 💻 Now, clone this repository so that you can make a local copy on your PC / laptop.

    ```
    git clone <url>
    ```

3. ⌨ After cloning the repo, a folder will be created at location where you cloned the repo. There will be a **README.md** file in this folder. Open the file and make some changes according to your wish.
4. 💾 After you have made your changes, save the file.
5. 💬 Now add the changes and then commit the changes with an appropriate message.

    ```
    git add .
    git commit -m "message-of-your-choice"
    ```

6. ✅ Finally, push the changes to the github repository. After pushing the changes, you will be able to look at the changes in the repository that you created in your account.

    ```
    git push origin master
    ```

### 🎉 Congratulations, you just created your first GitHub repository and pushed your first change..!!

## Steps to Contribute to DSC RNGPIT. (Git and GitHub Fundamentals - Day 2 Activity)

1. 🔱 Fork this Repository.
1. 🖥 After forking, a copy of this repository will be created in your account. Clone this Repository on your machine. (Please clone the repository which will be created in your account after forking.). Then change the directory to the repo directory. To get the url, click on the `green code button` on the repo page and copy `Clone with HTTPS` link.

    ```
    git clone <url>
    cd git-github-demo
    ```

1. 📄 After cloning the repo, a folder will be created at location where you cloned the repo. Now, open the README.md file from the repo folder on your desktop and go to the end of the file. You will find a Contributors section there. Add your name and your GitHub URL in this section by copy pasting the below statement. Please add your changes at the very end and please don't remove any other content.

    ```
    [your-name](your-github-url)

    For example,
    [John Doe](https://github.com/JohnD)
    ```

1. 📁 After doing the above steps, create a new folder in the repo folder on your computer and name it "Firstname-Lastname". For E.g., If your Firstname is "John" and Lastname is "Doe", then name the folder as `John-Doe`.
1. 📄 Inside this folder, create a **README.md** file.
1. ✍ Write something about yourself like your name, hobby, or something you are passionate about.( 🏈 | 💻 | 🎯)

1. 💬 Now add the changes and then create commit with commit message as your name.

    ```
    git add .
    git commit -m "Enter-your-name-here"
    ```

1. ➕ Add this repository as upstream.

    ```
    git remote add upstream https://github.com/DSC-RNGPIT/git-github-demo
    ```
1. 🔄 Now check if any changes were made by other people while you were making your changes. If any changes were made then please select **Accept both changes** to solve the merge conflict.

    ```
    git pull upstream master

    If any merge conflict occurs then resolve it by selecting ACCEPT BOTH CHANGES
    ```
    ```
    git add .
    git commit -m "your-name-here"
    ```
1. 👍 Now push the changes to your github repository.

    ```
    git push origin master
    ```

1. ✔ Create A Pull Request (PR).

### 🎉 Congratulations, for your first contribution to `<> DSC RNGPIT`. Your name will be displayed after we merge your PR.

## Contributors
[Raj Kharvar](https://github.com/rajkharvar)

[Deep Mevada](https://github.com/DeepMevada)

[Jayesh Mungara](https://github.com/Jay757)

[Zubair-12](https://github.com/Zubair-12)

[Palak Varu](https://github.com/PalakVaru)

[Fenil Patel](https://github.com/fenil420)
