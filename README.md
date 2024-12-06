# Привет, меня зовут Илья 👋

## О себе
public class NickNameYouTuber {
    public static void main(String[] args) {
        Technologies technologies = new Technologies();
        technologies.frontEnd = new FrontEnd();
        technologies.backEnd = new BackEnd();
        technologies.devOps = new String[]{"Docker", "Kubernetes"};
        technologies.mobile = new String[]{"Android"};

        System.out.println("Current Focus: Создание масштабируемых full-stack приложений");

        technologies.displayTechnologies();
    }
}

class Technologies {
    FrontEnd frontEnd;
    BackEnd backEnd;
    String[] devOps;
    String[] mobile;

    void displayTechnologies() {
        System.out.println("\nFront-End Technologies:");
        frontEnd.displayFrontEnd();

        System.out.println("\nBack-End Technologies:");
        backEnd.displayBackEnd();

        System.out.println("\nDevOps Tools: " + String.join(", ", devOps));
        System.out.println("Mobile Technologies: " + String.join(", ", mobile));
    }
}

class FrontEnd {
    String[] js = {"React", "Next.js"};
    String[] css = {"Tailwind", "Bootstrap", "SASS"};

    void displayFrontEnd() {
        System.out.println("JavaScript Frameworks: " + String.join(", ", js));
        System.out.println("CSS Frameworks: " + String.join(", ", css));
    }
}

class BackEnd {
    String[] java = {"Spring", "Spring Boot"};
    String[] python = {"Django", "FastAPI"};
    String[] databases = {"PostgreSQL", "MySQL", "MongoDB"};

    void displayBackEnd() {
        System.out.println("Java Frameworks: " + String.join(", ", java));
        System.out.println("Python Frameworks: " + String.join(", ", python));
        System.out.println("Databases: " + String.join(", ", databases));
    }
}

<!--

## 🔧 Технологии и инструменты
- Языки программирования: [перечисли языки, которые ты знаешь, например, Python, JavaScript, C++]
- Фреймворки: [перечисли фреймворки, с которыми ты работал, например, React, Django]
- Инструменты: [перечисли инструменты, которые ты используешь, например, Git, Docker]

## 🌱 В настоящее время изучаю
- [перечисли технологии или темы, которые ты изучаешь в данный момент]

## 📫 Как со мной связаться
- Email: [твой email]
- LinkedIn: [ссылка на твой профиль]
- Twitter: [ссылка на твой профиль]

## 📈 Статистика
![Твоя статистика GitHub](https://github-readme-stats.vercel.app/api?username=ТвойUsername&show_icons=true&theme=radical)

## 📝 Мои последние проекты
- [Проект 1](ссылка на проект 1) - Краткое описание проекта.
- [Проект 2](ссылка на проект 2) - Краткое описание проекта.

-->

<!--
**ileztom/ileztom** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
