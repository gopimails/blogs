# Steps
- First time
    - hugo new site codedrikblog
    - cd to themes
        - clone the theme to this 
        - https://github.com/lxndrblz/anatole
    - add theme to config.toml
        - https://www.youtube.com/watch?v=LIFvgrRxdt4&t=302s
- Repeat
   -  Create new post
       - `hugo new posts/vernemq_mosquitto_bridge.md`
   - Update the md file with your actual content.
   - Check if everything is good
       - `hugo server`
           - Will build and give an url to check.
   - publish
       - `hugo -t anatole`
       - `git add .`
       - `git commit -m vernemqtomosquitto`
       - `git push origin main`

# blogs

- Whenever you clone, or take latest, should be followed up with below two commands.
    - git submodule init
    - git submodule update
    - sudo git submodule update --init --recursive
    - sudo git submodule update --recursive
- Reason : themes\anatole is a submodule(not a clone add) and should be synced.