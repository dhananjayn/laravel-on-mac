# laravel-on-mac
How to setup a Mac for Laravel Development Environment

# Tools
Download and install the following tools
1. iTerm2 (https://www.iterm2.com/) and then install Oh My Zsh (https://ohmyz.sh/)
2. Github Desktop (https://central.github.com/deployments/desktop/desktop/latest/darwin)
3. Sublime Text (https://download.sublimetext.com/Sublime%20Text%20Build%203211.dmg)
4. Homebrew (https://brew.sh/)
5. PHP (brew install php)
6. Start PHP (brew services start php)
7. Composer (brew install composer)
8. MySQL (brew install mysql@5.7)
9. Start MySQL (brew services start mysql@5.7)
10. Laravel Valet (composer global require laravel/valet)
11. valet install
12. export PATH=$PATH:~/composer/vendor/bin
13. cd~
14. mkdir Sites
15. cd Sites
16. valet park
17. sudo apachectl stop
18. valet restart
19. Install Laravel (composer global require laravel/installer)
20. cd ~/Sites
21. laravel new project
22. Secure Site (cd ~/Site)
23. valet secure project
