<h1 align="center">Hi 👋, I'm Sasso</h1>

# Introduction

First of all: call me Sasso, it's easier. Or pronounce the `E` in Salvatore, please.

I'm a passionate Italian developer, currently based in France and working as a C++ Software Engineer.

I can reassume my philosophy in one sentence: what we know is a drop, and what we don't know is an ocean.
Following that, I try to improve my knowledge every single day in every possible domain, especially coding.

## About Me
```cpp

class SoftwareEngineer
{

private:
    std::string name;
    std::string role;
    std::vector<std::string> expertises;
    std::vector<std::string> proficiencies;
    std::vector<std::string> languageSpoken;
    std::vector<std::string> interests;

public:
    SoftwareEngineer() : name("Salvatore SPINA"),
                         role("Software Engineer"),
                         expertises("C", "C++", "Python", "Algorithm & Data Structures", "Scripting"),
                         proficiencies("Linux", "Git", "Docker", "Assembly", "Cybersecurity", "Agile"),
                         languageSpoken({"it_IT", "en_US", "fr_FR"}),
                         interests("Animation", "C++", "Algorithm & Data Structures") {}

    void sayHi() const
    {
        std::cout << "Hello ! My name is" << name << "\nWelcome to my GitHub profile !" << std::endl;
    }
};

```
