1. Pe-Parse
2. Парсер для работы с PE-файлами.
3. find . -type f | wc -l - 51
4. du -sh - 1,4M
5. 
6. find . -name ".clang-format" - ./.clang-format
7. find src -type f | wc -l - 4
8. grep -riw "socket" | wc -l - 0
9. grep -riw "select" | wc -l - 4
10. grep -riowE "Microsoft|Google|Intel" | wc -l - 10
11. fgit log --pretty=format: --name-only --diff-filter=A | grep LICENSE | head -n 1  - LICENSE
12. grep -E "BSD|GNU|MIT|APSL|Apache|GPL|AGPL|LGPL" LICENSE - The MIT License (MIT)
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS


/home/eikatkoff/pe-parse
