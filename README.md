# Привет, меня зовут Илья 👋

## ✍️ О себе
```java
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
```
## 📈 Статистика GitHub
<div align="center">
    <img height="180em" src="http://github-readme-streak-stats.herokuapp.com?user=ileztom&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D"/>
    <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ileztom&layout=compact&langs_count=7&theme=tokyonight&hide_border=true"/>
</div>

<div align="center">
    <img height="180em" src="https://github-readme-stats.vercel.app/api?username=ileztom&show_icons=true&theme=radical"/>
</div>

## 🔧 Технологии и инструменты
<!--
<div align="center">
    ![Java](https://github.com/user-attachments/assets/9a02072d-7d7c-4ce0-8618-087ec55e71ae)
    
</div>
-->

## 📝 Избранные проекты
<div align="center">
  <a href="https://github.com/ileztom/Apache-Logs-Aggregator">
    <img align="center" src="https://github.com/user-attachments/assets/83c7a4f5-30af-4f92-9813-c17a7126cd60" />
  </a>
</div>


- Java 
- JavaScript
- Python
- C#
- Postgres
- MySQL
- HTML/CSS

## ✅ Активность
<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ileztom&theme=tokyo-night&hide_border=true" alt="Contribution Graph" />
</div>



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
