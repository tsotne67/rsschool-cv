# Tsotne kireulishvili

# Contact

**Email:** tsokireulishvili@gmail.com  
**Phone:** +995 599 79 90 11  
**LinkedIn:** [MY LinkedIn](https://www.linkedin.com/in/tsotne-kireulishvili-653941275/)  
**GitHub:** [GitHub](https://github.com/tsotne67)  
**Telegram:** [Tsotne](https://t.me/tsotnekireulishvili)

---

## Skills

- HTML, CSS, JavaScript
- Git, GitHub
- Python
- C++,C,C#
- Sql

---

## Education

**Bachelor of Computer Science**  
Caucasus University -_2023 - 2027_

--

## About me

I am pasionate Computer science student from Tbilisi . I want to become profesional front-end developer

--

# My code

**Almost Prime Codeforces**

```c++
#include <bits/stdc++.h>
using namespace std;

int i, j, n, num[3005], ansx;

int main() {
    cin >> n;

    for (i = 2; i <= n; i++) {
        if (num[i] >= 1) continue;

        for (j = 2 * i; j <= n; j += i) {
            num[j] = num[j] + 1;
        }
    }

    for (i = 2; i <= n; i++) {
        if (num[i] == 2) ansx++;
    }

    cout << ansx << endl;

    return 0;
}
```

---

## Languages

- English advanced C1  
- Russian B2-C1  
- Georgian native  
