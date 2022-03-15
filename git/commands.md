$ git remote -v
origin  https://github.com/sshelake25/thbs_mean_mern.git (fetch)
origin  https://github.com/sshelake25/thbs_mean_mern.git (push)

DELL@DESKTOP-AARVGFN MINGW64 /e/TH_DevOps_MEAN_MERN/thbs_mean_mern (main)
$ git remote remove origin 

DELL@DESKTOP-AARVGFN MINGW64 /e/TH_DevOps_MEAN_MERN/thbs_mean_mern (main)
$ git remote -v

DELL@DESKTOP-AARVGFN MINGW64 /e/TH_DevOps_MEAN_MERN/thbs_mean_mern (main)
$ git remote add mythbs https://github.com/sshelake25/yuj-lab.git

DELL@DESKTOP-AARVGFN MINGW64 /e/TH_DevOps_MEAN_MERN/thbs_mean_mern (main)
$ git remote -v
mythbs  https://github.com/sshelake25/yuj-lab.git (fetch)
mythbs  https://github.com/sshelake25/yuj-lab.git (push)

DELL@DESKTOP-AARVGFN MINGW64 /e/TH_DevOps_MEAN_MERN/thbs_mean_mern (main)
$ git remote add origin https://github.com/sshelake25/thbs_mean_mern.git

DELL@DESKTOP-AARVGFN MINGW64 /e/TH_DevOps_MEAN_MERN/thbs_mean_mern (main)
$ git remote -v
mythbs  https://github.com/sshelake25/yuj-lab.git (fetch)
mythbs  https://github.com/sshelake25/yuj-lab.git (push)
origin  https://github.com/sshelake25/thbs_mean_mern.git (fetch)
origin  https://github.com/sshelake25/thbs_mean_mern.git (push)


----------------------------------------

1. Stage the files 
   `git add .`
2. To commit files
   `git commit -m "added first git commands file"`
3. Push remote repo
 git push --set-upstream mythbs main
    `git push origin main`

----------------- Setup global config for user ---------------

git config --list
git config user.email "shelakesurekha@gmail.com"
git config user.name ""