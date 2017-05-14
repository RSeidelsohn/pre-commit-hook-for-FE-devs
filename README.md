# pre-commit-hook-for-FE-devs
A php file acting as a pre-commit hook file for any git repository using Symfony in order to **preventing commits of debugging code remainders or unresolved merge conflicts**

The original file comes from Phil Wright- Christie and you can find his much more elaborate project 'code quality' [here](https://github.com/philwc/code-quality). He kindly gave me the permission to use that file in my project here.

This file should serve as a base for frontend developers working on PHP projects/websites who want to use a pre-commit hook that prevents them from committing unresolved merge conflicts, debugging output or enabled oder disabled conditions for debugging purposes that she/he has forgotten about.

The `script` entry in the `composer.json` file will download the pre commit hook php file from this git repository on each `composer install|update` run.

Any suggestion/improvement/comment highly welcome!
