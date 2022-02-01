# php-consistent-functions
A wrapper class of existing php functions to enable consistent function naming of functions in php
## Introduction
There was a discussion regarding suggestion to improve newer version of PHP(v9.x) and a redditor u/marktheprogrammer asked for the suggestions and opinion at  
https://www.reddit.com/r/PHP/comments/sfvi74/longterm_planning_for_php_90_error_promotion/

I requested to create an open-sorurce community managed package which can simplify the process of transforming all the existing functions to consistent naming, I don't know if my idea was good enough or not, but one redditor suggested to start it as a package.
so, Here I am starting this github repo for it.

I will not dedicate any pre-decided time or efforts on it as It is a hobby project type of thing for me. I would encourage all the interested people to join the project.

## Current Progress

I just scrapped list of all the functions available by default in php from https://www.php.net/manual/en/indexes.functions.php. After scrapping, I tried to reduce to current scope of project by removing all the functions which has colon(:) or slash(\) in the function name, and created an assoiciative array of the available function in the file.

## License
The project is distributed as GNU GPL v2 license

## Contributor Agreement.
To simplify the future complexicity of the project, All the pull request will be dual licensed. One will be licensed to me providing all the rights to use/grant the code as whatever means I want with no restriction, and Second will be licensed to the peoject as a original projects GNU GPL v2.0 License.
I am doing it simply to make sure that if the project gets momentum and needed to be transferred to the community, I can do it easily without any difficulty(I prefer permissive licenses).
