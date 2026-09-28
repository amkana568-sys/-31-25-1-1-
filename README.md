# Саркисян Нарек Каренович Икбо 31-25 пр1


Task 1

#!/usr/bin/env bash
grep -v '^#' /etc/passwd | cut -d: -f1 | sort
