![Logo](http://francky.me/images/quora001.png)
# HelloGit
My first github repository

- [ ] Line 1
- [ ] Line 2
- [ ] Line 3



| Zelle 1/1 | Zelle 1/2 | Zelle 1/3 |
| --------- | --------- | --------- |
| Text      | Text      | Text      |
|           |           |           |
|           |           |           |



```c++
float amplify(float d, float scale, float offset)
{
    d = scale * d + offset;
    d = clamp(d, 0, 1);
    d = 1 - exp2(-2*d*d);
    return d;
}
```