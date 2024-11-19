---
title: python setup logs
date: 2024-11-19T21:28:35.476Z
---
-------------------------//
-------------------------//25
---------------//15
-----//5




---------------//
-----//
-----//
-----//

-----//


---------------//
-----//
-----//
-----//

-----//

/﻿/problems statement 
p﻿ython does not have dep version manager like maven, it manages py version and libs using virtual env, but each env has only 1 version of a given dependency
s﻿ince couchbase have a big update for v7, if we want to work with both old and new version we need both connector for a single virtual env

`﻿
https://stackoverflow.com/questions/6570635
`﻿

w﻿hich seem to not have native pip support, changing PYTHONPATH each time does not seem to be ideal, so need to manually copy each version over then 
>﻿
import dependencyname_version as dependencyname



























-------------------------//
-------------------------//
