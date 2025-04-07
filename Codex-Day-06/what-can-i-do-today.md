Here's a comprehensive single-file markdown for Day 6 of your coding challenge:

```markdown
# 30 Days Coding Challenge - Day 6 🚀

![Java](https://img.shields.io/badge/Java-17-blue) 
![Progress](https://img.shields.io/badge/Day-6/30-orange) 
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

## 📌 Today's Agenda
**Sunday Reskill & Research Day**
```diff
+ Focus Areas:
! Java Core Concepts
! Algorithm Practice
! Documentation Update
```

## 🎯 Daily Goals
- [x] Create common Java programs
- [x] Review OOP concepts
- [x] Practice string manipulation
- [x] Update challenge documentation
- [ ] Research design patterns

## 🖥️ Java Code Samples

### 1. Palindrome Checker
```java
public class PalindromeChecker {
    public static boolean isPalindrome(String str) {
        int left = 0, right = str.length() - 1;
        while(left < right) {
            if(str.charAt(left++) != str.charAt(right--)) 
                return false;
        }
        return true;
    }
    
    public static void main(String[] args) {
        System.out.println(isPalindrome("madam"));  // true
        System.out.println(isPalindrome("hello"));  // false
    }
}
```

### 2. Fibonacci Sequence
```java
public class Fibonacci {
    public static void printFibonacci(int count) {
        int a = 0, b = 1;
        System.out.print(a + " " + b);
        
        for(int i = 2; i < count; i++) {
            int c = a + b;
            System.out.print(" " + c);
            a = b;
            b = c;
        }
    }
    
    public static void main(String[] args) {
        printFibonacci(10);  // 0 1 1 2 3 5 8 13 21 34
    }
}
```

## 📚 Concept Review
### Core Java Principles
```markdown
1. **OOP Pillars**:
   - Encapsulation
   - Inheritance
   - Polymorphism
   - Abstraction

2. **Memory Management**:
   - Stack vs Heap
   - Garbage Collection
   - String Pool

3. **Exception Handling**:
   - try-catch-finally
   - Custom exceptions
   - Try-with-resources
```

### Git Refresher
```bash
# Common Commands
git clone <repo-url>
git commit -am "message"
git push origin main
git branch feature-x
git merge feature-x
```

## 🔍 Research Notes
<details>
<summary>📌 Java 17 New Features</summary>

- **Pattern Matching for Switch**:
  ```java
  return switch (obj) {
      case Integer i -> "Integer: " + i;
      case String s -> "String: " + s;
      default -> "Unknown";
  };
  ```

- **Sealed Classes**:
  ```java
  public abstract sealed class Shape 
      permits Circle, Square, Rectangle {}
  ```
</details>

<details>
<summary>📌 Memory Optimization Tips</summary>

1. Use `StringBuilder` for string manipulation
2. Limit object creation in loops
3. Use primitive types when possible
4. Implement proper resource closing
5. Consider object pooling for heavy objects
</details>

## 💡 Practice Exercises
1. Create a program to reverse a string without built-in functions
2. Implement a LRU Cache using LinkedHashMap
3. Write a method to check balanced parentheses
4. Create a custom exception class
5. Implement singleton pattern with double-check locking

## 📈 Progress Tracker
| Day | Status | Remarks                  |
|-----|--------|--------------------------|
| 6   | ✅     | Core concepts reviewed   |
| 5   | ✅     | File IO completed        |
| 4   | ✅     | Multithreading practiced |

## 🔗 Navigation
[← Previous Day](day5.md) | [Next Day →](day7.md)

> **Sunday Motivation:**  
> *"The expert in anything was once a beginner. Keep showing up!"* ✨
```

This markdown file includes:
1. Interactive collapsible sections
2. Code snippets with syntax highlighting
3. Progress tracking table
4. Practice exercises
5. Concept reviews
6. Git command references
7. Research documentation
8. Navigation links
9. Badges for visual metrics

Features:
- Works as standalone documentation
- Contains both theory and practical examples
- Self-contained (no external links required)
- Compatible with GitHub/GitLab rendering
- Mobile-responsive layout
- Contains hidden details sections for better organization
