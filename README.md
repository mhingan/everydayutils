```markdown
# EverydayUtils 🛠️

A small Java utility library with everyday-useful tools, starting with a smart password strength evaluator.

## ✨ Features

- 🔐 **PasswordStrengthEvaluator**  
  Evaluate password strength based on:
  - Length (8–30 chars)
  - Uppercase and lowercase letters
  - Special characters (@, &, !)
  - Common password detection (from external list)

- 🔄 Password suggestion if input is weak or common
- 🔜 More utility classes coming soon (time converters, file organizer, internet checker, etc.)

## 🧪 How to Use

### Maven

Add the JitPack repository to your `pom.xml`:

```xml
<repositories>
    <repository>
        <id>jitpack.io</id>
        <url>https://jitpack.io</url>
    </repository>
</repositories>
```

Then add the dependency:

```xml
<dependency>
    <groupId>com.github.mhingan</groupId>
    <artifactId>everydayutils</artifactId>
    <version>v1.0.1</version>
</dependency>
```

---

## ✅ Example

```java
import com.myutils.everydayutils.PasswordStrengthEvaluator;

public class Main {
    public static void main(String[] args) throws Exception {
        String result = PasswordStrengthEvaluator.evaluatePassword("Test123!");
        System.out.println(result);
    }
}
```

---

## 📦 Build Locally

```bash
mvn clean install
```

---

## 🔄 Roadmap

- [x] Password strength evaluator
- [ ] Random data generator
- [ ] Business date calculator
- [ ] File organizer
- [ ] Internet connectivity checker

---

## 📚 License

MIT – Free to use, modify, distribute.  
Built with ❤️ by [mhingan](https://github.com/mhingan)
```

---

## 🧾 Ce trebuie să faci:

1. Creezi fișierul în rădăcina proiectului:

```bash
touch README.md
```

2. Deschizi și inserezi conținutul de mai sus.
3. Faci commit și push:

```bash
git add README.md
git commit -m "Add README.md for public repo"
git push
```
