# laravel-on-mac
How to setup a Mac for Laravel Development Environment

# Tools
Download and install the following tools
1. iTerm2 (https://www.iterm2.com/) and then install Oh My Zsh (https://ohmyz.sh/)
2. Github Desktop (https://central.github.com/deployments/desktop/desktop/latest/darwin)
3. Sublime Text (https://download.sublimetext.com/Sublime%20Text%20Build%203211.dmg)
4. Homebrew (https://brew.sh/)
4. PHP (brew install php)
4a. Start PHP (brew services start php)
5. Composer (brew install composer)
6. MySQL (brew install mysql@5.7)
7. Start MySQL (brew services start mysql@5.7)
8. Laravel Valet (composer global require laravel/valet)
8a. valet install
8b. export PATH=$PATH:~/composer/vendor/bin
9. cd~
10. mkdir Sites
11. cd Sites
12. valet park
13. sudo apachectl stop
14. valet restart
15. Install Laravel (composer global require laravel/installer)
16. cd ~/Sites
17. laravel new project
18. Secure Site (cd ~/Site)
18a. valet secure project

