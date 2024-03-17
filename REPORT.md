1. Pe-Parse
2. Парсер для работы с PE-файлами.
3. find . -type f | wc -l - 51
4. du -sh - 1,4M
5. find . -type f -iname "*.cpp" | xargs du -ch - 208K
find . -type f -iname "*.c" | xargs du -ch - 1,4M
find . -type f -iname "*.h" | xargs du -ch   - 64K
find . -type f -iname "*.hpp" | xargs du -ch - 1,4M
find . -type f -iname "*.cxx" | xargs du -ch - 1,4M
find . -type f -iname "*.py" | xargs du -ch - 8K
#остальных файлов нет в проекте
7. find . -name ".clang-format" - ./.clang-format
8. find src -type f | wc -l - 4
9. grep -riw "socket" | wc -l - 0
10. grep -riw "select" | wc -l - 4
11. grep -riowE "Microsoft|Google|Intel" | wc -l - 10
12. fgit log --pretty=format: --name-only --diff-filter=A | grep LICENSE | head -n 1  - LICENSE
13. grep -E "BSD|GNU|MIT|APSL|Apache|GPL|AGPL|LGPL" LICENSE - The MIT License (MIT)
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS


/home/eikatkoff/pe-parse
