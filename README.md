# C110118242 #
# peter 蔣宗勳
## peter 蔣宗勳
### peter 蔣宗勳
#### peter 蔣宗勳
##### peter 蔣宗勳
###### peter 蔣宗勳
:smile:  😠

----
Emphasis, aka italics, with asterisks or underscores.  
Strong emphasis, aka bold, with **asterisks** or **underscores**.  
Combined emphasis with **asterisks** and **underscore**s.  
Strikethrough uses two tildes. ~~Seratetthis~~.  

----
1. First ordered list item  
2. Another item  
..* Unordered sub-list.
3. Actual numbers don't matter, just that it's a number  
..1. Ordered sub-list  
...2. 2nd  
4. And another item.  
...* note 1  
...* note 2  
***note 3  


![NKUST](logo.png "高科大")

- [ ] to do list
- [x] 1st thing
- [ ] 2nd thing
- [ ] 3rd thing
- [ ] 4th thing

```python
s = "python highlighted syntex"
print(s)
```

```js
var s = "Javascript highlighted"
alert (s)
```
Colons can be used to columns.
|Tables|Are|Cool|
|:---------|:--------:|--------:|
|col 3 is |right-aligned|$1600|
|col 2 is | centered|$12|
|zebra stripes|are neat|$1|
----
There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.
| Markdown| Less    | Pretty   |
| :-------|:------- | :--------|
|*Still*  |`renders`|**nicely**|
|1        |2        |3         |
----

### 請寫出相對應的java code (github 連結)
import java.util.ArrayList;
import java.util.List;

public class Student {
    private String name;
    private List<Course> courses;

    public Student(String name) {
        this.name = name;
        this.courses = new ArrayList<>();
    }

    public boolean addCourse(Course course) {
        if (courses.size() < 10) {
            courses.add(course);
            return true;
        }
        return false;
    }

    public boolean removeCourse(Course course) {
        return courses.remove(course);
    }

    public List<Course> getCourses() {
        return courses;
    }

    // Other getters, setters, and relevant methods
}

public class Course {
    private String courseName;

    public Course(String courseName) {
        this.courseName = courseName;
    }

    // Getters, setters, and other relevant methods
}


