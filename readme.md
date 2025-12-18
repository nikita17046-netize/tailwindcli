   set:
    git config --global user.name "nikita17046-netize" (Sets your username for Git commits globally (for all repositories on your system).)
    git config --global user.email nikita17046@gmail.com (Sets your email address for Git commits globally.)
    git config --list (Displays all Git configuration settings currently active.)

    unset:
    git config --global --unset user.name (Removes the globally configured Git username.)
    git config --global --unset user.email (Removes the globally configured Git email.)
    -----------------------------------------------------------------------------
    git add .  (Adds all changed files in the current directory (and subdirectories) to the staging area.)
    git commit -m "msg" (Saves the staged changes as a snapshot (a commit) in your local repository.)
    git push origin main  or master  (Uploads your local commits to a remote repository (like GitHub).)
    --------------------------------------------------------------------------
    Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned


    tailwind.config.js  file
    ===

    /** @type {import('tailwindcss').Config} */
    export default {
      content: ["./src/**/*.{html,js}"],
      theme: {
        extend: {},
      },
      plugins: [],
    }
    ==============================================================================
    file in tailwindcli==============

    npm install tailwindcss @tailwindcss/cli (create 3 files packeg.json,packeg-lock.json,node_modual)

    ----------------- jo node delete thy jay to -----------------------
    npm i (create packeg-lock.json,node_modual file )
    -----------------------run krava mate------------------------------------------------
    in terminal 
    npm run start (run the program)
    =======================Branches============================================
    git branch (show all branch)
    git branch branch_name (create a new branch)
    git checkout branch_name (Switches your working directory to the specified branch.)

    =========…or create a new repository on the command line
    echo "# tailwind-cli" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/rupaprajapati082/tailwind-cli.git
    git push -u origin main
    …or push an existing repository from the command line
    git remote add origin https://github.com/rupaprajapati082/tailwind-cli.git
    git branch -M main
     git push -u origin main
