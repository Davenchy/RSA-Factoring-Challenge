# RSA-Factoring-Challenge

- To build `libfactorize.so`
```bash
gcc -Wall -Werror -Wextra -pedantic -std=c89 -lm --shared -fPIC -o libfactorize.so factors.c
```
